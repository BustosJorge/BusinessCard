# Business Card

## Description
This is the first version of my business card, it is based on an ATMEGA328P that can be configured to be used as an Arduino Nano and uses the Arduino Uno pinout. **Please note that this project is still in development and not yet complete.**

![Business_Card_front](/PCB_Business_Card/business_card_front.JPG)
![Business_Card_back](/PCB_Business_Card/business_card_back.JPG)

## Circuit Diagram



## Assembly Instructions
1. Connect the electronic components as per the provided circuit diagram.
2. Load the bootloader on atmega328p with the help of an arduino board, through the ICSP connector. You can search on the internet how to do it, here is some documentation of Arduino [Arduino as ISP and Arduino Bootloaders](https://docs.arduino.cc/built-in-examples/arduino-isp/ArduinoISP/), although you can search for a more specific tutorial.
3. Connect the board to the USB and open the Arduino editor.
4. Select the COM port and the arduino nano development board.
5. Upload sketch, if not visible, Upload sketch by Arduino ISP programmer, here is some documentation [Getting Started with the Arduino ISP](https://docs.arduino.cc/retired/getting-started-guides/ArduinoISP/) or you can search for a tutorial how to upload sketch by ISP.

## License
This project is licensed under the MIT License. 

## Contact
Jorge Bustos - bustos.jorge21@gmail.com

Project Link: https://github.com/BustosJorge/BusinessCard