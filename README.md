# Remote-Surgery-System
Embedded system capstone communication protocol project

Coded by Chunguang(Eric) Xie, Ethan Wang and Gaohong Liu.

This is a remote surgery system where the user could use the keyboard to send command and control a motor for surgery.
The user could change the speed, the position and the movement of the motor on PC serial terminal.
The remote interface would send feedback to PC and print the error if there's a discrepancy between expected voltage level and real voltage level. Then the system would stop working immediately.
There's a SRAM connected to the micro-controller for storage of i2c device address.

Hardware used: PIC18F25K22 micro-controller, Arduino UNO, MAX232, HM6116 SRAM, 74LS24 registers, 74LS04 inverter, EIA-232 Female wire

Communication protocols used: EIA(RS)232, EUART, I2C.

Special thanks to MPLAB Code Configurator.
