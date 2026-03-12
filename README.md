# Lazylime-s-Joystick-Mark-II-
Here is arduino code for joystick. Suitable for arduino pro micro USB-C or Micro.
Note to ser, run i2c Scanner first. I recommend you start with 1 i2c module and if the arduino detects it, add another i2c module until all modules are detected. Addresses must be changed for duplicate devices such as PCF8575 and ADS1115 by grounding specific pins on the i2c modules. Once i2c scanner detects all 5 modules with different addresses, upload this code finally to get the joystick buttons working.
