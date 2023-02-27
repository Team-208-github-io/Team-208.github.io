<!-- Copy and paste the converted output. -->

<!-----

You have some errors, warnings, or alerts. If you are using reckless mode, turn it off to see inline alerts.
* ERRORs: 0
* WARNINGs: 0
* ALERTS: 60

Conversion time: 21.894 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Sun Feb 26 2023 23:29:58 GMT-0800 (PST)
* Source doc: Report
* Tables are currently converted to HTML tables.
* This document has images: check for >>>>>  gd2md-html alert:  inline image link in generated source and store images to your server. NOTE: Images in exported zip file from Google Docs may not appear in  the same order as they do in your doc. Please check the images!


WARNING:
You have 24 H1 headings. You may want to use the "H1 -> H2" option to demote all headings by one level.

----->


<p style="color: red; font-weight: bold">>>>>>  gd2md-html alert:  ERRORs: 0; WARNINGs: 1; ALERTS: 60.</p>
<ul style="color: red; font-weight: bold"><li>See top comment block for details on ERRORs and WARNINGs. <li>In the converted Markdown or HTML, search for inline alerts that start with >>>>>  gd2md-html alert:  for specific instances that need correction.</ul>

<p style="color: red; font-weight: bold">Links to alert messages:</p><a href="#gdcalert1">alert1</a>
<a href="#gdcalert2">alert2</a>
<a href="#gdcalert3">alert3</a>
<a href="#gdcalert4">alert4</a>
<a href="#gdcalert5">alert5</a>
<a href="#gdcalert6">alert6</a>
<a href="#gdcalert7">alert7</a>
<a href="#gdcalert8">alert8</a>
<a href="#gdcalert9">alert9</a>
<a href="#gdcalert10">alert10</a>
<a href="#gdcalert11">alert11</a>
<a href="#gdcalert12">alert12</a>
<a href="#gdcalert13">alert13</a>
<a href="#gdcalert14">alert14</a>
<a href="#gdcalert15">alert15</a>
<a href="#gdcalert16">alert16</a>
<a href="#gdcalert17">alert17</a>
<a href="#gdcalert18">alert18</a>
<a href="#gdcalert19">alert19</a>
<a href="#gdcalert20">alert20</a>
<a href="#gdcalert21">alert21</a>
<a href="#gdcalert22">alert22</a>
<a href="#gdcalert23">alert23</a>
<a href="#gdcalert24">alert24</a>
<a href="#gdcalert25">alert25</a>
<a href="#gdcalert26">alert26</a>
<a href="#gdcalert27">alert27</a>
<a href="#gdcalert28">alert28</a>
<a href="#gdcalert29">alert29</a>
<a href="#gdcalert30">alert30</a>
<a href="#gdcalert31">alert31</a>
<a href="#gdcalert32">alert32</a>
<a href="#gdcalert33">alert33</a>
<a href="#gdcalert34">alert34</a>
<a href="#gdcalert35">alert35</a>
<a href="#gdcalert36">alert36</a>
<a href="#gdcalert37">alert37</a>
<a href="#gdcalert38">alert38</a>
<a href="#gdcalert39">alert39</a>
<a href="#gdcalert40">alert40</a>
<a href="#gdcalert41">alert41</a>
<a href="#gdcalert42">alert42</a>
<a href="#gdcalert43">alert43</a>
<a href="#gdcalert44">alert44</a>
<a href="#gdcalert45">alert45</a>
<a href="#gdcalert46">alert46</a>
<a href="#gdcalert47">alert47</a>
<a href="#gdcalert48">alert48</a>
<a href="#gdcalert49">alert49</a>
<a href="#gdcalert50">alert50</a>
<a href="#gdcalert51">alert51</a>
<a href="#gdcalert52">alert52</a>
<a href="#gdcalert53">alert53</a>
<a href="#gdcalert54">alert54</a>
<a href="#gdcalert55">alert55</a>
<a href="#gdcalert56">alert56</a>
<a href="#gdcalert57">alert57</a>
<a href="#gdcalert58">alert58</a>
<a href="#gdcalert59">alert59</a>
<a href="#gdcalert60">alert60</a>

<p style="color: red; font-weight: bold">>>>>> PLEASE check and correct alert issues and delete this message and the inline alerts.<hr></p>



# Nerve Damage Therapy Glove Project

By: Kyle Selasky, Felicia Szleszinski, Miles Wilson, Mingqi Yu

Team Number: 208

Class: EGR 314

Date: 2/26/2023


# 


# Table Of Contents:



1. 
Team 208 Charter—---------------------------------------------------------------------------------2


    1. Charter	—-------------------------------------------------------------------------------------2
    2. Product Mission Statement—--------------------------------------------------------------2



2. 
User Needs—-----------------------------------------------------------------------------------------2


    3. Benchmarking	—----------------------------------------------------------------------------3
    4. Organizing Need Statements—------------------------------------------------------------3



3. 
Product Requirements	—----------------------------------------------------------------------------5


    5. Aspects—-------------------------------------------------------------------------------------5



4. 
Design Ideation—------------------------------------------------------------------------------------6


    6. Ranked Ideas—------------------------------------------------------------------------------7
    7. Design Concepts—--------------------------------------------------------------------------8



5. 
Selected Design—----------------------------------------------------------------------------------11


6. 
Block Diagram—-----------------------------------------------------------------------------------13


7. 
List of Major Components—----------------------------------------------------------------------14


8. 
Microcontroller Selection—-----------------------------------------------------------------------15


9. 
Software Proposal—-------------------------------------------------------------------------------21


10. 
Hardware Proposal—-------------------------------------------------------------------------------22


11. 
Appendix A: Team 208’s Charter—--------------------------------------------------------------23


12. 
Appendix B: User Needs and Benchmarking—------------------------------------------------28


13. 
Appendix C: Design Ideation—------------------------------------------------------------------52


14. 
Appendix D: Verification Table—----------------------------------------------------------------60


15. 
Appendix E: Component Selection—------------------------------------------------------------60


16. 
Appendix F: Power Budget—---------------------------------------------------------------------80

# 


# Team 208 Charter: 


## Charter

Based on the goals listed above and through a team discussion, we constructed the following charter:

_To be successful in our understanding of microcontroller programming while addressing how environmental sensing influences can affect real world applications in our final project._


## Product Mission Statement

Based on the project description and project requirements, Team 208 has come up with the following mission statement:

_Our team will create an embedded systems device that senses at least two environmental conditions. This device will have at least one controlled response that reacts based on the sensory data. All sensing and actuation will be accomplished using serial communication. Our device will be used to solve a real world problem and will be demonstrated at the Polytechnic innovation showcase to industry professionals. The team will stay within budget and within the requirements of the 314 course. Some, but not all, of these requirements are surface mount components only, using cadence only, and board communication over wifi._


# <span style="text-decoration:underline;">User Needs: </span>

**Our Process: **To complete user needs analysis, the team met online via Discord. This made sharing screens and files easy. Then we decided that Jamboard would be used to display and consolidate our ideas. Then each team member started to add user needs ideas to the board. No idea was rejected at first, all team members suggested and wrote whatever need they could think of. No team member rejected ideas at this point, this was merely to get a large pool of user needs on the table. Then we organized all the user needs into groups. This helped to reduce the number of repeat user needs in each category. Next, we ranked each section by how much the team valued them. Finally, we ranked every need in each category as well. This gave us a very good idea of what we value and absolutely need in the design.  Based on the reviews the team saw on Amazon and other websites we then compiled and created a list of needs to suit the requirements of our product requirement


## Benchmarking:

**Our Process: **The team met on Discord again to do the benchmarking. First we agreed that we would look up ideas relating to Parkinson’s or nerve damage therapy relating to the hand. This produced a few different products that the team thought were interesting and helpful. We analyzed the positive and negative comments on each product to get more needs/ wants/ and pain points directly from users. The team’s plan was to review these products and find ways to incorporate the best parts of them into our own design and eliminate any potential pain points. 


## Organizing Need Statements


    Initial Notes:


    

<p id="gdcalert1" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image1.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert2">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image1.png "image_tooltip")



    Grouped Notes:


    Key:


<table>
  <tr>
   <td>
    Color
   </td>
   <td>
    Meaning
   </td>
  </tr>
  <tr>
   <td>
    Yellow
   </td>
   <td>
    100 User Needs
   </td>
  </tr>
  <tr>
   <td>
    Blue
   </td>
   <td>
    Category 
   </td>
  </tr>
</table>



    

<p id="gdcalert2" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image2.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert3">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image2.png "image_tooltip")



    Ranked Notes:


    Key:


<table>
  <tr>
   <td>
    3 Stars
   </td>
   <td>
    2 Stars
   </td>
   <td>
    1 Star
   </td>
  </tr>
  <tr>
   <td>
    Very Important 
   </td>
   <td>
    Important 
   </td>
   <td>
    Less Important 
   </td>
  </tr>
</table>



    

<p id="gdcalert3" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image3.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert4">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image3.png "image_tooltip")



# Product Requirements

**Our Process:** The team decided that each major category of the product requirements will  be the major categories that our user needs are organized into. These groups are not the suggested groups, but we felt like these will better inform our design based on our user needs. This will make it easier to both rank and generate the product requirements as we come up with and design our concepts. The product requirement list below is organized from the most important major category at the top and least at the bottom. Within each category the top most product requirement is the most important of that category.

**Stakeholders:**

Target Users: People with nerve damage or limited mobility in the hand.

Target Purchasers: This can be the target user directly or healthcare professionals for use in a medical/ rehabilitation facility.

Sponsor and Advisors: ASU acts as a financial sponsor. EGR314 and Professor Aukes act as advisors to the final product.


## Aspects:



1. **Safety (***):**

    1.1) The product’s structural components must not pinch, cut, or injure the user. 


    1.2) The product should be made out of regulatory compliant and sterile materials.


    1.3) All electrical components should be sealed, hidden, or inaccessible to the user.


    1.4) A temperature sensor should sense if the user is holding something hot.


    1.5) The product should generally move slowly and not require high voltages, this will keep total energy low.

2. **Ease of Use (***):**

    2.1) The product should be able to be used by any type of user regardless of age, hand size, strength, or mobility.


    2.2) The product should adjust to fit any user.


    2.3) Using the product should be easy to understand and use.


    2.4) The multiple indicators on the product should not be loud or annoying, but still noticeable and understandable to the user.


    2.5) The product should be easy to manufacture, assemble, disassemble, and clean.

3. **Functionality (**):**

    3.1) The product will sense and relay the temperature of a gripped object and the grip strength force in real time.


    3.2) The product will use a motor to resist user grip strength if it exceeds an acceptable limit in real time.


    3.3) The product should be less than $240 and affordable for the average user.


    3.4) The product should be therapeutic for the user and slowly increase hand functionality over time.

4. **Electronics (**):**

	4.1) All electronics should meet the requirements for EGR314.

	4.2) The product should have enough power for at least 2-4 hours of use.

	4.3) The power supply should be completely internal or supplied by a USB-c connection.


    4.4) The product should respond to sensor data in an accurate, fast, and controlled manner.



5. **Durability (*):**

5.1) The product should be water, heat, and impact resistant.

5.2) The product should be made out of durable materials for a long product lifespan.

5.3) The product should utilize easily replaceable parts.

5.4) Any balloon or enclosed air pocket should be puncture resistant.



6. **Comfort (*):**

6.1) The product should be comfortable and should not chafe during extended use.

6.2) The product should be able to fit most size hands.



7. **Misc. (*):**

	7.1) Amount of remaining power should be visible to the user.

	7.2) The product life cycle should be considered when designing the product.

	7.3) A screen should communicate data and information to the user.

	7.4) The product should be stylish for the user.


# Design Ideation

**Idea Generation Process:** For Team 208’s Design Ideation, we chose to look at what characteristics made our benchmarked examples successful products and how they could be improved upon. Listed below are one hundred ideas that discuss various aspects of potential design movements, material considerations, electrical component ideas, and other other potential successful characteristics. Once we had generated one hundred ideas, they were separated then into color coordinated categories and grouped  based on their ability to meet our project requirements. 


### **Legend:** 



<p id="gdcalert4" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image4.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert5">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image4.png "image_tooltip")



## Ranked Ideas:



<p id="gdcalert5" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image5.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert6">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image5.png "image_tooltip")


**Description: **The ideas were ranked by group vote. The #1 choice was picked due to it meeting the most product requirements and user need expectations.


## 


## Design Concepts:

**Balloon Grip Sensor Therapeutic Glove:**



<p id="gdcalert6" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image6.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert7">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image6.png "image_tooltip")


**Description:** This concept will be tethered to a wall power supply to avoid the need for a battery. The wall power supply will then go to a control box that houses our PCB. This will protect the PCB and make the glove design more streamlined. This box will have LED indicators to display how hard someone is gripping. The glove will have a balloon with a pressure sensor inside it to measure the grip strength of someones hand. The motor on the back of the hand will increase tension in the glove if a person is gripping too hard, and release if they decrease grip strength. This design will meet all class requirements. This design will also feature a temperature sensor that can indicate if someone is gripping something too hot.

**Variable Force Sensing Temperature/Pressure Glove**



<p id="gdcalert7" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image7.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert8">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image7.png "image_tooltip")


**Description: **This design will be battery powered for extra mobility. It will be fully enclosed in the glove and will not have any external parts. A compression sleeve on each finger will be the actuator. These will relax the fingers when someone is gripping too hard. LED indicators on the side of the glove will indicate grip strength. There will also be a LED screen for easy viewing of data. This design meets all class requirements.

**Velcro on Fingers for Various Sizes**




<p id="gdcalert8" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image8.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert9">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image8.jpg "image_tooltip")



# Selected Design

**Design Description:** The selected design is based mostly on the balloon grip sensor, with aspects from the other two designs. This new design will have two force sensors on the end of the index finger and the inside of the thumb. These sensors will be in place of the balloon pressure sensor. The team decided that the balloon would be too complex to manufacture and calibrate. The temperature sensor will be on the palm of the glove, this will sense if something is too hot to be touching. A motor on top of the wrist will pull on resistive bands attached to each finger when a person is exceeding a certain grip strength. Data from the sensors will be communicated wirelessly. The PCB itself will not be attached to the glove and instead be housed in a protective case external to the glove. This external control box will have three LEDs on it to indicate user grip strength. The design will be powered by a wall power supply and is not designed to be worn casually. Instead this device will be designed to be used in physical therapy settings with people that have little to no feeling in their hands, due to nerve damage.

**CAD Assembly of Control Box Housing**



<p id="gdcalert9" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image9.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert10">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image9.jpg "image_tooltip")


**CAD Exploded Assembly of Control Box Housing**



<p id="gdcalert10" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image10.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert11">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image10.jpg "image_tooltip")


**Control Box Description:** The control box will have two holes near the bottom. One for the signal, power, and ground wires that lead to the glove, and the other for the wall power supply. The box also features three holes for the three indicator LEDs. 

**Drawing of Glove**



<p id="gdcalert11" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image11.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert12">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image11.png "image_tooltip")


**Glove Description:** The glove will feature force sensors on the index finger and the thumb, a temperature sensor on the inside of the palm, and a motor on the back of the hand. The motor will pull at the resistive bands on each finger. A cable will run from the glove to the control box that will provide power, ground, and signal transmission.


# Block Diagram:



<p id="gdcalert12" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image12.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert13">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image12.png "image_tooltip")


**Description:** To deliver power to our nerve damage pressure glove we will be using a wall outlet 


    that supplies 5V and 1A to power up the device and let it function. Power will pass into a voltage regulator where it will output at 3.3V and proceed to the microcontroller. The microcontroller will be connected to and receive data from all of our sensors. When a user holds on to something with the glove the thin film pressure sensors will relay that information back to the microcontroller via ADC which converts it into an SPI signal. Our ESP32 wifi module utilizes UART and can upload the information to the server at a medical facility or someone's phone.  


# List of Major Components:


<table>
  <tr>
   <td><strong>Part Name/Description</strong>
   </td>
  </tr>
  <tr>
   <td>Temperature Sensor Digital BOM
   </td>
  </tr>
  <tr>
   <td>0.1 µF Ceramic Capacitor, +/-10%, X7R, 50V, 0805 package
   </td>
  </tr>
  <tr>
   <td>10K Ohm resistor surface mount
   </td>
  </tr>
  <tr>
   <td>Temperature Sensor Digital
   </td>
  </tr>
  <tr>
   <td>Barrel Jack
   </td>
  </tr>
  <tr>
   <td>4.7K Ohm resistor surface mount
   </td>
  </tr>
  <tr>
   <td>
   </td>
  </tr>
  <tr>
   <td>Shared Test Points BOM
   </td>
  </tr>
  <tr>
   <td>Test Points
   </td>
  </tr>
  <tr>
   <td>LED - Green
   </td>
  </tr>
  <tr>
   <td>220 Ohm resistor surface mount
   </td>
  </tr>
  <tr>
   <td>
   </td>
  </tr>
  <tr>
   <td>Motor and Motor Driver BOM
   </td>
  </tr>
  <tr>
   <td>0.033 µF ±10% 25V Ceramic Capacitor X7R 0805
   </td>
  </tr>
  <tr>
   <td>CAP ALUM 100UF 20% 25V SMD
   </td>
  </tr>
  <tr>
   <td>0.1 µF ±10% 50V Ceramic Capacitor X7R 1206
   </td>
  </tr>
  <tr>
   <td>40V 100Ma Diode
   </td>
  </tr>
  <tr>
   <td>Connector Header Through Hole 6 position 0.098" (2.50mm)
   </td>
  </tr>
  <tr>
   <td>Connector Header Through Hole 12 position 0.100" (2.54mm)
   </td>
  </tr>
  <tr>
   <td>5V DC MOTOR
   </td>
  </tr>
  <tr>
   <td>Full Half-Bridge Drivers
   </td>
  </tr>
  <tr>
   <td>
   </td>
  </tr>
  <tr>
   <td>Microcontroller and Voltage Regulator BOM
   </td>
  </tr>
  <tr>
   <td>LM2575 Voltage Regulator
   </td>
  </tr>
  <tr>
   <td>WSU050-4000 AC/DC Convertor
   </td>
  </tr>
  <tr>
   <td>PIC16F18876-I/PT Microcontroller
   </td>
  </tr>
  <tr>
   <td>
   </td>
  </tr>
  <tr>
   <td>Force Sensor
   </td>
  </tr>
  <tr>
   <td>IC ADC 24BIT SIGMA-DELTA 20TSSOP
   </td>
  </tr>
  <tr>
   <td>Op-Amp for Force Sensor
   </td>
  </tr>
  <tr>
   <td>Sensors RoHS
   </td>
  </tr>
  <tr>
   <td>1K Ohm resistor surface mount
   </td>
  </tr>
  <tr>
   <td>
   </td>
  </tr>
</table>


**Description:** The bill of materials contains all the parts each section of the nerve damage therapy glove will be utilizing. All parts meet the requirements and unless specified otherwise are surface mounted.  Everything from the voltage regulators to the OP-AMP and even our resistors and capacitors are surface-mounted. The only parts that aren’t surface mounted are the barrel jack, motor, microcontroller, and wall plug to supply power to the device.  A variety of communication methods are utilized such as SPI, UART, and I2C.  Our wall power supply supplies voltage at a measurement of 5V and 1A to a switching voltage regulator. From the switching voltage regulator the power drops down and comes out to 3.3 V. Our force sensors are resistive which utilize an ADC device to convert their analog signals to SPI so it can be read by the microcontroller. The ESP32 utilizes UART to communicate all this data over wifi to a digital storage space such as someone’s personal device or the medical records system at a doctor’s office. 


# Microcontroller Selection:


<table>
  <tr>
   <td colspan="2" ><strong>1. Determine your project-specific requirements</strong>
   </td>
   <td colspan="3" ><strong>3. Look up specifications in the PIC datasheet</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Design Considerations</strong>
   </td>
   <td><strong>Team Project-Specific Requirements </strong>
<p>
from Problem Definition and Block Diagram
   </td>
   <td><strong>PIC Option 1</strong>
   </td>
   <td><strong>PIC Option 2</strong>
   </td>
   <td><strong>PIC Option 3</strong>
   </td>
  </tr>
  <tr>
   <td>How many GPIO Pins?[^1]
   </td>
   <td>5 SPI+2*2 I2C+ 2 UART = 11 pins total
   </td>
   <td><strong>28</strong>
   </td>
   <td><strong>80</strong>
   </td>
   <td><strong>40</strong>
   </td>
  </tr>
  <tr>
   <td>Built-in Analog to Digital Converter? How many?
   </td>
   <td>0
   </td>
   <td><strong>6</strong>
   </td>
   <td><strong>1</strong>
   </td>
   <td><strong>2</strong>
   </td>
  </tr>
  <tr>
   <td>Built-in Hardware PWM? How many?
   </td>
   <td>0
   </td>
   <td><strong>0</strong>
   </td>
   <td><strong>0</strong>
   </td>
   <td><strong>2</strong>
   </td>
  </tr>
  <tr>
   <td>Built-in I2C? SPI? How many?
   </td>
   <td>I2C: 2 (Temp sensor, motor driver), SPI: 1 (Force sensor)
   </td>
   <td><strong>SPI:2 I2C: 2</strong>
   </td>
   <td><strong>SPI: 4</strong>
<p>
<strong>I2C: 3 </strong>
   </td>
   <td><strong>SPI:2</strong>
<p>
<strong>I2C:2</strong>
   </td>
  </tr>
  <tr>
   <td>Built-in UART? How many?
   </td>
   <td>1 (MQTT Server)
   </td>
   <td><strong>UART:2</strong>
   </td>
   <td><strong>UART: 6</strong>
   </td>
   <td><strong>UART:2</strong>
   </td>
  </tr>
  <tr>
   <td>Other Required Built-In Features? <em>(optional)</em>
   </td>
   <td>None currently
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Additional considerations specific to your project specifications <em>(optional)</em>
   </td>
   <td>None currently
   </td>
   <td>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td colspan="2" ><strong>2. Find 3 microcontrollers that meet your team project-specific requirements and find information on each</strong>
   </td>
   <td colspan="3" ><strong>4. Look up part details in the PIC datasheet</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Microcontroller Considerations</strong>
   </td>
   <td><strong>Instructions</strong>
   </td>
   <td><strong>PIC Option 1</strong>
   </td>
   <td><strong>PIC Option 2</strong>
   </td>
   <td><strong>PIC Option 3</strong>
   </td>
  </tr>
  <tr>
   <td>Part Number[^2]
   </td>
   <td><em>Include the entire part number (leave off any letters at the end that specify the package type)</em>
   </td>
   <td><strong>PIC24EP128GP202</strong>
   </td>
   <td>
<h1><strong>PIC24FJ512GU408</strong></h1>


   </td>
   <td>PIC16F18875-I/P
   </td>
  </tr>
  <tr>
   <td>Link (URL) to product page
   </td>
   <td><em>Do not paste links directly into the table. Instead, <a href="http://www.microchip.com/">link them like this</a>.</em>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/product/PIC24EP128GP202">link</a></strong>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/product/PIC24FJ512GU408">link</a></strong>
   </td>
   <td><strong><a href="https://www.digikey.com/en/products/detail/microchip-technology/PIC16F18875-I%2FP/5803537?utm_adgroup=General&utm_source=google&utm_medium=cpc&utm_campaign=PMax:%20Smart%20Shopping_Product_Zombie%20SKUS&utm_term=&utm_content=General&gclid=CjwKCAiAioifBhAXEiwApzCztiKsA2F-UhRKOECcYtAi6_Q1teACIXqo-rfiIIq--AozDiXbag5IjhoCYwAQAvD_BwE">link</a></strong>
   </td>
  </tr>
  <tr>
   <td>Links (URL) to Data Sheets
   </td>
   <td>
   </td>
   <td><strong><a href="https://ww1.microchip.com/downloads/aemDocuments/documents/MCU16/ProductDocuments/DataSheets/dsPIC33EPXXXGP50X-dsPIC33EPXXXMC20X-50X-and-PIC24EPXXXGP-MC20X-Family-Data-Sheet-DS70000657J.pdf">datasheet</a></strong>
   </td>
   <td><strong><a href="https://ww1.microchip.com/downloads/aemDocuments/documents/MCU16/ProductDocuments/DataSheets/PIC24FJ512GU410-Family-Data-Sheet-DS30010203D.pdf">datasheet</a></strong>
   </td>
   <td><strong><a href="https://ww1.microchip.com/downloads/aemDocuments/documents/MCU08/ProductDocuments/DataSheets/PIC16%28L%29F18855-75-Data-Sheet-40001802H.pdf">datasheet</a></strong>
   </td>
  </tr>
  <tr>
   <td>Links (URL) to Application Notes
   </td>
   <td><em>Often provided by manufacturers to give you specific examples of how to use their products. Search for them in the search bar on the Microchip’s website.</em>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/search?searchQuery=PIC24EP128GP202%20applications&category=Application%20Notes&fq=start%3D0%26rows%3D10">here</a></strong>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/application-notes/an1044">here</a></strong>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/product/PIC16F18875#document-table">here</a></strong>
   </td>
  </tr>
  <tr>
   <td>Links (URL) to Code Examples
   </td>
   <td>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/search?searchQuery=PIC24EP128GP202%20applications&category=Product%20Documents|User%20Guides&fq=start%3D0%26rows%3D10">here</a> </strong>
   </td>
   <td><strong><a href="https://ww1.microchip.com/downloads/aemDocuments/documents/MCU16/ProductDocuments/DataSheets/PIC24FJ512GU410-Family-Data-Sheet-DS30010203D.pdf">Code on page 84</a></strong>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/product/PIC16F18875#document-table">here</a> \
 \
<a href="https://ww1.microchip.com/downloads/en/Appnotes/TB3261-Technical-Brief-DS90003261A.pdf">getting started</a></strong>
   </td>
  </tr>
  <tr>
   <td>Links (URL) to External Resources
   </td>
   <td><em>Search on Google and YouTube for other resources for each specific microcontroller.</em>
   </td>
   <td><strong>none</strong>
   </td>
   <td><strong>none</strong>
   </td>
   <td><strong><a href="https://www.google.com/search?q=PIC16F18875+applications&oq=PIC16F18875+applications+&aqs=chrome..69i57j33i160l4.9158j0j4&sourceid=chrome&ie=UTF-8#ip=1">There is a lot</a></strong>
   </td>
  </tr>
  <tr>
   <td>Production Unit Cost
   </td>
   <td><em>Find in the Microchip online store, or Digikey</em>
   </td>
   <td><strong>$3.48(SM) and $4.28 (TH)</strong>
   </td>
   <td><strong>$4.05</strong>
   </td>
   <td><strong>$2.48</strong>
   </td>
  </tr>
  <tr>
   <td>Supply Voltage Range
   </td>
   <td><em>Find in the microcontroller datasheet</em>
   </td>
   <td><strong>3.0-3.6V</strong>
   </td>
   <td><strong>2.0-3.6 V</strong>
   </td>
   <td><strong>2.3-5.5 V</strong>
   </td>
  </tr>
  <tr>
   <td>Absolute Maximum Current for entire IC
   </td>
   <td><em>Find in the microcontroller datasheet</em>
   </td>
   <td><strong>300mA</strong>
   </td>
   <td><strong>10 µF to 47 µF</strong>
   </td>
   <td><strong>350 mA </strong>
   </td>
  </tr>
  <tr>
   <td>Maximum GPIO Pin Current (Source/Sink)
   </td>
   <td><em>Find in the microcontroller datasheet</em>
   </td>
   <td><strong>22mA</strong>
   </td>
   <td><strong>25 mA</strong>
   </td>
   <td><strong>50 mA </strong>
   </td>
  </tr>
  <tr>
   <td>8-bit or 16-bit Architecture
   </td>
   <td><em>Find in the microcontroller datasheet</em>
   </td>
   <td><strong>16 bit</strong>
   </td>
   <td><strong>16 bit</strong>
   </td>
   <td><strong>8 bit</strong>
   </td>
  </tr>
  <tr>
   <td>Available IC Packages / Footprints
   </td>
   <td><em>Find in the microcontroller datasheet. Choose a microcontroller with both surface mount and DIP/through-hole packages available. See Most Common Mistakes below for requirements to improve manufacturing reliability.</em>
   </td>
   <td><strong>SPDIP, SOIC, SSOP(4) , QFN-S</strong>
   </td>
   <td><strong>TQPF</strong>
   </td>
   <td><strong>PDIP, UQFN, QFP, QFN</strong>
   </td>
  </tr>
  <tr>
   <td>Supports External Interrupts?
   </td>
   <td><em>Find in the microcontroller datasheet</em>
   </td>
   <td><strong>Yes</strong>
   </td>
   <td><strong> Yes (5)</strong>
   </td>
   <td><strong>Yes</strong>
   </td>
  </tr>
  <tr>
   <td>In-System Programming Capability and Type
   </td>
   <td><em>Allows for programming the microcontroller without removing it from the PCB. Find in the microcontroller datasheet.</em>
   </td>
   <td><strong>Yes</strong>
   </td>
   <td><strong>Yes</strong>
   </td>
   <td><strong>Yes</strong>
   </td>
  </tr>
  <tr>
   <td>Programming Hardware, Cost, and URL
   </td>
   <td><em>Find on the microcontroller product page</em>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/development-tool/DM330013-2">Link</a></strong>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/product/PIC24FJ512GU408#document-table">Link</a></strong>
   </td>
   <td><strong><a href="https://www.microchip.com/en-us/product/PIC16F18875">Not needed</a></strong>
   </td>
  </tr>
  <tr>
   <td>Works with <a href="https://www.microchip.com/mplab/mplab-x-ide">MPLAB® X Integrated Development Environment</a> (IDE)?
   </td>
   <td><em>Required. See <a href="https://www.microchip.com/development-tools">Microchip Development Tools</a></em>
   </td>
   <td><strong>Yes</strong>
   </td>
   <td><strong>Yes</strong>
   </td>
   <td><strong>Yes</strong>
   </td>
  </tr>
  <tr>
   <td>Works with <a href="https://www.microchip.com/mplab/mplab-code-configurator">Microchip Code Configurator</a>?
   </td>
   <td><em>Required. Go to the <a href="https://www.microchip.com/en-us/tools-resources/configure/mplab-code-configurator">MCC website</a>, click the “Manual Downloads” tab, scroll to the device library that goes with the PIC you chose (likely “MCC 8-bit PIC”) and read the release notes to make sure your microcontroller is in the list of supported devices.</em>
   </td>
   <td><strong>Yes</strong>
   </td>
   <td><strong>Yes</strong>
   </td>
   <td><strong>Yes</strong>
   </td>
  </tr>
</table>





<table>
  <tr>
   <td colspan="5" ><strong>5. Write overall pros, cons, and rankings for the chosen microcontrollers</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Overall Pros</strong>
   </td>
   <td><em>Write at least 2 for each microcontroller</em>
   </td>
   <td><strong>1.Meets all project requirements</strong>
<p>
<strong>2.Seems simple and uncomplicated</strong>
   </td>
   <td>
<ol>

<li><strong>Has plenty of I2C and UART pins</strong>

<li><strong>Has a USB input </strong>

<li><strong>Meets all the project require-ments </strong>
</li>
</ol>
   </td>
   <td><strong>1.Meets all of the project requirements</strong>
<p>
<strong>2.Lots of information on how to program and use.</strong>
<p>
<strong>3.Surface Mount available  </strong>
   </td>
  </tr>
  <tr>
   <td><strong>Overall Cons</strong>
   </td>
   <td><em>Write at least 2 for each microcontroller</em>
   </td>
   <td><strong>1. No tutorials or helpful documentation</strong>
<p>
<strong>2.Unsure how to program</strong>
   </td>
   <td><strong>1. Too many pins will make soldering more difficult</strong>
<p>
<strong>2. Only the Packages method of TQPF</strong>
   </td>
   <td><strong>1.Surface mount is really small and would be difficult to manually solder</strong>
<p>
<strong>2.No information on programing hardware</strong>
   </td>
  </tr>
  <tr>
   <td><strong>Ranking</strong>
   </td>
   <td><em>1 = first, 2 = second, 3 = third</em>
   </td>
   <td><strong>2</strong>
   </td>
   <td><strong>3</strong>
   </td>
   <td><strong>1</strong>
   </td>
  </tr>
</table>


**Final Microcontroller Choice**: PIC16F18875-I/P

**Rationale**: Team 208 decided to move forward with PIC16F18875-I/P because of the three microcontrollers it had the most user and application notes. It also meets all of the project's requirements at the lowest overhead and doesn’t require separate hardware to work. This part also comes in a through hole and surface mount option for project implementation.


# 


# Software Proposal: 



<p id="gdcalert13" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image13.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert14">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image13.png "image_tooltip")


**Description:  **For this project we decided to break up our software proposal into multiple different sections as we believed it would be easier for readers of this report to understand. Each section shows how that part will operate and what it does as well. We have the main loop showing how the overall process will happen along with the chain showing how the wifi will communicate with UART and the ESP32 device.  The LED loop shows how many LEDs will turn on depending on how much force is applied to an object by a user when they are wearing the glove. Depending on how much force is applied either the green or the red LED will then turn on. The team used only one interrupt to run the update motor function every second.


# 


# Hardware Proposal: 

Team Schematic



<p id="gdcalert14" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image14.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert15">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image14.png "image_tooltip")


**Description:** The team schematic has been broken into sections to reduce confusion. There are six major sections in the team system. These are the switching voltage regulator, temperature sensor, LED array, motor driver, force sensors, and the microcontroller. Each section has arrows on the end of wires that connect to other sections. These arrows indicate the exact pin that wire should connect to.


# 


# Appendix A: Team 208’s Charter


# Team 208’s Charter

_Goals: _



* 
Create a project that is able to capture our audience’s attention during the Innovation Showcase.


* 
Developing a great addition to our engineering portfolios.


* 
Getting experience using industry level tools to create our project.


* 
Create a project that solves/remedies a real world problem.


* 
Create a project that can sense and respond to two or more environmental conditions. 


* 
Increase our knowledge of microcontrollers and interconnecting subsystems.


* 
Increase your proficiency in the use of the software and gain a clear understanding of how each module in MPLAB works and how it works.


* 
Improve team organization and coordination skills and clarify integrated common goals.
**Charter**

Based on the goals listed above and through a team discussion, we constructed the following charter:

_To be successful in our understanding of microcontroller programming while addressing how environmental sensing influences can affect real world applications in our final project._

**Product Mission Statement**

Based on the project description and project requirements, Team 208 has come up with the following mission statement:

_Our team will create an embedded systems device that senses at least two environmental conditions. This device will have at least one controlled response that reacts based on the sensory data. All sensing and actuation will be accomplished using serial communication. Our device will be used to solve a real world problem and will be demonstrated at the Polytechnic innovation showcase to industry professionals. The team will stay within budget and within the requirements of the 314 course. Some, but not all, of these requirements are surface mount components only, using cadence only, and board communication over wifi._

**Communication Channels**

**_Table 1: Team Member Communication Modes_**


<table>
  <tr>
   <td><strong>Name</strong>
   </td>
   <td><strong>First Choice Communication</strong>
   </td>
   <td><strong>Second Choice Communication</strong>
   </td>
   <td><strong>Third Choice Communication</strong>
   </td>
  </tr>
  <tr>
   <td>Kyle Selasky
   </td>
   <td><em>Text Message/Discord</em>
   </td>
   <td><em>Verbal</em>
   </td>
   <td><em>Zoom</em>
   </td>
  </tr>
  <tr>
   <td>Felicia Szleszinski
   </td>
   <td><em>Text Message/Discord</em>
   </td>
   <td><em>Verbal</em>
   </td>
   <td><em>Zoom</em>
   </td>
  </tr>
  <tr>
   <td>Miles Wilson
   </td>
   <td><em>Text Message/Discord</em>
   </td>
   <td><em>Verbal</em>
   </td>
   <td><em>Zoom</em>
   </td>
  </tr>
  <tr>
   <td>Mingqi Yu
   </td>
   <td><em>Verbal</em>
   </td>
   <td><em>Text Message/Discord</em>
   </td>
   <td><em>Zoom</em>
   </td>
  </tr>
</table>


**Communication Procedures**

_Team Communication:_

All team members will conduct communication to one another through text or Discord, in class collaboration and possibly through Zoom as seen in **Table 1**. Other alternative modes of communication include phone calls and emails. These will be used when necessary and will not be primary methods of communication. 

_Instructor Correspondence:_

Felicia Szleszinski will be responsible for instructor correspondence and will communicate all information to the team via text.

**Meeting Schedule**

**_Table 2: Team Member Availability Schedule_**



<p id="gdcalert15" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image15.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert16">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image15.png "image_tooltip")


_Team Prefered Meeting Times:_

For our team, meeting on Friday, Saturday, and Sunday between 5:00 pm and 9:00 pm will be most effective based on the data collected in **Table 2.**

**Meeting Coordination**

_Team Preferred Meeting Reminder Format:_

To help maintain scheduled team meetings our team will utilize a shared calendar.

_Team Preferred Meeting Alterations:_

If a team member needs to alter the time of a scheduled meeting or add an additional meeting time, they will reach out to the other team members via text or verbally. Once all team members have confirmed the change it will be reflected in the shared calendar.

_Team Preferred Meeting Format:_

Meeting face to face will be the most effective way for our team to communicate, followed by the voice channel in discord as our primary second choice. If those options are not available, meeting virtually is also applicable. 

_Team Other Necessary Procedures:_

Phone call communication is our alternative means of contact to notify of emergencies or last minute additional meetings. This resource will only be utilized if the primary communication sources were unsuccessful.

**Team Coordination**

_Team Preferred Assignment Sign Off and Submission:_

The team member submitting the assignment will always check with all the other team members that the assignment is ready to submit before submitting. This will happen via one of our primary communication methods. If a team member does not respond to this, secondary methods of communication will be used. If there is no response from either of these, the team member submitting will be allowed to submit without the unresponsive team member’s approval.

_Individual Team Member Comprehension and Adjustment:_

Team members should always inform the team if they don’t have the knowledge or skills to perform the work assigned. The team will come together and help each other to complete this work. Hopefully this will help the team learn together rather than struggle separately.

_Team Feedback Coordination:_

Feedback from assignments will be discussed by the team together. This will help us understand both the good and the bad parts of the assignment. The editing of documents according to feedback can be done individually if the team decides to divide and conquer. But the most important part is that we talk through it briefly to know what to do on future assignments.

**Team Accountability**

 

_Accountability Expectations:_

All team members should be contributing equally. Of course, with different expertises in different areas, varying amounts of work will be performed per each team member. This is not a problem as long as everyone is committed to working together and diligently.

_Recognizing Underperforming Team members:_

If a team member feels that themselves or another team member is underperforming it should be brought to the attention of the entire team. Signs of this include not attending meetings, classes, not helping each other, or not doing the work assigned.

_Supporting Team Members: _

Each team member is responsible for making sure their own and each other’s workloads are balanced. Helping each other and working together are the best ways to succeed in the course. Because of this, team members should not be afraid to ask for help when needed.

_Accountability Consequences:_

A discussion about why and how the underperformance is happening will happen. Hopefully a solution is found and the team member gets the help he/she needs. If it is not resolved, the professor will be contacted and informed on the situation.

**Conflict and Resolution**

Controversy or difference in opinions is expected in any group setting, however we all have the shared goal of learning and should always be respectful to one another. For our group, I don’t believe this will be an issue, however if any issues arise then we will host a group meeting with all team members to come up with a compromise or resolution for the conflict. 

**_Signatures_**

Team 208

Kyle Selasky 

Felicia Szleszinski

Miles Wilson

Mingqi Yu


# Appendix B: User Needs and Benchmarking


# **Team 208 User Needs and Benchmarking**

**Our Process:**

To complete user needs analysis, the team met online via Discord. This made sharing screens and files easy. Then we decided that Jamboard would be used to display and consolidate our ideas. Then each team member started to add user needs ideas to the board. No idea was rejected at first, all team members suggested and wrote whatever need they could think of. No team member rejected ideas at this point, this was merely to get a large pool of user needs on the table. Then we organized all the user needs into groups. This helped to reduce the number of repeat user needs in each category. Next, we ranked each section by how much the team valued them. Finally, we ranked every need in each category as well. This gave us a very good idea of what we value and absolutely need in the design. 

**User Needs **



1. 
The main components need to be made of high quality materials.


2. 
The design needs to be comfortable for the user to wear for long periods of time.


3. 
Directional movement needs to be precise to prevent personal injury.


4. 
The total design needs to be within the budget of $240.


5. 
The user instructions for use must be easy to comprehend.


6. The design must be able to be used by people with limited mobility.



7. 
The design must be designed to prevent recurring repairs or replacement.


8. 
The finger coils need to be able to be removed with one hand for those with limited mobility.


9. 
The design needs to have a low energy level to mitigate risk of injury.


10. 
Materials used must be stiff to help control muscle spasms and improve exercise capacity.


11. 
The finger straps must be able to adapt to various finger sizes.


12. 
The design must be less than 2-3 pounds for users with limited strength.


13. 
The design must be small and portable.


14. 
The design's main components must be self-contained.


15. 
The design must have connections from the fingers to the wrist for controlled movement and pressure.


16. 
The connection points need to avoid having any exposed wires or possible sharp edges.


17. 
The user must be able to grab objects while wearing the gloves. 


18. 
The design must take into consideration various user’s levels levels of pressure or strength.


19. 
The design must take into consideration various user’s levels of flexion and extension movements. 


20. 
The design needs to allow for stretching and flexing movements to prevent stiffness.


21. 
The design must allow for individual finger movements. 


22. 
The design must offer a stabilizer to offset tremors and shaking. 


23. 
The design must be rechargeable.


24. 
The design must be able to be maintained at a low cost.


25. 
The design needs to control stiffness through pressure control. 


26. 
The design must be accessible to all age groups and levels of education.


27. 
The design must be able to withstand 2-4 hours of daily use. 


28. 
The design needs to offer a passive movement to help improve muscle strength and aid recovery.


29. 
The design needs to avoid sharp edges to prevent injury to the user. 


30. 
The pressure sensor must be designed to prevent force that could cause injury to the user and others.


31. 
Instructions must be precise and able to be understood by an elementary reading level.


32. 
Any materials touching the user must be made of medical grade materials. 


33. 
Materials touching the user must not cause increased humidity while wearing to prevent chafing or damage to the user’s skin.  


34. 
The pressure sensor must be able to react and retract finger coils in under 3 seconds. 


35. 
The design must use at least one motor controlled by a motor controller communicating over the I2C or SPI-based protocol.


36. 
The design must incorporate at least two external environmental serial sensors.


37. 
The design must incorporate easy to understand visual indicators.


38. 
Indicators must be noticeable at all times, and in all weather conditions


39. 
The glove should include a sensor that shows the user how much pressure they are exerting.


40. 
The device should help the user sense fluctuations in temperature to prevent injury.


41. 
The device should help stabilize vibrations in the glove to help regulate pressure.


42. 
The product can display on-screen feedback from users after use.


43. 
Should come with everything needed to operate the device.


44. 
Designers need to understand the center of gravity of the product in the prototype to prevent user fatigue and other discomforts in the process of use.


45. 
Product design should take into account the size of the user's hand, or have stretchable materials to facilitate wearing.


46. 
The operating temperature of the components should be clearly understood before designing the product.


47. 
The design should not be complex to use.


48. 
The design should offer stabilization to help maintain hand control.


49. 
The internal components should be able to withstand heat to prevent injury.


50. 
Products should have a certain impact resistance to prevent damage caused by excessive collisions.


51. 
Designers need to understand the center of gravity of the product in the prototype to prevent user fatigue and other discomforts in the process of use.


52. 
Should be designed to be manufactured for either the right or left hand.


53. 
Any balloon or enclosed air should be resistant to leaks and sharp objects.


54. 
The product can display the remaining power on the screen.


55. 
 The battery capacity should be sufficient to support the user's daily use for a long time.


56. 
Design product features that can be easily accepted by the user's target.


57. 
The working principle does not need to be too complicated to facilitate the production and subsequent repair of the product.


58. 
The service life of the product should be within the user's ability to accept.


59. 
 After the product stops working, the finger movement joints controlled by each part should be returned to the normal position to prevent injury.


60. 
In the event of a product failure, the entire circuit system needs to have an emergency treatment plan.
**Benchmarking **

**Our Process:**

The team met on Discord again to do the benchmarking. First we agreed that we would look up ideas relating to Parkinson’s or nerve damage therapy relating to the hand. This produced a few different products that the team thought were interesting and helpful. We analyzed the positive and negative comments on each product to get more user needs directly from users.


## 
    Search #1

**Keywords: **Parkinson, grip, sensor

**Search Results Link:** [Here](https://www.google.com/search?q=Parkinson,+grip,+sensor&source=lmns&bih=876&biw=1031&hl=en&sa=X&ved=2ahUKEwjuwurbi9D8AhUQN0QIHRFhDC8Q_AUoAHoECAEQAA)


## 
    Selected Products


# **1.** [Steadi-Two: Tremor Reducing Glove](https://steadiwear.com/products/steadi-two?variant=39602647597118&currency=USD&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&srsltid=AeTuncrpidJZvByOF4i6p4qZoAI4PKyvljDF8Ib5S0TTi_WE0Cz6n2SayBg)



<p id="gdcalert16" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image16.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert17">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image16.png "image_tooltip")




* 
**Price**: $649.00


* 
**Vendor**: Steadi-Wear


* 
**Description**: The Steadi-Two is a ground-breaking glove designed to significantly reduce your hand tremor in Essential tremor.
Steadi-Two key features:



    * Provides INSTANT stability to your tremor.
    * NO batteries or charging required.
    * Lightweight: The device weighs under 1lb.


#### **Positive Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“The Steadi-Two has really helped her. Anything that helps to reduce her tremor makes her feel better about herself, and that makes me feel better.”
   </td>
   <td>
<ol>

<li>
The device inspires confidence (Explicit)

<li>Sense of independence ( Latent)

<li>Peace of mind for family (Explicit)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“I have just spent a month with the new Steadi-Two glove and I am delighted. It is light, very effective, easy to put on and take off and I could wear it for hours with no problem.” 
   </td>
   <td>
<ol>

<li>
The device is very simple to use (Explicit)

<li>Comfortable to wear ( Explicit)

<li>No adverse impact on day to functions (Latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“When I put [the glove] on, I had a lot of good relief as far as being able to drink without spilling all over myself, and eat”
   </td>
   <td>
<ol>

<li>
The device makes it easy to do simple life tasks. ( Explicit)

<li>Prevents messes from happening (Explicit)

<li>Less stress ( Latent)
</li>
</ol>
   </td>
  </tr>
</table>



#### **Negative Comments ([Original Version ](https://www.canadianmanufacturing.com/manufacturing/steadiwear-inc-develops-a-new-glove-to-combat-parkinsons-and-hand-tremors-273834/))**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“The original version was limited to certain tremor types”
   </td>
   <td>
<ol>

<li>
Offers no support for certain conditions (Explicit)

<li>More of a hindrance to non-covered users (Latent)

<li>Not listed conditions covered (Latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“Original version was to large”
   </td>
   <td>
<ol>

<li>
Could not fit everybody (Explicit)

<li>Limited to certain customers (Explicit)

<li>Complicated to use (Latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“Original version was to heavy”
   </td>
   <td>
<ol>

<li>
Harder to use (Explicit)

<li>Not user-friendly (Explicit)

<li>Not compatible with all users ( Explicit)
</li>
</ol>
   </td>
  </tr>
</table>



## 
    Search #2

**Keywords: **Parkinson, grip, gyroscope

**Search Results Link:** [Here](https://www.google.com/search?q=Parkinson%2C+grip%2C+gyroscope&oq=Parkinson%2C+grip%2C+gyroscope&aqs=chrome..69i57j33i160l3.874j0j4&sourceid=chrome&ie=UTF-8)


## 
    Selected Products

**2. **[GYENNO Parkinson Spoon and Fork](https://www.amazon.com/GYENNO-Twist-Parkinson-Stabilizing-Parkinsons/dp/B07FRPX2H8?source=ps-sl-shoppingads-lpcontext&ref_=fplfs&psc=1&smid=AJE1XFPPGWEBV)



<p id="gdcalert17" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image17.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert18">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image17.png "image_tooltip")




* 
**Price**: $259.00


* 
**Vendor**: Amazon


* 
**Description**: GYENNO Spoon for hand tremor：Steady helps people with eat more easily. Steady is designed to counteract tremors and shaky hands that may be related to conditions like Parkinson's disease or essential tremor.

#### **Positive Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“Love the spoon part. In the mornings my shakes can be real bad,and the spoon with the little lip holds my cheerios in the spoon 99% of the time. The handle takes get use to hold, still working on that. Over all I like it. I would rate it 4.5 out of 5.”
   </td>
   <td>
<ol>

<li>
Lip holds food in (Explicit) 

<li>Enjoyable to use ( Explicit)

<li>Modular (Explicit)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“My 80 year old husband has tremors to both hands. Intensity varies from mild to severe depending upon the day. With this adaptive eating utensil, he can get foods to his mouth without spilling. He found the device easy to operate. The fork was a big plus.’
   </td>
   <td>
<ol>

<li>
Can be used with varying severity of tremors (Explicit)

<li>No messes (Explicit)

<li>Ease of use ( Explicit)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“Had an issue with a magnet in the fork, contacted the company. They were very responsive. We got new utensils within 3 weeks. Very happy and works well for my husband.”
   </td>
   <td>
<ol>

<li>
Company was responsive to customer inquiries ( Explicit)

<li>Counteracts tremors (Latent)

<li>Magnet works well  (Explicit)
</li>
</ol>
   </td>
  </tr>
</table>



#### **Negative Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“Do not purchase this useless thing. Far, far too complicated and unusable for anyone, much less elderly.”
   </td>
   <td>
<ol>

<li>
Not worth the price ( Explicit)

<li>Complicated ( Explicit)

<li>Not user-friendly (Explicit)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“The spoon and fork are made of very fragile plastic material. How long will it last? It is very difficult to get used to this condition. Money thrown away.”
   </td>
   <td>
<ol>

<li>
Easily breakable (Explicit)

<li>Not user friendly ( Explicit)

<li> Not worth amount paid for( Explicit)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“I really need these eating utensils for my tremors, but your many misspellings in your description scares me about how reliable you are as a seller.” 
   </td>
   <td>
<ol>

<li>
Suspicion of seller (Explicit)

<li>Concerns about reliability of product (Latent)

<li>Lack of transparency ( Latent)
</li>
</ol>
   </td>
  </tr>
</table>



## 
    Search #3

**Keywords: gloves to help post stroke**

**Search Results Link:** [Here](https://www.google.com/search?q=gloves+to+help+post+stroke&sxsrf=AJOqlzUZ5ONRWC1dj8Pa6UXEpDkxHr5fmw%3A1674011868947&ei=3GTHY9u9OdbHkPIP5uWs-AY&ved=0ahUKEwjbm7GWlND8AhXWI0QIHeYyC28Q4dUDCA8&uact=5&oq=gloves+to+help+post+stroke&gs_lcp=Cgxnd3Mtd2l6LXNlcnAQAzIFCCEQoAE6BAgjECc6BAgAEEM6BQgAEJECOhAILhCxAxCDARDHARDRAxBDOgsIABCABBCxAxCDAToKCC4QxwEQrwEQJzoICC4QgAQQsQM6CwguEIAEEMcBEK8BOhEILhCABBCxAxDHARDRAxDUAjoKCC4QxwEQ0QMQQzoHCAAQsQMQQzoKCC4QxwEQrwEQQzoLCC4QgAQQsQMQgwE6DQgAEIAEEIcCELEDEBQ6CAgAEIAEELEDOgUIABCABDoKCAAQgAQQhwIQFDoGCAAQFhAeOgUIABCGAzoFCCEQqwI6CAghEBYQHhAdSgQIQRgASgQIRhgAUABYuChg5SloAHAAeACAAWqIAZkQkgEEMjQuMpgBAKABAcABAQ&sclient=gws-wiz-serp)


## 
    Selected Products

**3.**[XUETAO Rehabilitation Robot Gloves](https://www.amazon.com/Rehabilitation-Dysfunction-Hemiplegia-Exerciser-Strengthener/dp/B09PTJD96H/ref=asc_df_B09PTJD96H/?tag=hyprod-20&linkCode=df0&hvadid=563607579726&hvpos=&hvnetw=g&hvrand=1474911321915781718&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9029968&hvtargid=pla-1639344496302&th=1)



<p id="gdcalert18" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image18.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert19">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image18.png "image_tooltip")




* 
**Price**: $189.00


* 
**Vendor**: Amazon


* 
**Description**: It has a half cut design features, a wrist extension exerciser can be worn comfortably on wrists and finger, Suitable for finger work habits. Inhibit the fingers of the finger stroke or rheumatism rheumatoid arthritis deformation, prevent the fingers bend spasm or atrophy.

#### **Positive Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“So my Mom has had weakness in her left side for a while. She didn't think this glove was really going to do anything she hadn't already been doing. We started out on the auto exercise for 5 minutes a day on her left hand. It's hard for her to get her left hand to do anything, it doesn't mind and kind of gets grabby on its own.
<p>
After a few days of using this device, Mom found herself reaching for an object with her left hand, just using the power of her mind - you know, like your body should! Every movement she has to do needs to be so mindful, so her brain thinking "I want that object" and sending her left hand, which was closest, to get it is an absolute breakthrough!
<p>
The glove works through air pressure to make your hand open and close. It doesn't feel weird when it does it, and she really likes that it makes her fingers extend, since that's also an exercise she doesn't do often anymore. You can adjust the intensity, the pressure, and even use the other glove on your right hand to send messages to the left on what you would like it to do.
<p>
Obviously, your mileage may vary. Everyone works at their own pace and can only do what they can, but I see how this device can help people relearn to use their hand. She'll never be 100%, but every little bit counts.”
   </td>
   <td>
<ol>

<li>
The device uses a comfortable amount of pressure to provoke exercise. (explicit)

<li>The glove forces the user to extend and retract fingers to promote movement in limbs. (explicit)

<li>The device teaches the user how to “reuse” their hands to grab objects through movement exercises and pressure regulation. (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“What I love about this robot glove is how straight forward it is to use. The different modes and intensity level can easily be changed via the control monitor (orange box). Air pressure can be turned off to a particular finger by the white valves on the glove which makes it easy to isolate a particular finger or fingers for training. What I really love the most is the mirror training glove, genius. The mirror glove is worn on the non-training hand. When I clench the mirror glove and press a button it mimics this movement on the robot glove. This is great for trying to retrain your hand and stimulate movement. The glove works by air compression and is a bit on the loud side when the orange box is pumping air. The control box is cordless so can be taken anywhere without having to rely on an outlet. I appreciate the fact that they actually included a AC USB charger and cable.”
   </td>
   <td>
<ol>

<li>
The device allows for various levels of intensity. (explicit)

<li>The device is portable and can be used anywhere. (explicit)

<li>The glove allows for isolation to focus on finger training. (explicit)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“All other sellers were showing delivery 2+ months later and at higher price. I took a chance here with only 2 review. I am very pleasantly surprised with quick delivery. The product works amazingly well for my brother who suffered a stroke and can’t move left arm/fingers. Even the doctors, nurses and the physical therapists at the hospital are amazed when they see my brother using it while admitted. It’s really helping with his rehabilitation.I am in tech, and am super impressed that someone developed this.”
   </td>
   <td>
<ol>

<li>
The device helps provide relief. (latent)

<li>Provides help with rehabilitation. (explicit)

<li>The device is portable and can be used in hospital settings. (latent)
</li>
</ol>
   </td>
  </tr>
</table>



#### **Negative Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“Video instructions did not show the proper size or placement to put the glove on. After my stroke it leaves your hand unable to put it on, both constricted or paralysis, with your other hand alone. Tried out both.”
   </td>
   <td>
<ol>

<li>
The directions should be thorough. (explicit)

<li>The device should be accessible for those with handicaps. (latent)

<li>The device should be easy to put on with one hand. (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“It’s a nice product, I guess because I never got to use it. They didn’t describe the sizing correctly and therefore, they size I bought was WAY too big for my son.”
   </td>
   <td>
<ol>

<li>
The design should allow for various sizes. (latent)

<li>The design must instate the size of hand it is designed for. (explicit)

<li>The design should fit the hands of a child or an adult. (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“Incredible product. If you think about the fact that you're paying to give someone their hand back, it is absolutely worth it.
<p>
However when you see it, all this is is the pump from a blood pressure cuff hooked to a glove with some tubing. There is absolutely no reason why this costs $200. This product could change the lives of millions if it were priced more reasonably.”
   </td>
   <td>
<ol>

<li>
Too expensive (explicit)

<li>The design is not well made. (latent)

<li>The design should offer more options to the user for the price. (latent)
</li>
</ol>
   </td>
  </tr>
</table>



## 
    Search #4

**Keywords: **healthcare hand Robot

**Search Results Link:** [Here](https://www.amazon.com/Baldoni-Neuromodulation-Tremor-Device-Carrying/dp/B0BBGPGBCV/ref=sr_1_12?crid=5JJE3ZLN6O9S&keywords=parkinson+glove&qid=1674017606&sprefix=parkinson+glove%2Caps%2C171&sr=8-12)


## 
    Selected Products [Neuromodulation Tremor Device Set](https://www.amazon.com/Baldoni-Neuromodulation-Tremor-Device-Carrying/dp/B0BBGPGBCV/ref=sr_1_12?crid=5JJE3ZLN6O9S&keywords=parkinson+glove&qid=1674017606&sprefix=parkinson+glove%2Caps%2C171&sr=8-12) 

**4.**



<p id="gdcalert19" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image19.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert20">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image19.png "image_tooltip")




* 
**Price**: $239


* 
**Vendor**: Baldoni Neuromodulation 


* 
**Description**:


    * Effective only for left hand hand-initiated tremors
    * Works like a gyroscope to stabilize hand tremor motion
    * Helps with eating and writing and Quiet enough to watch TV
    * Weighs the same as a weighted glove at 0.65 lb


#### **Positive Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“A family member uses this as therapy for his hands after a stroke. He has used other machines, but has not had the results as he had after using this machine after such a short time. He has more feeling and control in his affected arm and fingers. I wish I had purchased this item sooner. It is easy for him to put on even without the full use of his affected hand. Another plus is that it is not battery operated so we do not spend extra money on purchasing batteries.”
   </td>
   <td>
<ol>

<li>
Rapid treatment effect of the machine.(latent)

<li>The device is easy to put on. (explicit)

<li>No need to use separate batteries. (explicit)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“I ordered this glove for my dad that had the worst kind of stroke that paralyzed his right side. We have been working with him to wake up his brain, muscles and nerves a little over a month now with no improvement in his hand. We received the glove on Tuesday and by Thursday dad was able to wiggle his fingers. I am a true believer that this glove works! So impressed with this product.”
   </td>
   <td>
<ol>

<li>
The guidance according to the measurement instructions still leads the user to purchase the wrong size. (explicit)

<li>Can work as introduced in the promotional image. (latent)

<li>The device can offer rehabilitation improvement. (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“So far my mom has been pleased using this product! She understands it's not meant to "cure the tremors but it definitely does calm them down.”
   </td>
   <td>
<ol>

<li>
The point is not to treat tremors, but it does help stabilize the hands of Parkinson's patients. (explicit)

<li>Offers stabilization properties. (latent)

<li>Comfortable to wear for periods of time. (latent) 
</li>
</ol>
   </td>
  </tr>
</table>



#### **Negative Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“This product would be awesome if the glove stayed on my hand...it addresses hand only and does not offer support for wrist...I have long fingers and a slim hand, ordered large size for my finger length...product worked its way off with every use starting with pinky then thumb...I have left side hemiparesis maybe it's more useful for hand injuries only...”
   </td>
   <td>
<ol>

<li>
Wrong size (explicit)

<li>For hands only, no wrist support (explicit)

<li>Only for finger injuries (explicit)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“Size not as advertised, takes a long time, it is too early to tell if it works.When you want the exercise to start, press the play button in the bottom right corner. It took me a while to figure that out since are a little confusing.”
   </td>
   <td>
<ol>

<li>
Wrong size (explicit)

<li>Hands-on difficulty is relatively high, User needs to slowly practice to adapt. (latent)

<li>You do not know if they can really be treated. (explicit)
</li>
</ol>
   </td>
  </tr>
</table>



##     Search #5

**Keywords: rehab glove**

**Search Results Link:** [Here](https://duckduckgo.com/?q=rehab+glove&atb=v314-1&ia=web)


## 
    Selected Products [Neofect Extender](https://www.amazon.com/NEOFECT-Extender-Positioning-minimize-Spasticity/dp/B07D36JK48/ref=psdc_706809011_t2_B0B2X3JX9Z?th=1)

**5.**



<p id="gdcalert20" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image20.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert21">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image20.png "image_tooltip")




* 
Price: $57.90


* 
Vendor: Amazon


* 
Description: Passive resistance rehabilitation gloves.

#### **Positive Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“Been looking off & on for something like this for fingers curling. A little tricky to thread all curled fingers in at first but saw results after only a few uses. I can now insert those now straighter fingers without using my good hand to guide them in. Sizing guide was spot on, snug at first that resulted in a perfect "break in" fit. I wish I could leave more than five stars.”
   </td>
   <td>
<ol>

<li>
The glove should fit comfortably (explicit)

<li>The glove should be adjustable (latent)

<li>Instructions should be clear (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“I got it for my brother, he had a motorcycle accident and was left with spasticity as sequel. He likes the way it fits and is also happy because it allows him to perform more tasks with his right hand.”
   </td>
   <td>
<ol>

<li>
The glove should increase hand functionality (explicit)

<li>The glove should fit all types of hands (latent)

<li>Should passively operate without supervision (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“Nerve damage in hand after spinal surgery left hand and clenched position helps straightening fingers all the doctors and therapist who saw this glove loved it”
   </td>
   <td>
<ol>

<li>
Healthcare workers should be able to easily use/store/maintain it (latent)

<li>Should provide relief of ailment (latent)

<li>Should be medical grade (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



#### **Negative Comments**


<table>
  <tr>
   <td>Voice of the Customer
   </td>
   <td>Restated Customer Need
   </td>
  </tr>
  <tr>
   <td>“Extremely big!! The description says s/m/l but when I received the item the package said one size fits all. And that was more of an accurate description of the item. Didn’t fit my child size hands lol if I knew it was one size fits all I would’ve never bought this item. I did send it back and got my refund”
   </td>
   <td>
<ol>

<li>
Glove should work for all ages (explicit)

<li>Use instructions and product specifications should be clear (latent)

<li>Should be adjustable (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“It's important to understand that without proper occupational therapy training and the assistance of a portable stim device, this glove is of little help. You must have structured, professional OT sessions to make this work. Otherwise, it's just a neoprene glove with a bunch of fancy straps on it.”
   </td>
   <td>
<ol>

<li>
Device should be easy to use (explicit)

<li>Device should come with everything needed to operate (latent)

<li>Shouldn’t need professional help to operate (latent)
</li>
</ol>
   </td>
  </tr>
  <tr>
   <td>“The glove came apart and straps came lose , it is very cheaply made not good at all! Would not purchase any thing like this anymore on line. It is not worth the money that they charged for it. It is a rip off! Don't buy!! (O) star rating!”
   </td>
   <td>
<ol>

<li>
The device should be made of durable materials (explicit)

<li>The device should be made of cheap materials (latent)

<li>The device should communicate clearly exactly what it does (latent)
</li>
</ol>
   </td>
  </tr>
</table>


**Organizing Need Statements**

Initial Notes:



<p id="gdcalert21" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image21.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert22">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image21.png "image_tooltip")


Grouped Notes:

Key:


<table>
  <tr>
   <td>Color
   </td>
   <td>Meaning
   </td>
  </tr>
  <tr>
   <td>Yellow
   </td>
   <td>100 User Needs
   </td>
  </tr>
  <tr>
   <td>Blue
   </td>
   <td>Category 
   </td>
  </tr>
</table>




<p id="gdcalert22" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image22.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert23">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image22.png "image_tooltip")


Ranked Notes:

Key:


<table>
  <tr>
   <td>3 Stars
   </td>
   <td>2 Stars
   </td>
   <td>1 Star
   </td>
  </tr>
  <tr>
   <td>Very Important 
   </td>
   <td>Important 
   </td>
   <td>Less Important 
   </td>
  </tr>
</table>




<p id="gdcalert23" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image23.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert24">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image23.png "image_tooltip")


**Product Requirements**

**Our Process:**

	The team decided that each major category of the product requirements will just be the major categories that our user needs are organized into. These groups are not the suggested groups, but we felt like these will better inform our design based on our user needs. This will make it easier to both rank and generate the product requirements. The product requirement list below is organized from the most important major category at the top and least at the bottom. Within each category the top most product requirement is the most important of that category.

**Stakeholders:**

Target Users: People with nerve damage or limited mobility in the hand.

Target Purchasers: This can be the target user directly or healthcare professionals for use in a facility.

Sponsor and Advisors: ASU acts as a financial sponsor. EGR314 and Professor Aukes act as advisors to the final product.

**Use Cases:**

Case #1: Mrs. Haro has nerve damage in her right hand. This has left her without the ability to gauge her grip strength or feel anything in her hand for that matter. She decides to try out a new therapeutic device. It's a glove that allows her to know her grip strength in her right hand. This not only gives her more confidence and functionality in her hand, but also a mind-body relationship with her grip strength as well. A temperature sensor is integrated into the product so she doesn’t burn her hand on her hot coffee cup.

Case #2: Mr. Jacobs got in a car accident recently and is recovering from his injuries. His left hand is weak and suffers from clawing. A healthcare professional decides that a new therapeutic machine is best for his physical therapy. The new machine allows his hand to strengthen and accurately grip objects again. The data from the machine is sent via wi-fi to the hospital server. Mr. Jacobs doctor, after seeing the data, decides Jacobs is ready for stronger resistance on the machine. The doctor plugs into the machine and alters the resistance via PuTTY motor control. Jacobs recovers in a few weeks and no longer needs the machine to gauge his grip strength.

**Aspects:**



1. 
**Safety (***):**
1.1) The product’s structural components must not pinch, cut, or injure the user. 

1.2) The product should be made out of regulatory compliant and sterile materials.

1.3) All electrical components should be sealed, hidden, or inaccessible to the user.

1.4) A temperature sensor should sense if the user is holding something hot.

1.5) The product should generally move slowly and not require high voltages, this will keep total energy low.



2. 
**Ease of Use (***):**
2.1) The product should be able to be used by any type of user regardless of age, hand size, strength, or mobility.

2.2) The product should adjust to fit any user.

2.3) Using the product should be easy to understand and use.

2.4) The multiple indicators on the product should not be loud or annoying, but still noticeable and understandable to the user.

2.5) The product should be easy to manufacture, assemble, disassemble, and clean.



3. 
**Functionality (**):**
3.1) The product will sense and relay the temperature of a gripped object and the grip strength force in real time.

3.2) The product will use a motor to resist user grip strength if it exceeds an acceptable limit in real time.

3.3) The product should be less than $240 and affordable for the average user.

3.4) The product should be therapeutic for the user and slowly increase hand functionality over time.



4. 
**Electronics (**):**
	4.1) All electronics should meet the requirements for EGR314.

	4.2) The product should have enough power for at least 2-4 hours of use.

	4.3) The power supply should be completely internal or supplied by a USB-c connection.

4.4) The product should respond to sensor data in an accurate, fast, and controlled manner.



5. 
**Durability (*):**
5.1) The product should be water, heat, and impact resistant.

5.2) The product should be made out of durable materials for a long product lifespan.

5.3) The product should utilize easily replaceable parts.

5.4) Any balloon or enclosed air pocket should be puncture resistant.



6. 
**Comfort (*):**
6.1) The product should be comfortable and should not chafe during extended use.

6.2) The product should be able to fit most size hands.



7. 
**Misc. (*):**
	7.1) Amount of remaining power should be visible to the user.

	7.2) The product life cycle should be considered when designing the product.

	7.3) A screen should communicate data and information to the user.

	7.4) The product should be stylish for the user.


# 
    Appendix C: Design Ideation

Team 208

Professor Aukes

EGR 314

19 January 2023


# **Team 208 Design Ideation**


## Legend: 



<p id="gdcalert24" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image24.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert25">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image24.png "image_tooltip")



## Generated Ideas: 

For Team 208’s Design Ideation, we chose to look at what characteristics made our benchmarked examples successful products and how they could be improved upon. Listed below are one hundred ideas that discuss various aspects of potential design movements, material considerations, electrical component ideas, and other other potential successful characteristics. 

Once we had come up with one hundred ideas, we separated them into color coordinated categories and grouped them based on their ability to meet our project requirements. 



<p id="gdcalert25" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image25.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert26">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image25.png "image_tooltip")



## Sorted Ideas (By Color):



<p id="gdcalert26" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image26.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert27">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image26.png "image_tooltip")



## Design Concepts:



<p id="gdcalert27" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image27.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert28">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image27.png "image_tooltip")


Once we had decided upon three variations of a pressure and temperature regulated glove, we separated our initial grouped ideas into more developed product concepts, and ranked them as seen below. 


## Three Chosen Ideas:  



<p id="gdcalert28" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image28.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert29">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image28.png "image_tooltip")


Ranked Ideas:



<p id="gdcalert29" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image29.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert30">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image29.png "image_tooltip")


Design Concepts:

**Balloon Grip Sensor Therapeutic Glove:**



<p id="gdcalert30" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image30.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert31">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image30.png "image_tooltip")


**Variable Force Sensing Temperature/Pressure Glove**



<p id="gdcalert31" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image31.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert32">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image31.png "image_tooltip")


**Velcro on Fingers for Various Sizes**




<p id="gdcalert32" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image32.jpg). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert33">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image32.jpg "image_tooltip")



# 


# Appendix D: Verification Table



<p id="gdcalert33" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image33.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert34">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image33.png "image_tooltip")



# Appendix E: Component Selection

Team 208

Professor Aukes

EGR 314

1 February  2023

**Component Selection**

**Power Supply Subsystem (Kyle):**

**Wall Outlet Power Supply**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert34" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image34.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert35">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image34.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
High current output
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Very unaffordable
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 1
   </td>
   <td>
<ul>

<li>
High operating temperature
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Heavy
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: DTL65-19SX-W6
   </td>
   <td>
   </td>
   <td>
<ul>

<li>
Large footprint
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $60
   </td>
   <td>
   </td>
   <td>
<ul>

<li>
Requires high input voltage
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/eta-usa/DTL65-19SX-W6/11656394">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert35" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image35.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert36">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image35.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Interchangeable main connectors
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Long lead time
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 2
   </td>
   <td>
<ul>

<li>
High current output
</li>
</ul>
   </td>
   <td>
<ul>

<li>
High output voltage required
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: VER18US240-JA
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $15.80
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/xp-power/VER18US240-JA/5864682">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert36" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image36.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert37">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image36.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Affordable
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Low output current
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 3
   </td>
   <td>
<ul>

<li>
High input/output voltage range
</li>
</ul>
   </td>
   <td>
<ul>

<li>
 Long lead time
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: AMF24US09
   </td>
   <td>
<ul>

<li>
 High max input current
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $24.42
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/xp-power/AMF24US09/16351205">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert37" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image37.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert38">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image37.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
High current output
</li>
</ul>
   </td>
   <td>
<ul>

<li>
On the more expensive side
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 4
   </td>
   <td>
<ul>

<li>
Plugs directly into wall
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: WSU050-4000
   </td>
   <td>
<ul>

<li>
Easy barrel jack input connection
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $15.71
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/triad-magnetics/WSU050-4000/3094945">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice:  **WSU050-4000

**Rationale: **Our team has decided to go with the WSU050-4000 as it is an affordable option for our group and can supply us with 5V which will be just right to run the motor. It can also supply us with a very powerful current (4A) to help us power our design and the motor. It can be shipped immediately.

**Switching Voltage Regulator**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert38" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image38.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert39">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image38.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Have familiarity with it via the thru hole version

<li>Is surface mounted

<li>Is a buck regulator

<li>Easy footprint to solder
</li>
</ul>
   </td>
   <td>
<ul>

<li>
 Low current output
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 1
   </td>
   <td>
<ul>

<li>
Very wide range of voltage input options
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: LM2575
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: Free
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.mouser.com/ProductDetail/Microchip-Technology/LM2575-12WU?qs=kh6iOki%2FeLGpYpwL5b%2Fivg%3D%3D&mgh=1&gclid=CjwKCAiAl9efBhAkEiwA4TorirKcXM7vX2qEkFyVFUpCz-cA6P7tWsDGGFtFOKgN5gfcdBhzptbdyhoC0loQAvD_BwE">Mouser Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert39" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image39.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert40">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image39.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Affordable
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Long lead time
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 2
   </td>
   <td>
<ul>

<li>
High voltage output
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Low max voltage output
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: NCP59763AMN120TBG
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $1.68
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/onsemi/NCP59763AMN120TBG/15851954">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert40" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image40.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert41">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image40.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Very affordable
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Low current output
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 3
   </td>
   <td>
<ul>

<li>
 Wide voltage input/output options
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: NCP160
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $0.07
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/rochester-electronics-llc/NCP160AFCT514T2G/15635815">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice:  **LM2575

**Rationale: ** The team agrees that the LM2575 is the best choice for a switching voltage regulator. It has a wide range of acceptable voltages form 4-40V and we are familiar with it due to previous assignments that have required usage of the thru-hole version in class. 

**Motor and Motor Driver Subsystem (Mingqi):**

**Motor**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert41" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image41.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert42">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image41.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Steps per Revolution 4096
</li>
</ul>
   </td>
   <td>
<ul>

<li>
May be too weak
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 1
   </td>
   <td>
<ul>

<li>
5VDC
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: 28BYJ-48
   </td>
   <td>
<ul>

<li>
Cheap
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $8.00
   </td>
   <td>
<ul>

<li>
Small
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/mikroelektronika/MIKROE-1530/5724295?s=N4IgTCBcDa4BwCECaApAtAFjiAugXyA">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>

<p id="gdcalert42" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image42.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert43">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image42.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
5VDC
</li>
</ul>
   </td>
   <td>
<ul>

<li>
May be too weak
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 2
   </td>
   <td>
<ul>

<li>
 small
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: 108990003
   </td>
   <td>
<ul>

<li>
cheap
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $4.50
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/seeed-technology-co.,-ltd/108990003/5487797?utm_adgroup=Stepper%20Motors&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Motors%2C%20Solenoids%2C%20Driver%20Boards%2FModules_NEW&utm_term=&utm_content=Stepper%20Motors&gclid=CjwKCAiAleOeBhBdEiwAfgmXf5is6x8f4EBvlwASAPr6dyyyJd6ylyHbPYO9TRPaTnvp2sk2SjOrzhoCmC4QAvD_BwE">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>

<p id="gdcalert43" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image43.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert44">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image43.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
 Torque - Holding (oz-in / mNm)
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Option 3
   </td>
   <td>
<ul>

<li>
small
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: JSX5300-370
   </td>
   <td>
<ul>

<li>
5VDC
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $14.99
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.tsukasa-d.co.jp/en/data_download/english_catalogue.pdf">Datasheet Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice:** Option 3, JSX5300-370

**Rationale: **The purpose of using this motor is that he is competent enough to work within the range of capabilities we need. Depending on our chip selection, we can only use the dc motor. Compared to the stepper -motor, it performs well in projects that require precise positioning, such as fixation. Considering its size, it provides good torque even at standstill, and it maintains torque as long as the motor is energized.

**Motor Driver**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert44" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image44.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert45">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image44.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Already have this component Previous experience 
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Might not work with brushless motor of our choice
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 1
   </td>
   <td>
<ul>

<li>
 Simple to used
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Not very cheap
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: IFX9201SGAUMA1
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $4.88
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/infineon-technologies/IFX9201SGAUMA1/5415542">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>

<p id="gdcalert45" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image45.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert46">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image45.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Multiphase Motor Driver Power MOSFET I²C, SPI, UART 64-HTQFN 
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Might not work with brushless motor of our choice
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 2
   </td>
   <td>
<ul>

<li>
500mA
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: RAJ306010GNP#AAN
   </td>
   <td>
<ul>

<li>
6V ~ 42V
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $6.49
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/renesas-electronics-america-inc/RAJ306010GNP-AAN/13913292?s=N4IgTCBcDaIEoEEBSBmADANjQRjQcQDkAFAYgQQJAF0BfIA">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td>

<p id="gdcalert46" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image46.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert47">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image46.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Cheap
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Might not work with brushless motor of our choice
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 3
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: ULN2003A
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $0.319
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.ti.com/product/ULN2003A">Taxes Instrument</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice:** Option 1, IFX9201SGAUMA1

**Rationale: **The IFX9201SG from Infineon is a general-purpose 6A H-bridge for applications designed to control small DC motors. It is controlled via PWM/DIR. It is short-circuit and over-temperature protected and provides diagnostics via SPI or basic error feedback via status flags. It has a simple design with few external components; SPI available, making it the best choice of chip for our projects.

**Pressure Sensor Subsystem (Miles):**

**Force/Pressure Sensor**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert47" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image47.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert48">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image47.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Output type: I2C or SPI
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Will require complex mechanical/physical setup for accurate results. (balloon, sealing, etc.)
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 1
   </td>
   <td>
<ul>

<li>
Inexpensive
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: DPS368XTSA1
   </td>
   <td>
<ul>

<li>
Can sense both pressure and temperature
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $4.72
   </td>
   <td>
<ul>

<li>
Low voltage consumption
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/infineon-technologies/DPS368XTSA1/10244079?s=N4IgTCBcDaICIAUDKBmAbADhAXQL5A">Digikey Link</a>
   </td>
   <td>
<ul>

<li>
Does not need separate ADC chip
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert48" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image48.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert49">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image48.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Output type: I2C or SPI
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Will require complex mechanical/physical setup for accurate results. (balloon, sealing, etc.)
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 2
   </td>
   <td>
<ul>

<li>
Has connectors for both tubes
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Expensive
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: HV120-SM02-R
   </td>
   <td>
<ul>

<li>
Differential sensing allows the part to be external from the balloon.
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $33.89
   </td>
   <td>
<ul>

<li>
Does not need separate ADC chip
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/superior-sensor-technology-inc/HV120-SM02-R/10645549">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert49" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image49.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert50">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image49.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Inexpensive
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Will require signal processing.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 3
   </td>
   <td>
<ul>

<li>
Small
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Will require an ADC chip to convert analog value into SPI.
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: GHF-10
   </td>
   <td>
<ul>

<li>
Eliminates the need for the balloon.
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $7.29
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/uneo-inc/GHF-10/15657152">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice:** Option 3, GHF-10

**Rationale: **The team agrees that implementing the force sensor will give more accurate data for a few reasons. Firstly, the team has little experience with atmospheric pressure sensors and failure is more likely. Secondly, we feel the force sensor will more accurately represent a human’s grip strength. The force sensor is relatively inexpensive as well and multiple sensors could be purchased without going over budget. The only drawback being a more complex circuit structure is needed to support this kind of sensor.

**ADC for Force Sensor**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert50" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image50.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert51">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image50.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
3 inputs for 3 sensors
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Option 1
   </td>
   <td>
<ul>

<li>
Outputs SPI
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: SI8902B-A01-GS
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $7.21
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/skyworks-solutions-inc/SI8902B-A01-GS/2791090">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert51" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image51.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert52">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image51.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
2 inputs for 2 sensors
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Option 2
   </td>
   <td>
<ul>

<li>
Outputs SPI
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: MCP3562RT-E/ST
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $4.88
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/microchip-technology/MCP3562RT-E-ST/12807598">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice:** Option 2

**Rationale:** This option has two inputs for two force sensors. It communicates in SPI to the microcontroller which meets class requirements. The other option was discontinued by the manufacturer and is no longer available.

**Op-Amp for Force Sensor Amplification**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert52" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image52.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert53">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image52.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Very Simple
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Long lead time
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 1
   </td>
   <td>
<ul>

<li>
Surface mount
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name: TLV271CW5-7
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $0.50
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/diodes-incorporated/TLV271CW5-7/4747689">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert53" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image53.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert54">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image53.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Very Simple
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Manageable lead time
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 2
   </td>
   <td>
<ul>

<li>
Surface mount
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Name:NCV321SN3T1G
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $0.88
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.digikey.com/en/products/detail/onsemi/NCV321SN3T1G/10321445">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice:** Option 2

**Rationale:** The second option was chosen due to long lead times on the first part. Since these are very basic components there is not much difference about them. Both op-amps meet system and class requirements.

**Temperature Sensor Subsystem (Felicia):**

**Temperature Sensor**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert54" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image54.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert55">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image54.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Meets project requirements. Serial and uses I2C and very affordable 
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Long production times if more parts are required
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option # 1
   </td>
   <td>
<ul>

<li>
Low Power:  \
- 200 µA (typ.) Operating Current  \
- 5 µA (typ.) Standby Mode Current
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Only offers temperature sensing, and not humidity unlike other options
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: STC74A4-3.3VCTTR
   </td>
   <td>
<ul>

<li>
Low voltage required 2.7-5.5V
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Slower response time of 8 seconds
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $1.09
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Digikey Link: <a href="https://www.digikey.com/en/products/detail/microchip-technology/TC74A4-3-3VCTTR/443268">Here</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert55" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image55.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert56">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image55.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Operates between -40Cº - 100Cº

<li>+- 0.5% temperature accuracy 
</li>
</ul>
   </td>
   <td>
<ul>

<li>
If the sensor is exposed to long periods of heat can dehydrate sensor, the read will be off
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option #2
   </td>
   <td>
<ul>

<li>
Quick response time of 6s
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Needs to be hydrated to function at maximum capabilities
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: Honeywell Sensing and Productivity Solutions HIH6030-021-001
   </td>
   <td>
<ul>

<li>
Requires a low voltage between 2.3V - 5.5V
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Moderately expensive
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $13.98
   </td>
   <td>
<ul>

<li>
Meets project requirements
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Digikey Link: <a href="https://www.digikey.com/en/products/detail/honeywell-sensing-and-productivity-solutions/HIH6030-021-001/4291625">Here</a>
   </td>
   <td>
<ul>

<li>
Goes in sleep mode when not in use,  consuming only 1 µA of power versus 650 µA in full operation in a battery operated system
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert56" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image56.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert57">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image56.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Operates between -40Cº - 100Cº

<li>+- 0.4% temperature accuracy 
</li>
</ul>
   </td>
   <td>
<ul>

<li>
If the sensor is exposed to long periods of heat can dehydrate sensor, the read will be off
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option #3
   </td>
   <td>
<ul>

<li>
Requires a low voltage between 2.3V - 5.5V
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Needs to be hydrated to function at maximum capabilities
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name:Honeywell Sensing and Productivity Solutions HIH6131-021-001
   </td>
   <td>
<ul>

<li>
Quick response time of 6s
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Most expensive chip
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $24.61
   </td>
   <td>
<ul>

<li>
Meets project requirements
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Digikey Link: <a href="https://www.digikey.com/en/products/detail/honeywell-sensing-and-productivity-solutions/HIH6131-021-001/2704702">Here</a>
   </td>
   <td>
<ul>

<li>
Goes in sleep mode when not in use,  consuming only 1 µA of power versus 650 µA in full operation in a battery operated system
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice:** Option 2,  Honeywell Sensing and Productivity Solutions HIH6030-021-001

**Rationale: **Utilizing the Honeywell Sensing and Productivity Solutions HIH6030-021-001 temperature and humidity sensor will be the best for our design due to its cost, operational applications, and power consumption. When compared to the other Honeywell component, this part offers the same practical application benefits at a fraction of the cost. Due to its ability to go into sleep mode when not in use, utilizing only 1 µA of power versus 650 µA in full operation, this part will help prevent overload. The only drawback to the Honeywell parts is that if the sensor is exposed to long periods of heat it can be dehydrated, and lose accuracy. This can be resolved by hydrating the component. 

**Mechanical Parts:**

**Glove**


<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert57" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image57.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert58">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image57.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Waterproof
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Will have to modify gloves as their are no mechanical parts
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option #
   </td>
   <td>
<ul>

<li>
Non-slip
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Unsure how well grip sensor would stick
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: Men's waterproof gloves
   </td>
   <td>
<ul>

<li>
Cold-proof
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $6.69
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.temu.com/subject/n9/googleshopping-landingpage-a-psurl.html?goods_id=601099512038485&_bg_fs=1&_p_rfs=1&_x_ads_channel=google&_x_ads_sub_channel=shopping&_x_login_type=Google&_x_vst_scene=adg&sku_id=17592188607946&_x_ns_sku_id=17592188607946&_x_ads_account=6885957807&_x_ads_set=18685731027&_x_ads_id=148363304808&_x_ads_creative_id=630202789800&_x_ns_source=g&_x_ns_gclid=CjwKCAiAleOeBhBdEiwAfgmXf5JK1PPkCRopYth5vR9HdhDvV0j2kFL8MBqp5wPRSZzsl-T_O48FdhoCoVQQAvD_BwE&_x_ns_placement=&_x_ns_match_type=&_x_ns_ad_position=&_x_ns_product_id=17592188607946&_x_ns_wbraid=CjgKCAiAleOeBhA2EigAjs0gWABu7N0V-ac9X0WMRMUJyw9BKlGv6dL2l3AFDVFvxykDswzkGgLCEw&_x_ns_gbraid=0AAAAAo4mICHMQ9EmDsvUbhBLoYQgJWDxs&gclid=CjwKCAiAleOeBhBdEiwAfgmXf5JK1PPkCRopYth5vR9HdhDvV0j2kFL8MBqp5wPRSZzsl-T_O48FdhoCoVQQAvD_BwE&is_back=1">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert58" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image58.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert59">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image58.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Keep fingers exposed
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Expensive
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 2
   </td>
   <td>
   </td>
   <td>
<ul>

<li>
Very little structure to them
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: Freedom Concepts Velcro Gloves
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $81.00
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.adaptivemall.com/velcrogloves.html">Digikey link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



<table>
  <tr>
   <td><strong>Solution</strong>
   </td>
   <td><strong>Pros</strong>
   </td>
   <td><strong>Cons</strong>
   </td>
  </tr>
  <tr>
   <td>

<p id="gdcalert59" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image59.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert60">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


<img src="images/image59.png" width="" alt="alt_text" title="image_tooltip">

   </td>
   <td>
<ul>

<li>
Made of durable materials
</li>
</ul>
   </td>
   <td>
<ul>

<li>
 More expensive compared to alternatives out their
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Option 3
   </td>
   <td>
<ul>

<li>
Fingers exposed to put wires around
</li>
</ul>
   </td>
   <td>
<ul>

<li>
Pressure sensors might be difficult to attach
</li>
</ul>
   </td>
  </tr>
  <tr>
   <td>Name: Fox Reflex Gel sport short gloves
   </td>
   <td>
<ul>

<li>
Velcro strap to keep glove on
</li>
</ul>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>Price per Part: $28.99
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://www.allsportprotection.com/Fox_Reflex_Gel_Short_Gloves_for_BMX_MTB_p/fox0027.htm">Digikey Link</a>
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>


**Choice: **The team agrees that we need to go with some type of gloves that have fingers on them. We feel that is the best choice as it would be easiest to attach the sensors and make sure we can put all the parts on it that we need to. 


# Appendix F: Power Budget



<p id="gdcalert60" ><span style="color: red; font-weight: bold">>>>>>  gd2md-html alert: inline image link here (to images/image60.png). Store image on your image server and adjust path/filename/extension if necessary. </span><br>(<a href="#">Back to top</a>)(<a href="#gdcalert61">Next alert</a>)<br><span style="color: red; font-weight: bold">>>>>> </span></p>


![alt_text](images/image60.png "image_tooltip")



<!-- Footnotes themselves at the bottom. -->
## Notes

[^1]:
<p>
     No PIC16F887, PIC16F917, PIC18F47Q10, or dsPICs allowed

[^2]:
<p>
     General Purpose Input/Output Pins - calculate based on your block diagram and include at least 20% more than you need. Avoid using In-System Programming (ISP) pins for GPIO.
