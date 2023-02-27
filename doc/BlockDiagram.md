Block Diagram:


**Description:**
* To deliver power to our nerve damage pressure glove we will be using a wall outlet that supplies 5V and 1A to power up the device and let it function. Power will pass into a voltage regulator where it will output at 3.3V and proceed to the microcontroller. The microcontroller will be connected to and receive data from all of our sensors. When a user holds on to something with the glove the thin film pressure sensors will relay that information back to the microcontroller via ADC which converts it into an SPI signal. Our ESP32 wifi module utilizes UART and can upload the information to the server at a medical facility or someone's phone.  

**List of Major Components:**

| Part Name/Description                                     | Unit Quantity |
|-----------------------------------------------------------|---------------|
| Temperature Sensor Digital BOM                            |               |
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
