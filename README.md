# motoHUDencl
Enclosure for motoHUD digital speedometer and instrument cluster for motorcycle. Based on STM32F103 micro, 2.8in LCD on ILI9341 SPI driver and X27.168 dial gauge stepper motor

Designed in Fusion360

Files in this repo are designed to fit Derbi Senda motorcycle. Feel free to edit them - i supply project files if Fusion360 format.

If you just want to print it step file is ok - just open them in 3D CAD program of your choice.

Needle of dial gauge prints fine with 0.5 mm nozzle, 0.1mm layer height, 10mm/s speed and 95% flow (hole is undersized, this makes it springy)

motoHUDsig is used to capture information about signals state from bulbs under the original speedometer. It acts as optical isolation between motoHUD and signal wiring.

- PCB & schematic (https://github.com/wiciu15/motoHUDsch/)

- Firmware ( https://github.com/wiciu15/motoHUDini/ )

- Demo video: https://youtu.be/awKXkiaZZUE

![alt text](https://i.imgur.com/zx7ixDC.png)
