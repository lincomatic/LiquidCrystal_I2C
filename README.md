# Description #

Arduino LiquidCrystal driver for HD44780 LCD connected PCF8574 port expander for I2C access

# Installation #
Create a new folder called "LiquidCrystal_I2C" under the folder named "libraries" in your Arduino sketchbook folder.
Create the folder "libraries" in case it does not exist yet. Place all the files in the "LiquidCrystal_I2C" folder.

# Usage #
To use the library in your own sketch, select it from *Sketch > Import Library*.

-------------------------------------------------------------------------------------------------------------------
This library is based on work done by DFROBOT (www.dfrobot.com).

# ChangeLog #

20210623 SCL
- forked from https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library
  -> seems to be a cleaned up version of DFRobot code
- removed extraneous virtual from write()
- preface all private methods w/ '_'
- move x,y,dots from constructor to begin()