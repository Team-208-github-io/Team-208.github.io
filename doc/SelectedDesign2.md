# <a id="_797kv2l8er9t"></a>Selected Design

__Current Design Description:__ The selected design is based mostly on the balloon grip sensor, with aspects from the other two designs\. This new design will have two force sensors on the end of the index finger and the inside of the thumb\. These sensors will be in place of the balloon pressure sensor\. The team decided that the balloon would be too complex to manufacture and calibrate\. The temperature sensor will be on the palm of the glove, this will sense if something is too hot to be touching\. A motor on top of the wrist will pull on resistive bands attached to each finger when a person is exceeding a certain grip strength\. Data from the sensors will be communicated wirelessly\. The PCB itself will not be attached to the glove and instead be housed in a protective case external to the glove\. This external control box will have three LEDs on it to indicate user grip strength\. The design will be powered by a wall power supply and is not designed to be worn casually\. Instead this device will be designed to be used in physical therapy settings with people that have little to no feeling in their hands, due to nerve damage\.

__CAD Assembly of Control Box Housing__

__CAD Exploded Assembly of Control Box Housing__

__Control Box Description:__ The control box will have two holes near the bottom\. One for the signal, power, and ground wires that lead to the glove, and the other for the wall power supply\. The box also features three holes for the three indicator LEDs\. 

__Drawing of Glove__

__Glove Description:__ The glove will feature force sensors on the index finger and the thumb, a temperature sensor on the inside of the palm, and a motor on the back of the hand\. The motor will pull at the resistive bands on each finger\. A cable will run from the glove to the control box that will provide power, ground, and signal transmission\.

# <a id="_38u2zui3pl9g"></a>

# <a id="_rl77ufse3z8p"></a>Block Diagram:

__Description:__ To deliver power to our nerve damage pressure glove we will be using a wall outlet 

that supplies 5V and 1A to power up the device and let it function\. Power will pass into a voltage regulator where it will output at 3\.3V and proceed to the microcontroller\. The microcontroller will be connected to and receive data from all of our sensors\. When a user holds on to something with the glove the thin film pressure sensors will relay that information back to the microcontroller via ADC which converts it into an SPI signal\. Our ESP32 wifi module utilizes UART and can upload the information to the server at a medical facility or someone's phone\.  

# <a id="_6xssmeyxhdev"></a>List of Major Components:

__Part Name/Description__

__Unit Quantity__

Temperature Sensor Digital BOM

0\.1 µF Ceramic Capacitor, \+/\-10%, X7R, 50V, 0805 package

4

10K Ohm resistor surface mount

4

Temperature Sensor Digital

4

Barrel Jack

2

4\.7K Ohm resistor surface mount

2

Shared Test Points BOM

Test Points

6

LED \- Green

2

220 Ohm resistor surface mount

4

Motor and Motor Driver BOM

0\.033 µF ±10% 25V Ceramic Capacitor X7R 0805

4

CAP ALUM 100UF 20% 25V SMD

4

0\.1 µF ±10% 50V Ceramic Capacitor X7R 1206

4

40V 100Ma Diode

2

Connector Header Through Hole 6 position 0\.098" \(2\.50mm\)

2

Connector Header Through Hole 12 position 0\.100" \(2\.54mm\)

2

5V DC MOTOR

1

Full Half\-Bridge Drivers

2

Microcontroller and Voltage Regulator BOM

LM2575 Voltage Regulator

6

WSU050\-4000 AC/DC Convertor

1

PIC16F18876\-I/PT Microcontroller

3

Force Sensor

IC ADC 24 BIT SIGMA\-DELTA 20 TSSOP

2

Op\-Amp for Force Sensor

2

Sensors RoHS

2

1K Ohm resistor surface mount

2
