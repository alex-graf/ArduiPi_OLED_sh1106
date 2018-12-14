Raspberry PI OLED Library Driver for sh1106 spi 
===============================================

These changes correct the corrupt representation on a sh1106 display (128x64) via spi and fixes the error "/usr/bin/ld: cannot find -li2c"
**Important:** Use a new version of bcm2835.c + .h 
You can download it from here http://www.airspayce.com/mikem/bcm2835/bcm2835-1.58.tar.gz
(Tested with oled display sh1106 128 x 64 via spi and raspberry pi 3b)

Please use the source-code from https://github.com/hallard/ArduiPi_OLED and replace the fixed files from this repostiory...
**Many thanks to Charles for the good libary!!!**

Installation
============
Everything is documented on this dedicated post from Charles: http://hallard.me/adafruit-oled-display-driver-for-pi/

