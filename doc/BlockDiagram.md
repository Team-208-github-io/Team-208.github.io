
[<Back](https://team-208-github-io.github.io/egr314-team208.github.io/)

# Block Diagram

![Final Block Diagram-1](![Block Diagram_V4](https://user-images.githubusercontent.com/93965371/235585882-9bcac0f9-3372-46cd-b35b-27db9dcc84db.png)




**Description:**
To deliver power to our nerve damage pressure glove we will be using a wall outlet that supplies 5V and 1A to power up the device and let it function. Power will pass into a voltage regulator where it will output at 3.3V and proceed to the microcontroller. The microcontroller will be connected to and receive data from all of our sensors. When a user holds on to something with the glove the thin film pressure sensors will relay that information back to the microcontroller via ADC which converts it into an SPI signal. Our ESP32 wifi module utilizes UART and can upload the information to the server at a medical facility or someone's phone.  

 When revising our block diagram, we received feedback aimed at enhancing our design. In order to confirm that our project requirements were being met, we ensured that the bidirectional communication blocks had bidirectional arrows, consolidated the SPI and I2C blocks into one block per subsystem, and indicated that the 5V power was separate from the main subsystems.

By incorporating these changes, we were able to provide a more precise depiction of how our design would operate and be controlled, ensuring that it met our project requirements.
