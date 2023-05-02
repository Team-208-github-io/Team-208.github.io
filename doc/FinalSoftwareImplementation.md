[<Back](https://team-208-github-io.github.io/Team-208/)

# Final Software Implementation: 

![Software Proposal drawio](https://user-images.githubusercontent.com/122709159/235580754-affaf278-98c8-42ca-82ef-f57de9f3ae39.png)

**Description:**
* For this project we decided to break up our software proposal into multiple different sections as we believed it would be easier for readers of this report to understand\. Each section shows how that part will operate and what it does as well\. We have the main loop showing how the overall process will happen along with the chain showing how the wifi will communicate with UART and the ESP32 device\.  The LED loop shows how many LEDs will turn on depending on how much force is applied to an object by a user when they are wearing the glove\. Depending on how much force is applied either the green or the red LED will then turn on\. The team used only one interrupt to run the update motor function every second\. The indecation from either the red or green LED turning on will allow the user to know if they are applying to much pressure to a object andthis will serve as a warning preventing something from getting crsuhed or broken sastifying user needs\. The product requirements called for a device that can sense two different variables\. Our glove is able to sense both temperature and pressure\.




 `````  
#include <stdbool.h>
#include <stdint.h>
#include <stdio.h>
#include "mcc_generated_files/mcc.h"
#include "mcc_generated_files/spi2.h"
#include "mcc_generated_files/examples/i2c1_master_example.h"

#define address 0b1001100 //hex 0x4C //hex through hole 0x48
#define tempreg 0x00

void INIT_FULL_SYSTEM(void)
{
    //system init
    SYSTEM_Initialize();

    //resource init
    I2C1_Initialize();
    EUSART1_Initialize();
    SPI2_Initialize();
    I2C1_Initialize();
    PWM6_Initialize();
    
    //interrupt init
    INTERRUPT_GlobalInterruptEnable();
    INTERRUPT_PeripheralInterruptEnable();
}

void Update_LED_State(uint8_t tempc, uint8_t tempmax)
{
    //check if temp value in F is above danger threshold (85)
    if (tempc >= tempmax) {
        LED_1_SetHigh();
        LED_2_SetHigh();
        LED_3_SetHigh();
        __delay_ms(100);
        LED_1_SetLow();
        LED_2_SetLow();
        LED_3_SetLow();
        __delay_ms(100);

    } 
}
int Update_Motor(uint8_t tempc,uint8_t tempmax, int motorchange)
{
    
    if (motorchange <= 4500){
        if (tempc >= tempmax) {
            //MOTOR_CS_SetLow();
            //__delay_ms(50);
            
            PWM6_LoadDutyValue(1000);
            DIR_SetHigh();
            
           // MOTOR_CS_SetHigh();
            
            __delay_ms(2000);
            motorchange = motorchange+2000;
        }
    }else{
        //MOTOR_CS_SetLow();
        //__delay_ms(50);
        PWM6_LoadDutyValue(0);
        MOTOR_CS_SetHigh();
    }
   
    if (motorchange >= 0){
        if (tempc < tempmax) {
            //MOTOR_CS_SetLow();
            //__delay_ms(50);
            
            PWM6_LoadDutyValue(1000);
            DIR_SetLow();
            
            //MOTOR_CS_SetHigh();
            __delay_ms(1000);
            
            motorchange = motorchange-1000;
        }
    }
    else {
        //MOTOR_CS_SetLow();
        //__delay_ms(50);
        PWM6_LoadDutyValue(0);
        MOTOR_CS_SetHigh();
    }
    return motorchange;
}

uint8_t* read_Sensor_Values(void)
{  
    uint8_t tempc = 0;
    tempc = I2C1_Read1ByteRegister(address, tempreg);
    return tempc;
}

void ESP32_Send_Sensor_Data(uint8_t tempc)
{
     printf ("TEMP = %uC\r\n", tempc);
    __delay_ms(1000);    
}

void ESP32_motor_command(void){
    
    EUSART1_Receive_ISR();
    
  
    if (EUSART1_is_rx_ready()) {
        
        //LED_2_Toggle();
        unsigned char receivedByte = EUSART1_Read();
        int decimalNumber = (int)receivedByte;
        if (receivedByte == 99){
            DIR_SetHigh();
            //backward
        }
        if (receivedByte == 114){
            DIR_SetLow();
            //Forward
        }
        printf("Motor Speed changed to %d\r\n",receivedByte);
        
    } else {
        printf("RX PIN NOT READY\r\n COMMAND REJECTED\r\n");
    }  
}



void main(void)
{
    //Init system,resources,and interrupts
    INIT_FULL_SYSTEM();
   
    //all variables used in main loop
    uint8_t tempc;
    uint8_t tempmax = 30;
    EUSART1_SetRxInterruptHandler(ESP32_motor_command);
    int motorchange = 0;
    DIS_SetLow();
    __delay_ms(500);
    while (1)
       
    {
        //read all 4 sensor values into an array of 4 length
        tempc = read_Sensor_Values();
        
        //Updates LEDs based on sensor values
        Update_LED_State(tempc, tempmax);
       
        //updates motor with sensor values
        
        motorchange = Update_Motor(tempc, tempmax, motorchange);
        
        //printf("motorspeed: %d\r\n", motorspeed);
        //sends sensor data to mqtt server
        ESP32_Send_Sensor_Data(tempc);

    }
}
`````      
**MCC configuration setting：**

<img width="1279" alt="image" src="https://user-images.githubusercontent.com/122709159/235582326-1cb87efb-0ab6-4bb6-9de8-4c3422dfee22.png">

<img width="634" alt="image" src="https://user-images.githubusercontent.com/122709159/235582448-8322e45b-7432-4521-8e0e-3ecb381737d0.png">

<img width="631" alt="image" src="https://user-images.githubusercontent.com/122709159/235582464-fc8a8991-16d1-4f74-b896-e2c5411afd51.png">

<img width="633" alt="image" src="https://user-images.githubusercontent.com/122709159/235582479-eb2bd1c7-9d19-4173-aaf9-b7af810dced8.png">

<img width="627" alt="image" src="https://user-images.githubusercontent.com/122709159/235582494-bc6100e3-2940-4c34-b514-acadd31e97cb.png">

<img width="629" alt="image" src="https://user-images.githubusercontent.com/122709159/235582504-da03b92e-a1e9-40b7-b311-a00262da11ec.png">

**MQTT topic table setting：**

<img width="432" alt="image" src="https://user-images.githubusercontent.com/122709159/235581557-0d82040f-bf74-4ff4-b5c8-7444821b8827.png">


