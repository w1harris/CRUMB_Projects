# 4-bit Counter

## Description

A 4-bit counter with LEDS displaying 4-bit binary value along with dual 7 segment displays showing the decimal value. Powered with a 5v supply and has reset funcitonality. Documentatin for boolean logic available [here](https://steamcommunity.com/sharedfiles/filedetails/?id=2900823549).

[![IMAGE ALT TEXT](https://img.youtube.com/vi/khBXeBu4q2U/0.jpg)](https://youtu.be/khBXeBu4q2U "Video Demo")

## Components

### ICs:
* LM555 Timer or equivalent
* 74HC161 Counter
* 2 x 74HC04 Hex Inverter
* 5 x 74HC08 Quad AND
* 6 x 74HC32 Quad OR

### Resistors:
* 14 x 1kOhm

### Capacitors:
* 1 x .01 uF
* 1 x 1 uF

### Misc:
* 2 seven segment displays
* 1 red LED
* 4 blue LEDS
* 1 button
* 1 switch

## Additional Notes
In simulation the blue LEDs have a forward voltage of 4v to force the voltage high enough to trigger the other ICs. For IRL breadboarding probably going to need to add addition diodes in series or come up with another solution.