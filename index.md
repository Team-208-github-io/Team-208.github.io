<div style="text-align: center">
<img src="https://user-images.githubusercontent.com/122709159/221691301-fc6a161e-1b05-4322-9fa3-a99ac9ab6c3f.jpg"/>
</div>

# Nerve Damage Therapy Glove

**EGR314 Spring Semester Project**

**Project Name: Nerve Damage Therapy Glove**

**Team 208**

**Team Members:**

1. _Felicia Szleszinski_
2. _Kyle Selasky_
3. _Miles Wilson_
4. _Mingqi Yu_

**Preparation date:** 02/26/2023 

**Organization Information:**

* University: _Arizona State University_ 
* Class: _EGR314: Embedded Systems Design Project II_
* Professor: _Daniel Aukes_

## [1. Team Organization](doc/TeamOrganization.md)

To be successful in our understanding of microcontroller programming while addressing how environmental sensing influences can affect real world applications in our final project.

Our team will create an embedded systems device that senses at least two environmental conditions. This device will have at least one controlled response that reacts based on the sensory data. All sensing and actuation will be accomplished using serial communication. Our device will be used to solve a real world problem and will be demonstrated at the Polytechnic innovation showcase to industry professionals. The team will stay within budget and within the requirements of the 314 course. Some, but not all, of these requirements are surface mount components only, using cadence only, and board communication over wifi.


## [2. User Needs, Benchmarking, and Requirements](doc/UserNeeds.md)

To complete user needs analysis, the team met online via Discord. This made sharing screens and files easy. Then we decided that Jamboard would be used to display and consolidate our ideas. Then each team member started to add user needs ideas to the board. No idea was rejected at first, all team members suggested and wrote whatever need they could think of. No team member rejected ideas at this point, this was merely to get a large pool of user needs on the table. Then we organized all the user needs into groups. This helped to reduce the number of repeat user needs in each category. Next, we ranked each section by how much the team valued them. Finally, we ranked every need in each category as well. This gave us a very good idea of what we value and absolutely need in the design. 

## [3. Product Requirements](doc/ProductRequirements.md)

The team decided that each major category of the product requirements will  be the major categories that our user needs are organized into. These groups are not the suggested groups, but we felt like these will better inform our design based on our user needs. This will make it easier to both rank and generate the product requirements as we come up with and design our concepts. The product requirement list below is organized from the most important major category at the top and least at the bottom. Within each category the top most product requirement is the most important of that category.

## [4. Design Ideation](doc/DesignIdeation.md)

![image](https://user-images.githubusercontent.com/122709159/224907563-c8e903c7-a6f2-4efb-92af-207290f267f0.png)

For our design ideation process we agreed on four main categories to focus on. They were electrical, movement, material, and miscellaneous. Then all team members started listing ideas for what the product should have based on the main categories. The best brainstorming method for us was Rapid Ideation. We looked at all of our benchmarked products and took the best from each of them while finding ways to improve them .Then we just started throwing everything we could think of onto the jamboard until we couldn't come up with any more ideas. Mind mapping didn't work for us as we started coming up with too many main ideas we wanted to focus on and was taking too much time. 

After coming up with all the ideas we then went through each one individually and determined whether we wanted to include it or not and whether or not they meant our requirements for the project. Miles drew the Balloon Grip Sensor Therapeutic Glove while Kyle drew the Variable Force Sensing Temperature/Pressure Glove and Mingqi did the Velcro on Fingers for Various Sizes.

## [5. Presentation 1](https://www.youtube.com/watch?v=2TSZasZKMRI)

![Jan  23 Checkpoint-1](https://user-images.githubusercontent.com/122709159/213969216-e0314781-86c9-40dc-9be9-0322e4fc1f9b.jpg)

[Video of Presentation 1](https://www.youtube.com/watch?v=2TSZasZKMRI)
 
## [7. Selected Design](doc/SelectedDesign.md)

The selected design is based mostly on the balloon grip sensor, with aspects from the other two designs. This new design will have two force sensors on the end of the index finger and the inside of the thumb. These sensors will be in place of the balloon pressure sensor. The team decided that the balloon would be too complex to manufacture and calibrate. The temperature sensor will be on the palm of the glove, this will sense if something is too hot to be touching. A motor on top of the wrist will pull on resistive bands attached to each finger when a person is exceeding a certain grip strength. Data from the sensors will be communicated wirelessly. The PCB itself will not be attached to the glove and instead be housed in a protective case external to the glove. This external control box will have three LEDs on it to indicate user grip strength. The design will be powered by a wall power supply and is not designed to be worn casually. Instead this device will be designed to be used in physical therapy settings with people that have little to no feeling in their hands, due to nerve damage.

## [8. Component Selection](doc/ComponentSelection.md)
After selecting our design, Team 208 determined the necessary components by comparing various pros and cons between different components. For each required component, three different options were compared to determine which would best suit our design. By listing three pros and cons, each team member was able to create justification for their selection.

## [9. Microcontroller Selection](doc/MicrocontrollerSelection.md)

Final Microcontroller Choice: PIC16F18875-I/P. After comparing the design of the three microcontrollers, Team 208 decided upon utilizing PIC16F18876. Despite having fewer built in SPI’s compared to the other options, the amount of available ADC pins as well as a multitude of design applications on Microchip's website made this microcontroller the perfect choice for our design. The 36 available IC pins allow for a larger amount of design flexibility when choosing how many sensors we will be implementing. These pins also allow for the flexibility of adding extra test points for future debugging. With the numerous documents on Microchip’s website and support, this chip was the best selection for our team.
 
## [10. Block Diagram](doc/BlockDiagram.md)
 
To deliver power to our nerve damage pressure glove we will be using a wall outlet that supplies 5V and 1A to power up the device and let it function. Power will pass into a voltage regulator where it will output at 3.3V and proceed to the microcontroller. The microcontroller will be connected to and receive data from all of our sensors. When a user holds on to something with the glove the thin film pressure sensors will relay that information back to the microcontroller via ADC which converts it into an SPI signal. Our ESP32 wifi module utilizes UART and can upload the information to the server at a medical facility or someone's phone.  

## [11. Hardware Proposal](doc/HardwareProposal.md)

The team schematic has been broken into sections to reduce confusion. There are six major sections in the team system. These are the switching voltage regulator, temperature sensor, LED array, motor driver, force sensors, and the microcontroller. Each section has arrows on the end of wires that connect to other sections. These arrows indicate the exact pin that wire should connect to.

## [12. Software Proposal](doc/SoftwareProposal.md)
 
For this project we decided to break up our software proposal into multiple different sections as we believed it would be easier for readers of this report to understand. Each section shows how that part will operate and what it does as well. We have the main loop showing how the overall process will happen along with the chain showing how the wifi will communicate with UART and the ESP32 device.  The LED loop shows how many LEDs will turn on depending on how much force is applied to an object by a user when they are wearing the glove. Depending on how much force is applied either the green or the red LED will then turn on. The team used only one interrupt to run the update motor function every second.

## [13. System Verification]

On the day of the innovation showcase, the final day to work on and present our design, only three out of four subsystems functioned. The force sensor subsystem didn't function due to the complexity of the ADC SPI chip used. The team never figured out SPI functionality for the motor driver as well. Because of this, for demonstration the team used PWN and DIR control of the motor driver. The temperature sensor, microcontroller, switching voltage regulator, and ESP32 subsystems all functioned as intended. An inturrupt was used to control the motor via incoming message from the MQTT server.

## [14. Lessons Learned]

* Datasheets should be read in full before buying/selecting a component.
* If possible computer simulations of circuits should be used before a prototype is made.
* Complexity is a killer, keep it simple.

## [15. Recommendations for Future Students]

1. Cadence is not KiCad, it is far worse. Read lots of documentation and always ask for help from the TA's.
2. l
3. l
4. l
5. l
 
## Appendix A

[Link to "Team 208's Charter"](https://github.com/Team-208-github-io/Team-208/files/10844546/Team.208.s.Charter.pdf)

[Link to "Team 208's User Needs and Benchmarking"](https://github.com/Team-208-github-io/Team-208/files/10856865/User.Needs.and.Benchmarking.pdf)

[Link to "Team 208's Design Ideation"](https://github.com/Team-208-github-io/Team-208/files/10856875/Design.Ideation.pdf)

[Link to "Team 208's Block Diagram"](https://github.com/Team-208-github-io/Team-208/files/10964667/Block.Diagram-314.drawio.pdf)

[Link to "Team 208's Component Selection"](https://github.com/Team-208-github-io/Team-208/files/10856889/Component.Selection.pdf)

[Link to "Team 208's Microcontroller Selection"](https://github.com/Team-208-github-io/Team-208/files/10856890/microcontroller-selection-table.docx.pdf)

[Link to "Team 208's Software Proposal"](https://github.com/Team-208-github-io/Team-208/files/10964668/Software.Proposal.drawio.1.pdf)

[Link to "Team 208's Hardware Proposal"](https://github.com/Team-208-github-io/Team-208/files/10964653/Hardware.Proposal.pdf)

[Link to "Team 208's Verification Table"](https://github.com/Team-208-github-io/Team-208/files/10856922/Verification.Table.-.Sheet1.pdf)

[Link to "Team 208's Team 208 BOM"](https://github.com/Team-208-github-io/Team-208/files/10856927/Team.208.BOM.xlsx.-.Sheet1.pdf)

[Link to "Team 208's Team and Individual Cadence Subsystems"](https://drive.google.com/drive/folders/13jUH9Vl2aOTExGctnM7fT20rFPp-uSIZ?usp=sharing)

[Link to "Team 208's Jan. 26 MPLAB"](https://drive.google.com/file/d/1nDP8JixQ91Ch6AFLqdIlS3i-IN7m-84g/view?usp=share_link) 

[Link to "Team 208's Jan. 23 Checkpoint-1"](https://docs.google.com/presentation/d/1hgJn6WouZ5ktR1tikmxeMw9MUZq5OlJOVkCAVtTWgRQ/edit?usp=sharing)


Date: 02/26/2023 
