![asu](https://user-images.githubusercontent.com/122709159/213967775-f1117c93-3efb-41ed-b1aa-34e423750c9c.png)

remote_theme: benbalter/retlab

## EGR314 Spring Semester Project
 
**Team 208**

**Project name: Nerve damage therapy glove**

**Team members:**

1. _Felicia Szleszinski_
2. _Kyle Selasky_
3. _Miles Wilson_
4. _Mingqi Yu_

**Preparation date:** 1/22/2023 

**Organisation information:**

* University: _Arizona State University_ 
* Class: _EGR314: Embedded Systems Design Project II_
* Professor: _Dan Aukes_

## 1. Team Organization

**Charter:**
* To be successful in our understanding of microcontroller programming while addressing how environmental sensing influences can affect real world applications in our final project.

**Product Mission Statement:**
* Our team will create an embedded systems device that senses at least two environmental conditions. This device will have at least one controlled response that reacts based on the sensory data. All sensing and actuation will be accomplished using serial communication. Our device will be used to solve a real world problem and will be demonstrated at the Polytechnic innovation showcase to industry professionals. The team will stay within budget and within the requirements of the 314 course. Some, but not all, of these requirements are surface mount components only, using cadence only, and board communication over wifi.


## 2. User Needs, Benchmarking, and Requirements
**Our Process:**
* To complete user needs analysis, the team met online via Discord. This made sharing screens and files easy. Then we decided that Jamboard would be used to display and consolidate our ideas. Then each team member started to add user needs ideas to the board. No idea was rejected at first, all team members suggested and wrote whatever need they could think of. No team member rejected ideas at this point, this was merely to get a large pool of user needs on the table. Then we organized all the user needs into groups. This helped to reduce the number of repeat user needs in each category. Next, we ranked each section by how much the team valued them. Finally, we ranked every need in each category as well. This gave us a very good idea of what we value and absolutely need in the design. 

![user needs ranked](https://user-images.githubusercontent.com/122709159/213968878-697e78d0-26be-4114-b271-7d2dc2a9d990.jpg)

## 3. Design Ideation

![1](https://user-images.githubusercontent.com/122709159/213965963-f8247255-c0f5-45f7-b8b9-de3b4387599c.png) 

* For our design ideation process we agreed on four main categories to focus on. They were electrical, movement, material, and miscellaneous. Then all team members started listing ideas for what the product should have based on the main categories. The best brainstorming method for us was Rapid Ideation. We looked at all of our benchmarked products and took the best from each of them while finding ways to improve them .Then we just started throwing everything we could think of onto the jamboard until we couldn't come up with any more ideas. Mind mapping didn't work for us as we started coming up with too many main ideas we wanted to focus on and was taking too much time. 

![3](https://user-images.githubusercontent.com/122709159/213966327-d724d5fc-da0b-442a-a4be-13c727f222c8.png)

* After coming up with all the ideas we then went through each one individually and determined whether we wanted to include it or not and whether or not they meant our requirements for the project. Miles drew the Balloon Grip Sensor Therapeutic Glove while Kyle drew the Variable Force Sensing Temperature/Pressure Glove and Mingqi did the Velcro on Fingers for Various Sizes.

---
**Balloon Grip Sensor Therapeutic Glove**
---
![Balloon Grip Sensor Therapeutic Glove](https://user-images.githubusercontent.com/122709159/213966462-f60028a3-5916-4f63-95ae-82ab78ccc513.png)
---
**Variable Force Sensing Temperature Pressure Glove**
---
![Variable Force Sensing Temperature Pressure Glove](https://user-images.githubusercontent.com/122709159/213966564-2cba5767-babe-4e55-85ea-b9585db0051f.png)
--- 
**Velcro on Fingers for Various Sizes**
---
![Velcro on Fingers for Various Sizes](https://user-images.githubusercontent.com/122709159/213966611-4041dacc-41a9-4ff9-aeaa-34a482402d6a.jpg)
---

## 4. Presentation 1

![Jan  23 Checkpoint-1](https://user-images.githubusercontent.com/122709159/213969216-e0314781-86c9-40dc-9be9-0322e4fc1f9b.jpg)

[Video of Presentation 1](https://www.youtube.com/watch?v=2TSZasZKMRI)
 
## 5. Selected Design

* The selected design is based mostly on the balloon grip sensor, with aspects from the other two designs. This new design will have two force sensors on the end of the index finger and the inside of the thumb. These sensors will be in place of the balloon pressure sensor. The team decided that the balloon would be too complex to manufacture and calibrate. The temperature sensor will be on the palm of the glove, this will sense if something is too hot to be touching. A motor on top of the wrist will pull on resistive bands attached to each finger when a person is exceeding a certain grip strength. Data from the sensors will be communicated wirelessly. The PCB itself will not be attached to the glove and instead be housed in a protective case external to the glove. This external control box will have three LEDs on it to indicate user grip strength. The design will be powered by a wall power supply and is not designed to be worn casually. Instead this device will be designed to be used in physical therapy settings with people that have little to no feeling in their hands, due to nerve damage.

 
## 6. Component Selection

## 7. Microcontroller Selection
 
## 8. Block Diagram
 
*  To deliver power to our nerve damage pressure glove we will be using a wall outlet that supplies 5V and 1A to power up the device and let it function. Power will pass into a voltage regulator where it will output at 3.3V and proceed to the microcontroller. The microcontroller will be connected to and receive data from all of our sensors. When a user holds on to something with the glove the thin film pressure sensors will relay that information back to the microcontroller via ADC which converts it into an SPI signal. Our ESP32 wifi module utilizes UART and can upload the information to the server at a medical facility or someone's phone.  
 
## 9. Hardware Proposal
 
* The team schematic has been broken into sections to reduce confusion. There are six major sections in the team system. These are the switching voltage regulator, temperature sensor, LED array, motor driver, force sensors, and the microcontroller. Each section has arrows on the end of wires that connect to other sections. These arrows indicate the exact pin that wire should connect to.

## 10. Software Proposal
 
* For this project we decided to break up our software proposal into multiple different sections as we believed it would be easier for readers of this report to understand. Each section shows how that part will operate and what it does as well. We have the main loop showing how the overall process will happen along with the chain showing how the wifi will communicate with UART and the ESP32 device.  The LED loop shows how many LEDs will turn on depending on how much force is applied to an object by a user when they are wearing the glove. Depending on how much force is applied either the green or the red LED will then turn on. The team used only one interrupt to run the update motor function every second.

 
## Appendix A

[Link to "Team 208's Charter"](https://docs.google.com/document/d/1KnbiiMYb2K0HKReNCJJwkJIaMzlF_pRPQoaXfeS1aX0/edit?usp=sharing)

[Link to "Team 208's User Needs and Benchmarking"](https://docs.google.com/document/d/1yNhMk36OD9xKp0WGD0XdSZ_GKACv3c8gfcodrc5hSE0/edit?usp=sharing)

[Link to "Team 208's Design Ideation"](https://docs.google.com/document/d/1rwlRUkhHN8_KuPjEGyNR5eVbSKwuBbHuJvOcQV-REok/edit?usp=sharing)

[Link to "Team 208's Jan. 23 Checkpoint-1"](https://docs.google.com/presentation/d/1hgJn6WouZ5ktR1tikmxeMw9MUZq5OlJOVkCAVtTWgRQ/edit?usp=sharing)


Date: 1/22/2023 

plugins:
  - jekyll-feed
  - jekyll-paginate
  - jekyll-sitemap
  - jemoji
  - jekyll-remote-theme
