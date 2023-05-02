[<Back](https://team-208-github-io.github.io/Team-208/)

# Selected Design

**Design Description:**

The selected design is based mostly on the balloon grip sensor, with aspects from the other two designs.
This new design will have two force sensors on the end of the index finger and the inside of the thumb.
These sensors will be in place of the balloon pressure sensor. The team decided that the balloon would be too complex to manufacture and calibrate. 
The temperature sensor will be on the palm of the glove, this will sense if something is too hot to be touching. 
A motor on top of the wrist will pull on resistive bands attached to each finger when a person is exceeding a certain grip strength. 
Data from the sensors will be communicated wirelessly. The PCB itself will not be attached to the glove and instead be housed in a protective case external to the glove.
This external control box will have three LEDs on it to indicate user grip strength. 
The design will be powered by a wall power supply and is not designed to be worn casually. 
Instead this device will be designed to be used in physical therapy settings with people that have little to no feeling in their hands, due to nerve damage.

**CAD Assembly of Control Box Housing**

![image](https://user-images.githubusercontent.com/122938115/221493515-3aba4438-8e56-4616-96f7-1b0584720e98.jpg)


**CAD Exploded Assembly of Control Box Housing**

![image](https://user-images.githubusercontent.com/122938115/221493537-86941480-ffee-4bec-bd05-2a24b8fbc36a.jpg)

* Control Box Description: The control box will have two holes near the bottom. One for the signal, power, and ground wires that lead to the glove, and the other for the wall power supply. The box also features three holes for the three indicator LEDs. 

**Final Selected Design**

The final design is similar to the selected design, with only a few changes. One of the resistive bands was removed from the thumb due to the unique bone structure and movement range, as well as time constraints. Additionally, we had to update the sensor placement due to software issues. Originally, we had planned for one pressure sensor to be placed on the index finger and thumb, with the temperature sensor in the palm. However, we had to make a last-minute change and place the temperature sensor in the middle finger. This change was made to ensure that the motor on the top of the hand could pull the rubber bands back, relaxing the fingers and preventing injury to the user when they are grabbing something hot. The final look of the microcontroller housing was also different due to multiple 3D printing errors. The subsystems and electrical design are exactly the same as stated above.

**Drawing of Glove**

![Sketch](https://user-images.githubusercontent.com/122709159/221492312-4bd2967f-89b7-4071-b39c-6c4ea64a4dd8.png)

Key:
- White: Motor to control the fingers as they get pulled back
- Blue: Cables around the fingers and runnnign to motor

* Glove Description: The glove will feature force sensors on the index finger and the thumb, a temperature sensor on the inside of the palm, and a motor on the back of the hand. The motor will pull at the resistive bands on each finger. A cable will run from the glove to the control box that will provide power, ground, and signal transmission.
