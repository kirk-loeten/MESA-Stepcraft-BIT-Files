# MESA-Stepcraft-BIT-Files

The Xilinx ISE is a bit difficult and not manageable for everyone. Therefore I provide the finished bit file for the Stepcraft. 


Standard PINOUT

| I/O | DB25 | DIR | Comment       |
|-----|------|-----|---------------|
| 00  |   1  | OUT | Relais 1      |
| 01  |   14 | OUT | Relais 2      |
| 02  |   2  | OUT | X Dir         |
| 03  |   15 | IN  | Free          |
| 04  |   3  | OUT | X Step        |
| 05  |   16 | OUT | Relais 3      |
| 06  |   4  | OUT | Y Dir         |
| 07  |   17 | OUT | Free          |
| 08  |   5  | OUT | Y Step        |
| 09  |   6	 | OUT | Z Dir         |
| 10  |   7  | OUT | Z Takt        |
| 11  |   8	 | OUT | A Dir         |
| 12  |   9	 | OUT | A Step        |
| 13  |   10 | IN  | Toolsensor    |
| 14  |   11 | IN  | Notaus        |
| 15  |   12 | IN  | Endstop X/Y/Z |
| 16  |   13 | IN  | Endstop A     |

all intern I/O 17 - 33 just GPIO

MyMod PINOUT

| I/O | DB25 | DIR | Comment       |
|-----|------|-----|---------------|
| 01  |   14 | OUT | PWM Spindle   |
