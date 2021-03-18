[![MCHP](images/microchip.png)](https://www.microchip.com)

# Getting Started with Analog-to-Digital Converter (ADC) Examples (MPLAB® X)

This repository contains examples of MCC-generated source code for Analog-to-Digital Converter (ADC) as described in the [TB3209-Getting Started with Analog-to-Digital Converter (ADC)](http://ww1.microchip.com/downloads/en/Appnotes/TB3209-Getting-Started-with-ADC-DS90003209.pdf) document from Microchip. The repository contains five MPLAB® X projects inside:

* [<strong>ADC Event Triggered:</strong>](Event_Triggered) This project has the purpose to provide an example on how to configure the ADC to trigger a conversion on a specific event (for more details, see [<strong>ADC Event Triggered</strong>](Event_Triggered))
* [<strong>ADC Free Running:</strong>](Free_Running) This example uses ADC in Free Running mode. When configuring the ADC in Free Running mode, the next conversion starts immediately after theprevious one completes (for more details, see [<strong>ADC Free Running</strong>](Free_Running))
* [<strong>ADC Sample Accumulator:</strong>](Sample_Accumulator) This example uses the ADC in Sample Accumulator mode. In Sample Accumulator mode, the ADC can add up to 64 samples in an accumulator register (for more details, see [<strong>ADC Sample Accumulator</strong>](Sample_Accumulator))
* [<strong>ADC Single Conversion:</strong>](Single_Conversion) This example shoes how to use the ADC to make a single conversion (for more details, see [<strong>ADC Single Conversion</strong>](Single_Conversion))
* [<strong>ADC Window Comparator:</strong>](Window_Comparator) This example uses the ADC in Window Comparator mode, the device can detect if the ADC result is below or above a specific threshold value (for more details, see [<strong>ADC Window Comparator</strong>](Window_Comparator))

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
