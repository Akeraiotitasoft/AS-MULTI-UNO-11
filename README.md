# AS-MULTI-UNO-11
Multi-Use Board - Partially Ardunio pin compatible with the exception of voltage regulation

Only 5V pin, IOREF, and AREF voltage pins are connected. (Vin and 3.3V are not).
Speed is 16MHz.
Based On ATMEGA328-PU

How to use:
1. Set the fuses to arduino fuses
2. Use SPI (ICSP) programmer and load the Arduino Boot Loader for Arduino UNO R3.
3. Attach an FTDI cable or breakout board that supports DTR and you can program this just like an Arduino UNO R3.  (Adafruit has FTDI friend but you have to configure for DTR and connect upside down).
