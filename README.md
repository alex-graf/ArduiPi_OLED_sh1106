
Fix for Raspberry PI OLED Library Driver for sh1106 spi 
===============================================

**1.** These changes correct the corrupt representation on a sh1106 display (128x64) via spi.
![corrupt output](https://github.com/alex-graf/ArduiPi_OLED_sh1106/blob/master/corrupt.jpg)

**2.** Fix the error:
 `/usr/bin/ld: cannot find -li2c`

**Important:** You have to use a new version of bcm2835.c + .h 
You can download it from here http://www.airspayce.com/mikem/bcm2835/bcm2835-1.58.tar.gz

(I tested the changes only with a oled display sh1106 128x64 via spi and raspberry pi 3b)

The changes are based on the source code from https://github.com/hallard/ArduiPi_OLED. 
**Many thanks to Charles for the good libary!!!** 

Take a look at his good installation post: http://hallard.me/adafruit-oled-display-driver-for-pi/


Installation
============
Pull the changes and replace the fixed files from this repostiory... Compile the libary, the demo and run it.
