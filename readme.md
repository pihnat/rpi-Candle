Candle for Raspberry Pi 4
-----------
Candle is a GRBL controller application with G-Code visualizer which is used to control a CNC machine. It's written in Qt. For the Windows and Linux versions and full support please go to the original site

https://github.com/Denvi/Candle

Also use that site for any issues with the software and feature requests.

The information on this site describes how to run Candle on a Raspberry Pi. It's based on issue #77 on Denvi's site

https://github.com/Denvi/Candle/issues/77

Many thanks to everyone who contributed to the discussion there. All I did was to put the information in one place.
 

System requirements for running Candle:
-------------------
Candle runs well on a raspi4. It will also run on a raspi3 but quite sluggishly, a raspi4 is definitely preferred. This version of Candle communicates with an Arduino Uno running GRBL v1.1 firmware.

Downloads:
----------
If you want to just use Candle on the raspi4 then download the following .zip file

* [Candle_1.1.8.zip](https://github.com/pihnat/rpi-Candle/releases/download/v1.1/Candle_1.1.8_for_raspi4.zip)

Click on the 'Wiki' link at the top of this page for full instructions on how to install and run it. Note that you do NOT need to install Qt5. However if you want to modify and re-compile the source code or run a different version of Candle then you will need to install Qt5. This is also explained in detail in the same Wiki. 


Candle's main window:

![screenshot](/screenshots/Screenshot_Candle_on_Raspi4.jpg)
