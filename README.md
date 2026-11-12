RP2040 Development Board
A custom RP2040 development board designed from the ground up, with the GPIO reference built directly into the PCB.


Why I Built This
I got tired of constantly checking the Raspberry Pi Pico pinout reference while prototyping.

So I decided to design my own RP2040 development board and put the reference information directly onto the silkscreen.

Every GPIO header is labeled with its supported alternate functions, making it easier to identify connections, wire peripherals, and debug without repeatedly opening a datasheet.
Hardware
- MCU: Raspberry Pi RP2040
- Flash: W25Q16JV external QSPI flash
- Clock: 12 MHz crystal
- Power: USB-C with AP2112K-3.3 voltage regulator
- Interfaces: GPIO, UART, SPI, I²C, PWM, ADC
- Debugging: Dedicated SWD header
- Boot: Manual BOOT control
- Design: Custom schematic, PCB layout, routing, and silkscreen
Design Files
File	Description
RP2040.kicad_pcb	KiCad PCB layout
schematic.pdf	Complete circuit schematic
images/	3D PCB renders

**I also included gerber files but it is based for JLCPCB. If that works out fine for you feel free to check out the Bill of Materials and CPL file**
