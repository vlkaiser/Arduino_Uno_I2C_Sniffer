# Arduino_Uno_I2C_Sniffer
Uses an Arduino Uno (or equivalent) to Scan through I2C Addresses on bus connected to Arduino.

On Arduino Uno:
Pin A5 = SCLK
Pin A4 = SDA


Connect A5 to SCLK bus of unknown address peripheral I2C Device(s)

Connect A4 to SDA bus of unknown address peripheral I2C Device(s)

Connect Arduino GND to peripheral GND


Load code from repo in (eg Arduino IDE).  Program Arduino.

Open Serial Monitor (9600 Baud)

Code should automatically execute and scan through addresses 0-127 [7 bit addresses only, no 10 bit address support) 
Serial monitor will report addresses found on I2C bus.
