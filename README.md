      ===========================
     ||   _________       _     ||
     ||  |__   __  |    _| |_   ||
     ||     | |  | |   |_   _|  ||
     ||     | |  | |____ |_|    ||
     ||     |_|  |______|       ||
     ||                         ||
      ===========================


Timelapse+ Firmware [![Build Status](https://travis-ci.org/timelapseplus/TimelapsePlus-Firmware.png)](https://travis-ci.org/timelapseplus/TimelapsePlus-Firmware)
===================

Official Firmware for the Timelapse+ Intervalometer [https://www.timelapseplus.com]

Download prepackaged binaries from http://firmware.timelapseplus.com

Requirements
------------

avr-gcc  
dfu-programmer  
libusb  

Mac users: do not use the CrossPack installer -- it's broken and won't work with this firmware.  Instead, use homebrew with this formula: http://github.com/larsimmisch/homebrew-avr


Building/Programming
--------

First, connect the Timelapse+ device via USB and boot in DFU mode (hold top two buttons and press the down button, red light will blink).  Then, run the following two commands in the project folder:

make  
make dfu  



