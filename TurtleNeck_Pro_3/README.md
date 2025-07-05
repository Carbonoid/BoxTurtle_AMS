# TurtleNeck Pro 3 - Smart Filament Buffer for BoxTurtle AMS

The TurtleNeck Pro 3 (TNP3) combines the HW parts of the original TurtleNeck Filament Buffer with a small Raspberry RP2040 based MCU board: The Waveshare RP2040-Zero running Klipper. This allows to connect the TNP3 to your klipper host as another MCU via USB-C.

![TurtleNeck Pro 3](https://github.com/Carbonoid/BoxTurtle_AMS/blob/main/TurtleNeck_Pro_3/Fotos/IMG_3107.jpeg)

## BOM - Additional stuff required on top of the original TN parts

+ M3 x 18 mm hex bolts (2x)
+ M3 x 22 mm hex bolts (2x)
+ Waveshare rp2040-zero MCU (1x) (see [Waveshare Wiki](https://www.waveshare.com/wiki/RP2040-Zero))

## Wiring tips

+ Solder C pins of the microswitches to separate GPIOs, e.g. GP12 & GP14.
+ The microswitches NO pins are both soldered to GND on the rp2040-zero.

![Wiring plan](https://github.com/Carbonoid/BoxTurtle_AMS/blob/main/TurtleNeck_Pro_3/Fotos/wiring.png)


## Some fotos of the inside of the TNP3 to help with wiring and assembly

![Switch installation](https://github.com/Carbonoid/BoxTurtle_AMS/blob/main/TurtleNeck_Pro_3/Fotos/IMG_3072.jpeg)
![Switch cable routing](https://github.com/Carbonoid/BoxTurtle_AMS/blob/main/TurtleNeck_Pro_3/Fotos/IMG_3073.jpeg)
![Solder switch wires](https://github.com/Carbonoid/BoxTurtle_AMS/blob/main/TurtleNeck_Pro_3/Fotos/IMG_3074.jpeg)
![TNP3 lid with buttons](https://github.com/Carbonoid/BoxTurtle_AMS/blob/main/TurtleNeck_Pro_3/Fotos/IMG_3076.jpeg)
![TNP3 LED test](https://github.com/Carbonoid/BoxTurtle_AMS/blob/main/TurtleNeck_Pro_3/Fotos/IMG_3081.jpeg)
