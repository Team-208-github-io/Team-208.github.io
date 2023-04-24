
[<Back](https://team-208-github-io.github.io/Team-208/)

# Block Diagram

![Final Block Diagram-1](https://user-images.githubusercontent.com/93965371/234103237-aca36fb2-8937-4e8e-8a5d-d2c0bb4f0fea.png)



**Description:**
* To deliver power to our nerve damage pressure glove we will be using a wall outlet that supplies 5V and 1A to power up the device and let it function. Power will pass into a voltage regulator where it will output at 3.3V and proceed to the microcontroller. The microcontroller will be connected to and receive data from all of our sensors. When a user holds on to something with the glove the thin film pressure sensors will relay that information back to the microcontroller via ADC which converts it into an SPI signal. Our ESP32 wifi module utilizes UART and can upload the information to the server at a medical facility or someone's phone.  
