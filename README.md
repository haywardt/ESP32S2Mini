# ESP32S2Mini
How to use the ESP32S2 mini LOLIN WEMOS Mini
## Why
Because it has no power LED or Serial Converter to eat up power
Because it breaks out a lot of IO pins
Because it is cheap and simple
## How
Open framework.ino
Create credentials.h
#Loading code the first time:
In board manager select LOLIN s2 Mini
USB CDC on boot: ENABLE
PSRAM Enabled

Press and hold Button 0, press and release RST, release Button 0
Port will appear
Select port and download framework.ino

## Notes
GP00 is button
GP15 is LED_BUILTIN
Deep sleep current with regulator is 40uA at 5v
Current with wifi is about 100mA
Analog Vref is 1.1V
