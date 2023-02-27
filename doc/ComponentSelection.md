[<Back](https://team-208-github-io.github.io/Team-208/)

# Component Selection

**List of Major Components:**

| Part Name/Description                                     | Unit Quantity |
|-----------------------------------------------------------|---------------|
| Temperature Sensor Digital BOM                            | 1             |
| 0.1 µF Ceramic Capacitor, +/-10%, X7R, 50V, 0805 package  | 4             |
| 10K Ohm resistor surface mount                            | 4             |
| Temperature Sensor Digital                                | 4             |
| Barrel Jack                                               | 2             |
| 4.7K Ohm resistor surface mount                           | 2             |
|                                                           |               |
| Shared Test Points BOM                                    |               |
| Test Points                                               | 6             |
| LED - Green                                               | 2             |
| 220 Ohm resistor surface mount                            | 4             |
|                                                           |               |
| Motor and Motor Driver BOM                                |               |
| 0.033 µF ±10% 25V Ceramic Capacitor X7R 0805              | 4             |
| CAP ALUM 100UF 20% 25V SMD                                | 4             |
| 0.1 µF ±10% 50V Ceramic Capacitor X7R 1206                | 4             |
| 40V 100Ma Diode                                           | 2             |
| Connector Header Through Hole 6 position 0.098" (2.50mm)  | 2             |
| Connector Header Through Hole 12 position 0.100" (2.54mm) | 2             |
| 5V DC MOTOR                                               | 1             |
| Full Half-Bridge Drivers                                  | 2             |
|                                                           |               |
| Microcontroller and Voltage Regulator BOM                 |               |
| LM2575 Voltage Regulator                                  | 6             |
| WSU050-4000 AC/DC Convertor                               | 1             |
| PIC16F18876-I/PT Microcontroller                          | 3             |
|                                                           |               |
| Force Sensor                                              |               |
| IC ADC 24 BIT SIGMA-DELTA 20 TSSOP                        | 2             |
| Op-Amp for Force Sensor                                   | 2             |
| Sensors RoHS                                              | 2             |
| 1K Ohm resistor surface mount                             | 2             |

**Description:**

* The bill of materials contains all the parts each section of the nerve damage therapy glove will be utilizing. All parts meet the requirements and unless specified otherwise are surface mounted.  Everything from the voltage regulators to the OP-AMP and even our resistors and capacitors are surface-mounted. The only parts that aren’t surface mounted are the barrel jack, motor, microcontroller, and wall plug to supply power to the device.  A variety of communication methods are utilized such as SPI, UART, and I2C.  Our wall power supply supplies voltage at a measurement of 5V and 1A to a switching voltage regulator. From the switching voltage regulator the power drops down and comes out to 3.3 V. Our force sensors are resistive which utilize an ADC device to convert their analog signals to SPI so it can be read by the microcontroller. The ESP32 utilizes UART to communicate all this data over wifi to a digital storage space such as someone’s personal device or the medical records system at a doctor’s office. 


**Power Budget Table:**

| Power Budget                                                                                                                                                                                                                                                                                                                                                                                                       |                                                              |                  |              |     |              |      |       |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|------------------|--------------|-----|--------------|------|-------|
| Team Number:                                                                                                                                                                                                                                                                                                                                                                                                       | 208                                                          |                  |              |     |              |      |       |
| Project Name:                                                                                                                                                                                                                                                                                                                                                                                                      | Nerve Damage Thearpy Glove                                   |                  |              |     |              |      |       |
| Team Member Names:                                                                                                                                                                                                                                                                                                                                                                                                 | Miles Wilson, Kyle Selasky, Mingqi Yu, Felicia Szleszinski   |                  |              |     |              |      |       |
| Version:                                                                                                                                                                                                                                                                                                                                                                                                           | 1                                                            |                  |              |     |              |      |       |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |              |     |              |      |       |
| A. List ALL major components (active devices, integrated circuits, etc.) except for power sources, voltage regulators, resistors, capacitors, or passive elements                                                                                                                                                                                                                                                  |                                                              |                  |              |     |              |      |       |
| All Major Components                                                                                                                                                                                                                                                                                                                                                                                               | Component Name                                               | Part Number      | "Supply      |
| Voltage                                                                                                                                                                                                                                                                                                                                                                                                            |
| Range"                                                                                                                                                                                                                                                                                                                                                                                                             | #                                                            | "Absolute        |
| Maximum                                                                                                                                                                                                                                                                                                                                                                                                            |
| Current (mA)"                                                                                                                                                                                                                                                                                                                                                                                                      | "Total                                                       |
| Current                                                                                                                                                                                                                                                                                                                                                                                                            |
| (mA)"                                                                                                                                                                                                                                                                                                                                                                                                              | Unit                                                         |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Force Sensor                                                 | GHF-10           |  +3.3-5V     | 3   | 100          | 300  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Force ADC SPI Chip                                           | MCP3562RT-E/ST   | 1.8-3.6V     | 1   | 100          | 100  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Temperature Sensor                                           | HIH6030-021-00   |  +2.7-5.5V   | 1   | 650          | 650  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Motor                                                        | JSX5300-370      |  +5V to -5V  | 1   | 240          | 240  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Motor Driver                                                 | IFX9201SGAUMA1   | 0-50V        | 1   | 500          | 500  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | ESP32                                                        |  ESP32­WROOM­32  | 3-3.6V       | 1   | 150          | 150  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Switching Regulator                                          | LM2575           |  +2.3-6V     | 1   | 7            | 0.08 | mA    |
| "B. Assign each major component above to ONE power rail below. Try to minimize the number of different power rails in the design.                                                                                                                                                                                                                                                                                  |
| Add additional power rails or change the power rail voltages if needed."                                                                                                                                                                                                                                                                                                                                           |                                                              |                  |              |     |              |      |       |
|  +3.3V Power Rail                                                                                                                                                                                                                                                                                                                                                                                                  | Component Name                                               | Part Number      | "Supply      |
| Voltage                                                                                                                                                                                                                                                                                                                                                                                                            |
| Range"                                                                                                                                                                                                                                                                                                                                                                                                             | #                                                            | "Absolute        |
| Maximum                                                                                                                                                                                                                                                                                                                                                                                                            |
| Current (mA)"                                                                                                                                                                                                                                                                                                                                                                                                      | "Total                                                       |
| Current                                                                                                                                                                                                                                                                                                                                                                                                            |
| (mA)"                                                                                                                                                                                                                                                                                                                                                                                                              | Unit                                                         |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Force Sensor                                                 | GHF-10           |  +3.3-5V     | 3   | 100          | 300  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Temperature Sensor                                           | HIH6030-021-00   |  +2.7-5.5V   | 1   | 650          | 650  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Force ADC SPI Chip                                           | MCP3562RT-E/ST   | 1.8-3.6V     | 1   | 100          | 100  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | ESP32                                                        | ESP32WROOM32     | 3-3.6V       | 1   | 150          | 150  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |              |     |              | 0    | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Subtotal                                                     |                  |              |     |              | 1200 | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Safety Margin                                                |                  |              |     |              | 25%  |       |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Total Current Required on +3.3V Rail                         |                  |              |     |              | 1500 | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |              |     |              |      |       |
| c1. Regulator or Source Choice                                                                                                                                                                                                                                                                                                                                                                                     |  +3.3V Switching Regulator                                   | LM2575           |  4.75V-40V   | 3.3 | 1000         | 3300 | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Total Remaining Current Available on +3.3V Rail              |                  |              |     |              | 1800 | mA    |
| C. For each power rail above, select a specific voltage regulator using the same process as for major component selection. Confirm that the Total Remaining Current Available on each rail above is not negative.                                                                                                                                                                                                  |                                                              |                  |              |     |              |      |       |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |              |     |              |      |       |
| D. Select a specific external power source (wall supply or battery) for your system, and confirm that it can supply all of the regulators for all of the power rails simultaneously. If you need multiple power sources, list each separately below and indicate which regulators will be connected to each supply. Confirm that the Total Remaining Current Available on each power source below is not negative. |                                                              |                  |              |     |              |      |       |
| External Power Source 1                                                                                                                                                                                                                                                                                                                                                                                            | Component Name                                               | Part Number      | "Supply      |
| Voltage                                                                                                                                                                                                                                                                                                                                                                                                            |
| Range"                                                                                                                                                                                                                                                                                                                                                                                                             | Output Voltage                                               | "Absolute        |
| Maximum                                                                                                                                                                                                                                                                                                                                                                                                            |
| Current (mA)"                                                                                                                                                                                                                                                                                                                                                                                                      | "Total                                                       |
| Current                                                                                                                                                                                                                                                                                                                                                                                                            |
| (mA)"                                                                                                                                                                                                                                                                                                                                                                                                              | Unit                                                         |
| Power Source 1 Selection                                                                                                                                                                                                                                                                                                                                                                                           | Plug-in Wall Supply                                          | WSU050-4000      | 90 ~ 264 VAC | 5V  | 4000         | 4000 | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |              |     |              |      |       |
| Power Rails Connected to External Power Source 1                                                                                                                                                                                                                                                                                                                                                                   |                                                              |                  |              |     |              |      |       |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |  +3.3V Switching Regulator                                   | LM2575           | 4.75V-40V    | 3.3 | 1000         | 3300 | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Motor Driver                                                 | IFX9201SGAUMA1   | 5V-50V       | 5V  | 500          | 500  |       |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Total Remaining Current Available on External Power Source 1 |                  |              |     |              | 200  | mA    |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |              |     |              |      |       |
| E. Calculate Battery Life (if applicable).  For each battery, also check the worst-case lifetime of the battery by indicating the capacity in mAh.                                                                                                                                                                                                                                                                 |                                                              |                  |              |     |              |      |       |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | Component Name                                               | Part Number      | "Supply      |
| Voltage                                                                                                                                                                                                                                                                                                                                                                                                            |
| Range"                                                                                                                                                                                                                                                                                                                                                                                                             |                                                              | "Capacity        |
| (mAh)"                                                                                                                                                                                                                                                                                                                                                                                                             | "Required                                                    |
| By                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Regulators"                                                                                                                                                                                                                                                                                                                                                                                                        |                                                              |
|                                                                                                                                                                                                                                                                                                                                                                                                                    | N/A                                                          | N/A              | N/A          | N/A | N/A          | N/A  |       |
|                                                                                                                                                                                                                                                                                                                                                                                                                    |                                                              |                  |              |     | Battery Life | N/A  | hours |
| Notes                                                                                                                                                                                                                                                                                                                                                                                                              |                                                              |                  |              |     |              |      |       |
| External Supply Voltage should be determined by the dropout voltage for highest-voltage regulator (e.g., +14V for a +12V regulator).                                                                                                                                                                                                                                                                               |                                                              |                  |              |     |              |      |       |
| If you have multiple units in your design (e.g., a base unit and remote unit) then you need a separate power budget for each unit 



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

 ![image1](https://user-images.githubusercontent.com/122938115/221623248-20917da3-98b9-44e0-af0a-95db8d589487.png)

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

 ![image2](https://user-images.githubusercontent.com/122938115/221623287-8b3a3816-fcee-4c85-8660-1cdb932aab70.png)

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

 ![image3](https://user-images.githubusercontent.com/122938115/221623317-3504b470-996a-4114-8fda-ad4f09635e93.png)

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

![image4](https://user-images.githubusercontent.com/122938115/221623332-6355115c-b87a-4fb9-9b4e-0617c9cec1de.png)

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

![image5](https://user-images.githubusercontent.com/122938115/221623353-a7bdde8b-d168-4ad1-afdb-1ce698accdf3.png)

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

![image6](https://user-images.githubusercontent.com/122938115/221623386-4f385571-ee3d-4c42-8ab5-43cdb4d74017.png)

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

![image7](https://user-images.githubusercontent.com/122938115/221623413-1d307659-331b-41c2-9de2-84ec6295036c.png)

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

![image9](https://user-images.githubusercontent.com/122938115/221623456-5b0742ea-282a-407f-83b5-6c9e5989dd7d.png)

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

![image10](https://user-images.githubusercontent.com/122938115/221623481-8c813bef-1c2e-47b5-84ef-c38b5d7fd14e.png)

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

![image11](https://user-images.githubusercontent.com/122938115/221623508-8d9e44b3-241e-419d-8a42-698e2c993079.png)

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

![image12](https://user-images.githubusercontent.com/122938115/221623536-96b451f6-aee7-467e-9838-dc30dd1cf05a.png)

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

![image13](https://user-images.githubusercontent.com/122938115/221623581-7853ceb3-7b48-4046-aa15-ae0c5991eac1.png)

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

![image14](https://user-images.githubusercontent.com/122938115/221623605-a7295342-5891-4ed2-bbd1-84d34ffc98d3.png)

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

![image15](https://user-images.githubusercontent.com/122938115/221623633-fd2ff358-b5cc-4977-93e6-38ea37f02772.png)

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

![image16](https://user-images.githubusercontent.com/122938115/221623660-e434a500-1374-4e1e-8d9b-290f0af5d43b.png)

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

![image16](https://user-images.githubusercontent.com/122938115/221623685-7072b3b8-992c-42d2-a801-e90cbfd29f19.png)

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

![image17](https://user-images.githubusercontent.com/122938115/221623709-6ffe869c-a5a3-4335-a193-7d621747a03a.png)

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

![image18](https://user-images.githubusercontent.com/122938115/221623764-c364cf68-89f3-45ae-adf2-a33bf1a74485.png)

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

![image19](https://user-images.githubusercontent.com/122938115/221623794-1845cf82-ad5e-4482-8808-a11f5d808227.png)

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

![image20](https://user-images.githubusercontent.com/122938115/221623823-985842fd-6611-4a26-a1c1-b8a1fd6cfe5a.png)

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

![image21](https://user-images.githubusercontent.com/122938115/221623862-400c779a-a6a4-4c68-ad61-0d6cd0dcf58d.png)

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

![image22](https://user-images.githubusercontent.com/122938115/221623892-9d023a92-175a-4309-8019-ac8b6de2b707.png)

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

![image23](https://user-images.githubusercontent.com/122938115/221623913-105c925a-353e-4806-849c-d9b685439d3c.png)

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

![image24](https://user-images.githubusercontent.com/122938115/221623949-b385e40b-d2a3-43b4-a916-7036926df6c1.png)

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

![image25](https://user-images.githubusercontent.com/122938115/221623977-be4e7871-91be-4c9c-9700-656318445193.png)

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

![image26](https://user-images.githubusercontent.com/122938115/221624000-3aaa0d3c-73b8-49d6-8ce2-d00e8d6e12a4.png)

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

