[![MCHP](../images/microchip.png)](https://www.microchip.com)

 # Sample Accumulator

This example demonstrates how to use the sample accumulation function of the Analog-to-Digital Converter (ADC) to obtain better results that are not affected by noise. The example accumulates 64 samples. The conversion result is represented by the accumulated value divided by 64. By using a hardware accumulator instead of adding those readings in software, the CPU load is reduced.

## Related Documentation
More details and code examples on the AVR128DA48 can be found at the following links:

- [TB3209-Getting Started with Analog-to-Digital Converter (ADC)](http://ww1.microchip.com/downloads/en/Appnotes/TB3209-Getting-Started-with-ADC-DS90003209.pdf)
- [AVR128DA48 Product Page](https://www.microchip.com/wwwproducts/en/AVR128DA48)
- [AVR128DA48 Code Examples on GitHub](https://github.com/microchip-pic-avr-examples?q=avr128da48)
- [AVR128DA48 Project Examples in START](https://start.atmel.com/#examples/AVR128DA48CuriosityNano)

## Software Used
- MPLAB® X IDE 5.40 or newer [(microchip.com/mplab/mplab-x-ide)](http://www.microchip.com/mplab/mplab-x-ide)
- MPLAB® XC8 2.30 or a newer compiler [(microchip.com/mplab/compilers)](http://www.microchip.com/mplab/compilers)
- MPLAB® Code Configurator (MCC) 4.0.1 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- MPLAB® Code Configurator (MCC) Device Libraries 8-bit AVR® MCUs 2.5.0 or newer [(microchip.com/mplab/mplab-code-configurator)](https://www.microchip.com/mplab/mplab-code-configurator)
- AVR-Dx 1.4.75 or newer Device Pack

## Hardware Used
- AVR128DA48 Curiosity Nano [(DM164151)](https://www.microchip.com/Developmenttools/ProductDetails/DM164151)

## Setup
The AVR128DA48 Curiosity Nano Development Board is used as test platform.

 <br><img src="../images/AVR128DA48_CNANO_instructions.PNG" width="500">

The following configurations must be made for this project:
- Set the main clock to 4 MHz
- Configure the ADC in 10-bit mode, choose peripheral clock divided by 4 as clock source and select the 64 sample accumulator. Pin PD6 will be used as ADC input channel
- Configure VREF to use the VDD as voltage reference for ADC and enable the ALWAYS ON feature
- Disable the digital input buffer and the pull-up resistor for pin PD6


 |Pin                       | Configuration      |
 | :---------------------:  | :----------------: |
 |           PD6            | Analog Input       |

 ## Operation
 1. Connect the board to the PC.

 2. Open the Sample_Accumulator.X project in MPLAB® X IDE.

 3. Set the Sample_Accumulator.X project as main project. Right click on the project in the **Projects** tab and click **Set as Main Project**.
 
 <br><img src="../images/Set_as_Main_Project.PNG">

 4. Clean and build the Sample_Accumulator.X project. Right click on the **Sample_Accumulator** project and select **Clean and Build**.

 <br><img src="../images/Clean_and_Build.PNG">

 5. Select the **AVR128DA48 Curiosity Nano** in the Connected Hardware Tool section of the project settings:
   - Right click on the project and click **Properties**
   - Click on the arrow right next to Connected Hardware Tool
   - Select the **AVR128DA48 Curiosity Nano** (click on the **SN**), click **Apply** and then click **OK**:

   <br><img src="../images/Tool_Selection.PNG">

 6. Program the project to the board. Right click on the project and click **Make and Program Device**.

<br><img src="../images/Make_and_Program_Device.PNG">

 ## Summary
This example shows how to use the sample accumulation function of the Analog-to-Digital Converter (ADC) to obtain better results that are not affected by noise.
