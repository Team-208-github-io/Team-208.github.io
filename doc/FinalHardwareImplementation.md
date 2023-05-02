[<Back](https://team-208-github-io.github.io/egr314-team208.github.io/)

# Final Hardware Implementation

## Final Team Schematic

![Team_V10-1](https://user-images.githubusercontent.com/93965371/235608571-b3fe81eb-43c1-4a5c-95eb-5cb1411b4ad4.png)

## Hardware Description:
* Having a requirement of 5V for power input the LM2575 voltage regulator takes in 5V and outputs that at 3.3 V. The power then goes to a barrel jack where the glove is plugged into in order to deliver power. Since the pressure sensor is a passive resistor, it outputs an analog signal. An ADC took the analog signal and converted it into a digital communication protocol so we could communicate with the glove using SPI. An array of 3 LEDs was connected to the temperature sensor. As the temperature increased the LEDs would light up, with a higher temperature corresponding to more LEDs lighting up. Using UART communication protocol the Motor driver enabled bidirectional movement of the motor. When the temperature or force applied was to high then the motor would turn and pull the resistive bands back, causing the fingers to be pulled back. The microcontroller could communicate in all required communication protocols in order to help the system run.  It had 44 pins with a mixture of GPIO and test points. The ESP32 allowed for communication to an MQTT server via WIFI. All parts with the exception of the ESP32 were surface mount components.

## Bill of Materials Page 1

|Part Name/Description|Unit Quantity|Unit Prototype Cost|Total Prototype Cost|Unit Production Cost|Total Production Cost|
|:----|:----|:----|:----|:----|:----|
|Temperature Sensor Digital BOM| | | | | |
|0.1 µF Ceramic Capacitor, +/-10%, X7R, 50V, 0805 package|4|$0.45|$1.80|$0.81|$1.46|
|10K Ohm resistor surfacemount |4|$0.39|$1.56|$0.61|$0.95|
|Temperature Sensor Digital|4|$1.09|$4.36|$1.09|$4.36|
|Barrel Jack|2|$0.00|$0.00|$0.00|$0.00|
|4.7K Ohm resistor surfacemount|2|$0.10|$0.20|$0.20|$0.20|
| | | | | | |
|Shared Test Points BOM| | | | | |
|Test Points|6|$0.42|$2.52|$0.00|$2.52|
|LED - Green  Only takes 2.4 V max|2|$0.31|$0.62|$0.00|$0.62|
|220 Ohm resistor surfacemount|4|$0.00|$0.00|$0.00|$0.00|
| | | | | | |
|Motor and Motordriver BOM| | | | | |
|0.033 µF ±10% 25V Ceramic Capacitor X7R 0805|4|$0.34|$1.36|$0.00|$0.00|
|CAP ALUM 100UF 20% 25V SMD|4|$0.29|$1.16|$0.00|$0.00|
|0.1 µF ±10% 50V Ceramic Capacitor X7R 1206|4|$0.46|$0.92|$0.00|$0.00|
|40V 100Ma Diode|2|$0.80|$1.60|$0.00|$0.00|
|Connector Header Through Hole 6 position 0.098" (2.50mm)|2|$0.27|$0.54|$0.00|$0.00|
|Connector Header Through Hole 12 position 0.100" (2.54mm)|2|$0.00|$0.00|$0.00|$0.00|
|5V DC MOTOR |1|$14.99|$14.99|$0.00|$14.99|
|Full Half-Bridge Drivers|2|$4.88|$9.76|$0.00|$0.00|
| | | | | | |
|Microcontroller and Voltage Regulator BOM| | | | | |
| LM2575 Voltage Regulator|6|$3.00|$18.00|$0.00|$0.00|
|WSU050-4000 AC/DC Convertor|1|$14.41|$14.41|$0.00|$0.00|
|PIC16LF15376-I/PT Microcontroller|6|$2.04|$12.24|$0.00|$0.00|
| | | | | | |
|Force Sensor| | | | | |
|IC ADC 24BIT SIGMA-DELTA 20TSSOP  3.4 V max|2|$4.88|$9.76|$4.88|$9.76|
|Op-Amp for Force Sensor|2|$0.88|$1.76|$0.88|$1.76|
|Sensors RoHS|2|$10.86|$21.72|$10.86|$21.72|
|1K Ohm resistor surfacemount|2|$0.10|$0.20|$0.10|$0.20|


## Bill of Materials Page 2

|Part Name/Description|Manufacturer|Manufacturer Part #|Datasheet Link|
|:----|:----|:----|:----|
|Temperature Sensor Digital BOM| | | |
|0.1 µF Ceramic Capacitor, +/-10%, X7R, 50V, 0805 package|Multicomp|C1206S104K5RACAUTO |https://www.digikey.com/en/htmldatasheets/production/3722546/0/0/1/c1206s104k5racauto.html|
|10K Ohm resistor surfacemount |Vishay Dale|CRCW080510K0JNEB|https://www.vishay.com/docs/20066/rcce3.pdf|
|Temperature Sensor Digital|Microchip Technology|TC74A4-3.3VCTTR|https://ww1.microchip.com/downloads/en/DeviceDoc/21462D.pdf|
|Barrel Jack|Switchcraft Inc.|RAPC742X|https://www.switchcraft.com/assets/1/24/rapc742x_cd.pdf?4751|
|4.7K Ohm resistor surfacemount|Vishay Dale|CRCW12064K70FKEBC|https://www.digikey.com/en/htmldatasheets/production/2718019/0/0/1/crcw1206549rfkeac.html|
| | | | |
|Shared Test Points BOM| | | |
|Test Points|Keystone Electronics|5000|https://www.keyelco.com/userAssets/file/M65p56.pdf|
|LED - Green  Only takes 2.4 V max|Adafruit Industries LLC|LTST-C230KGKT|https://optoelectronics.liteon.com/upload/download/DS22-2000-256/LTST-C230KGKT.pdf|
|220 Ohm resistor surfacemount|YAGEO|CRCW12064K70FKEBC|https://www.yageo.com/upload/media/product/productsearch/datasheet/lr/YAGEO%20CFR_datasheet_2021v0.pdf|
| | | | |
|Motor and Motordriver BOM| | | |
|0.033 µF ±10% 25V Ceramic Capacitor X7R 0805|Aillen|0805B333K250BD
|CAP ALUM 100UF 20% 25V SMD|Panasonic Electronic Components|EEE-FN1E101UV|https://api.pim.na.industrial.panasonic.com/file_stream/main/fileversion/9127|
|0.1 µF ±10% 50V Ceramic Capacitor X7R 1206|Murata|C1206S104K5RACAUTO |https://search.murata.co.jp/Ceramy/image/img/A01X/G101/ENG/RCE_X7R_X7S_25V-100V_E.pdf|
|40V 100Ma Diode|Vishay|M1MA141KT1G|https://www.vishay.com/docs/88692/p600a.pdf|
|Connector Header Through Hole 6 position 0.098" (2.50mm)|JST Sales America Inc.|B5B-XH-A(LF)(SN)|https://www.jst-mfg.com/product/pdf/eng/eXH.pdf|
|Connector Header Through Hole 12 position 0.100" (2.54mm)|Molex|10897120|https://www.molex.com/pdm_docs/sd/010897120_sd.pdf|
|5V DC MOTOR |Tsukasa|JSX5300-370|https://www.tsukasa-d.co.jp/en/data_download/english_catalogue.pdf|
|Full Half-Bridge Drivers|Infineon Technologies|IFX9201SGAUMA1|https://www.infineon.com/dgdl/Infineon-IFX9201SG-DS-v01_01-EN.pdf?fileId=5546d4624cb7f111014d2e8916795dea&ack=t|
| | | | |
|Microcontroller and Voltage Regulator BOM| | | |
| LM2575 Voltage Regulator|Microchip|LM2575T-3.3GOS-ND|https://www.onsemi.com/pdf/datasheet/lm2575-d.pdf|
|WSU050-4000 AC/DC Convertor|Triad Magnetics|533-WSU050-4000-R|https://www.mouser.com/datasheet/2/410/WSU050_4000_R-1892988.pdf|
|PIC16LF15376-I/PT Microcontroller|Microchip|PIC16F18876-I/PT|https://s3.amazonaws.com/snapeda/datasheet/PIC16LF15376-I/PT_Microchip.pdf|
| | | | |
|Force Sensor| | | |
|IC ADC 24BIT SIGMA-DELTA 20TSSOP  3.4 V max|Microchip Technology|MCP3562RT-E/ST|https://ww1.microchip.com/downloads/en/DeviceDoc/MCP3561.2.4R-Data-Sheet-DS200006391A.pdf|
|Op-Amp for Force Sensor|Onsemi|NCV321SN3T1G|https://www.onsemi.com/pdf/datasheet/lmv321-d.pdf|
|Sensors RoHS|UNEO|Uneo GHF10|https://xonstorage.blob.core.windows.net/pdf/uneo_ghf10_xonjuly20_20_link.pdf|
|1K Ohm resistor surfacemount|TE Connectivity Passive Product|CRG1206F1K0|https://www.te.com/commerce/DocumentDelivery/DDEController?Action=srchrtrv&DocNm=1773204&DocType=DS&DocLang=English|


## Front of Team PCB

<img src="ttps://user-images.githubusercontent.com/93965371/235584936-033eb9b9-9dda-40e4-a097-e38e64e9803d.png>
       
## Back of Team PCB

![TSAP_V10_BACK](https://user-images.githubusercontent.com/93965371/235585057-340d5f08-fe59-4ed1-bea1-9b4dc06f512c.png)

## Full Team PCB

![TSAP_V10](https://user-images.githubusercontent.com/93965371/235585417-8f05e2a2-1f07-4390-abd6-e963129dcafd.png)

# Version 2.0

* If we had the chance to create a 2nd version of our project, we would change to a different ADC chip. Our ADC chip came with very little in the way of documentation concerning communication with SPI. We would want to do more research and find a chip that has better support for SPI. We would also want to do more research concerning how our temperature sensors and motor driver could communicate to the MQTT. That was something which took our team a long time to figure out. Making sure we also got our motor driver able to properly communicate using SPI would be a main focus going forward. Originally, we ordered a 12V LM2575 voltage regulator instead of the 5V LM2575.We also ordered a microcontroller that required 5V to program instead of 3.3V, the only difference being an L in the name of the chip. Eventually we were able to get a microcontroller that meant the requirement of being programmed at 3.3V. Double checking that we ordered the correct parts the first time around would save us headaches and prevent us from having to scramble at the last minute  By focusing on these pain points we could solve these problems faster and have more time to figure out any other challenges that might come up while putting together our PCB.
