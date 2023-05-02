![Bill of Materials Page 1](![Team 208 BOM xlsx - Sheet1-1](https://user-images.githubusercontent.com/93965371/235584370-83d68871-24fd-43c6-bfcd-4d8cadc4a723.png)

![Bill of Materials Page 2] (![Team 208 BOM xlsx - Sheet1-2](https://user-images.githubusercontent.com/93965371/235584490-64481f6c-d4e1-4fa9-9736-7c677d43359b.png)

![Bill of Materials Page 3](![Team 208 BOM xlsx - Sheet1-3](https://user-images.githubusercontent.com/93965371/235584532-2e7f0bda-51b2-472a-a73c-ed9b5c4287fe.png)

![Final Team Schematic] (![Team_V10-1](https://user-images.githubusercontent.com/93965371/235608571-b3fe81eb-43c1-4a5c-95eb-5cb1411b4ad4.png)
)

**Hardware Description:**
* Having a requirement of 5V for power input the LM2575 voltage regulatro takes in 5V and outputs that at 3.3 V. The power then goes to a barrel jack where the glove is plugged into in order to deliver power. SInce the pressure sensor is a passive resistor it outputs an analog signal. A ADC took the analog signal and converted into into a digital communication protocol so we could communicate with the glove using SPI. An array of 3 LEDs was connected to the temperature sensor. As the temperature increased the LEDs would light up, with a higher temperature corresponding to more LEDs lighting up. Using UART communication protocol the Motor driver enabled bidrectional movement of the motor. When the temperature or force applied was to high then the motor would trun and pull the resitive bands back, causing the fingers to be pulled back. The microcontroller could communicate in all required communication protocols in order to help the system run.  It had 44 pins with a mixture of GPIO and test points. The ESP32 allowed for communication to an MQTT server via WIFI. All parts with the exception of the ESP32 were surface mount components. 

![Front of Team PCB](![TSAP_V10_FRONT](https://user-images.githubusercontent.com/93965371/235584936-033eb9b9-9dda-40e4-a097-e38e64e9803d.png)

![BAck of Team PCB](![TSAP_V10_BACK](https://user-images.githubusercontent.com/93965371/235585057-340d5f08-fe59-4ed1-bea1-9b4dc06f512c.png)

![Full Team PCB] (![TSAP_V10](https://user-images.githubusercontent.com/93965371/235585417-8f05e2a2-1f07-4390-abd6-e963129dcafd.png)




Include an image of the team's final schematics as a figure in the report. you may use landscape mode on this page to better fit the format of the schematic.
Discuss how the functionality of this schematic satisfies user needs and product requirements though an in depth discussion of function.
Discuss your team's design and decision making process related to this section
Include the team's bill of materials in the appendix
Include front and back screenshots of the team's final PCB design.
Include front and back photos of the team's final PCB design.
If you were to create a "Version 2.0" of your hardware design, discuss what could be improved in the hardware design and why it should be improved. Use the schematic above to support the discussion. (½ page minimum)
