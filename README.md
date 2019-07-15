# AVR ATmega128 development board

Simple board with ATmega128 microcontroller and breakout connectors for each port

![ATmega base schematic](https://raw.githubusercontent.com/picohari/AVR_Base_M128/master/images/schematic.png)

## Hardware:

* Each port is accessible over Molex 10pin header (Px0 - Px7, +5V, GND)
* L7805 voltage regulator
* Serial driver ic for 2x RS-232
* LCD connector for HD44780 displays (no BUSY reading possible, just wait..)
* Pinheader for display background LED
* Reset button
* 16 MHz crystal oscillator
* Additional +5V and GND pins
* Holes for easy mounting

![ATmega base schematic](https://raw.githubusercontent.com/picohari/AVR_Base_M128/master/images/eagle-avr-base.png)


## Software:

Check out my other GitHub pages for more driver support (only C), I will post some libraries once I've got more time...

