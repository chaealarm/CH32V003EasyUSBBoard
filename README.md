# CH32V003EasyUSBBoard
Development board of [rv003usb](https://github.com/cnlohr/rv003usb)
![image](https://github.com/chaealarm/CH32V003EasyUSBBoard/assets/12396749/e3bd4d33-15e1-4ed8-9f80-7faf484b4374)
![image](https://github.com/chaealarm/CH32V003EasyUSBBoard/assets/12396749/2f0a0096-e600-4c45-948b-fb9e791707e2)
![image](https://github.com/chaealarm/CH32V003EasyUSBBoard/assets/12396749/4954319f-6c02-4591-b5b4-1fede76bdb7e)
![image](https://github.com/chaealarm/CH32V003EasyUSBBoard/assets/12396749/a6061f60-018c-4803-a858-5e60f1a8069c)

Designed in EasyEDA. 
You can import json files to EasyEDA can open schematic and PCB.

To Order PCB, use Gerber file.
To Order PCB and PCBA, use Gerber, PickAndPlace, BOM files.

## Bill of Materials
1 x CH32V003F4P6(Qin Heng RISC-V Microcontroller)
1 x U254-051T-4BH23-S2B(USB Micro-B Female Connector)
1 x ME6203A33M3G(3.3V 300mA Voltage regulator, also can use ME6211A33M3G(3.3V 500mA) to use more current)
2 x 0603 SMD 10uF Capacitor
2 x 0603 SMD 33 Ohm Resistor(If you don't want to use USB features or want to use PD3, PD4, PD5 as GPIO, Don't solder it)
1 x 0603 SMD 1.5k Ohm Resistor(If you don't want to use USB features or want to use PD3, PD4, PD5 as GPIO, Don't solder it)
2 x Pin header 1x10 of Pitch 2.54mm
1 x Pin header 1x3 of Pitch 2.54mm

## Credits
This design is based on [rv003usb](https://github.com/cnlohr/rv003usb).
(You need both [rv003usb](https://github.com/cnlohr/rv003usb) and [ch32v003fun](https://github.com/cnlohr/ch32v003fun) libraries to using as USB HID device.)
