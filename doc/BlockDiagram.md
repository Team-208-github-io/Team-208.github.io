[<Back](https://team-208-github-io.github.io/Team-208/)

# Block Diagram

![image](https://user-images.githubusercontent.com/122709159/221494593-0db435db-6eb4-408a-84d6-0cdc903214d1.png)

**Description:**
* To deliver power to our nerve damage pressure glove we will be using a wall outlet that supplies 5V and 1A to power up the device and let it function. Power will pass into a voltage regulator where it will output at 3.3V and proceed to the microcontroller. The microcontroller will be connected to and receive data from all of our sensors. When a user holds on to something with the glove the thin film pressure sensors will relay that information back to the microcontroller via ADC which converts it into an SPI signal. Our ESP32 wifi module utilizes UART and can upload the information to the server at a medical facility or someone's phone.  
