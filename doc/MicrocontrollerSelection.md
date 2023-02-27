## Microcontroller Selection**

**Final Microcontroller Choice: PIC16F18875-I/P**

**Rationale:**
*  Team 208 decided to move forward with PIC16F18875-I/P because of the three microcontrollers it had the most user and application notes. It also meets all of the project's requirements at the lowest overhead and doesn’t require separate hardware to work. This part also comes in a through hole and surface mount option for project implementation.

* After comparing the design of the three microcontrollers, Team 208 decided that the PIC16F18876. Despite having fewer built in SPI’s compared to the other options, the amount of available ADC pins as well as a multitude of  design applications on Microchip's website made this microcontroller the perfect choice for our design. The 36 available IC pins allow for a larger amount of design flexibility when choosing how many sensors we will be implementing. These pins also allow for the flexibility of adding extra test points for future debugging. With the numerous documents on Microchip’s website and support, this chip was the best selection for our team.

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



