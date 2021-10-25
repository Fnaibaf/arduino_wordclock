# Think Wordclock
Arduino sourcecode for my DIY Wordclock.

## Features
This project includes following features:
- Arduino Nano as microcontroller
- 114 NeoPixel LEDs WS2812b as Zic-Zac matrix starting from top left  
- RTC module DS3231
- DCF77 receiver for german clock signal
- 7 different color modes (switched when turn off/on within 10 seconds after startup)
- light sensor to adjust brightness of LEDs to environment

## Full Tutorial
The full tutorial how to build this Wordclock is published on 

https://think-thi.de/2020/12/08/diy-wortuhr-mit-arduino-und-neopixel/

https://techniccontroller.de/word-clock-with-arduino-and-neopixel/

## Used Libraries
To be able to use this sourcecode, you need to install following libraries in Arduino IDE.
I added also my used versions of the libaries in this repository. 
In case of some incompatibility issues please use my provided versions.

- https://github.com/adafruit/RTClib
- https://github.com/PaulStoffregen/Time
- https://github.com/thijse/Arduino-DCF77
- https://github.com/adafruit/Adafruit-GFX-Library
- https://github.com/adafruit/Adafruit_NeoPixel
- https://github.com/adafruit/Adafruit_NeoMatrix

