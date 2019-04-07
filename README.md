# C64 for [DE1-SoC Edition of MiSTer](https://github.com/MiSTer-DE1-SoC/Main_MiSTer/wiki)

![C64 DE10-Standard FPGA](https://user-images.githubusercontent.com/48859672/55352045-3d469280-54c0-11e9-9253-6b6ef8164dc1.JPG)

Based on FPGA64 by Peter Wendrich with heavy later modifications by different people.

## Features
- C64 and C64GS modes.
- Disk read/write support (*.D64)
- Amost all cartrige formats (*.CRT)
- Direct file injection (*.PRG)
- Dual SID with several degree of mixing 6581/8580 from stereo to mono.
- Similar to 6581 and 8580 SID filters.
- OPL2 sound expander.
- 4 joysticks mode.
- UART connection to Internet.
- Loadable Kernal/C1541 ROMs.
- Special reduced border mode for 16:9 display.

## Installation
Copy the *.rbf to the root of the SD card. Copy disks/carts to C64 folder.

## Usage

### Keyboard
* F2,F4,F6,F8,Left/Up keys automatically activate Shift key.
* F9 - pound key.
* F10 - plus key.
* F11 - restore key. Also special key in AR/FC carts.
* Alt - C= key.

### Loadable ROM
Alternative ROM can be placed in C64 folder with the name boot.rom.
Format is simple concatenation of Kernal.rom + C1541.rom

### Autoload the cartridge
Place the desired cartridge with the name boot3.rom in C64 folder to autoload it on start.


This project brought to you by http://www.modernhackers.com
