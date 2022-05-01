
# TTGOAlienAttack

Alien Attack game on an ESP32 development board with a colour LCD screen.

Project was forked from (https://github.com/VolosR/TTGOAlienAttack). A [video](https://youtu.be/b8254--ibmM) explains how to set this up with Arduino.

This fork adds some simple code formatting and adapts the project to use PlatformIO to better facilitate support for additional boards without mangling the source code.

## Build
Build and install it using PlatformIO:

```bash
pio run --target upload
```

Edit src\platform.ini to add more boards and configure the TFT_eSPI library.