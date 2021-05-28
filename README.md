# CROSSROAD-LAB-MICRO-1284P

![1](https://user-images.githubusercontent.com/83240004/120014216-158cdf80-bfe2-11eb-89ea-bab2adac993a.png)

## GENERAL INFORMATION

#### MICRO 1284P is an open-source microcontroller based on the ATmega1284P. It features 24 digital input/output pins (of which 6 can be PWM outputs), 8 analog input pins, a 16 MHz ceramic resonator, an ICSP pin header, a reset button, and an LED is connected to pin 13. To power the microcontroller you can use the 5 volts of the serial or from 7 volts to 35 volts from the Vin pin (use one of the two methods, not both together). With its small size it allows its insertion in very compact projects.

## CORE SPECIFICATION

| Syntax      | Description | 
| :----:        |    :----:   |
| Memory type      | Flash       |
| Memory dimension (KB)   | 128        | 
| CPU Speed (MIPS/DMIPS)      | 20       |
| SRAM (B)   | 16384        | 
| EEPROM/HEF (bytes)      | 4096       |
| Communication Devices   | 2-UART, 3-SPI, 1-I2C        | 
| PWM      | 6 PWM pin       |
| Timer   | 2x8-bit, 2x16-bit        | 
| Number of comparators      | 1       |
| Operating temperature (°C)   | -40 to 85        | 
| Operating voltage   | 1.8 to 5.5        |

## PINOUT

![MICRO1284P_pinout](https://user-images.githubusercontent.com/83240004/118401468-26deff00-b666-11eb-8a3d-0f5df2917b50.png)

## LIBRARIES INSTALLATION

For download and installing libraries visit:
https://github.com/MCUdude/MightyCore#manual-installation

## HOW TO UPLOAD SKETCHES USING SERIAL PORT (UART)

First of all you need a USB TTL FTDI (like this https://t.ly/cMAf or this https://t.ly/RZF8) that will allow the sketch to be written to the microcontroller. First, however, preliminary operation must be carried out: 

- Burning the bootloader (visit this link for more information: https://www.arduino.cc/en/Tutorial/BuiltInExamples/ArduinoToBreadboard)

Connection between FTDI and MEGA 1284P:

| FTDI        |       |    MICRO 1284P   |
| :----:        |    :----:   |    :----:   |
| Vcc        |    <------->   |    5v   |
| Gnd        |    <------->   |    Gnd   |
| Tx        |    <------->   |    Rx   |
| Rx        |    <------->   |    Tx   |
| RTS/DTR        |    <------->   |    DTR   |

## PROJECT SITE

https://www.crossroadnetwork.org/CrossRoadLAB/projects/MICRO1284P.html

