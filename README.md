# 6KeyMacroPad

Feel free to use/modify the files to make your own macropad! ai03's keyboard design wiki is very helpful, I highly recommend reading it.
This includes all PCB files and CAD files for the case. 

Some pics (I 3D printed and sanded the keycaps by hand so they are not the most even/nice):
![w/ case no lighting](https://i.imgur.com/DQMOESU.jpeg)
![w/ case lighting](https://i.imgur.com/hH4iYNg.jpeg)

# Specs
In-key RGB lighting 
Hot-swappable
Atmega32U2 MCU
USB-C Port
Acrylic stack case
QMK/VIA compatible


# Firmware/QMK/VIA support
Use zadig to install the WinUSB drivers onto the Atmega32u2
Use qmk msys to compile the .hex file to flash onto the MCU
Use qmk toolbox to flash the MCU (to turn the MCU into bootloader mode, press the reset switch on the back of the PCB)
  - There are default and via keymaps (I recommend using the via one so you can easily map macros/your own keys/adjust lighting easily)

# PCB/Build Files
See folder named PCB Gerber files to get the required files to order the PCB. I did not order PCBA but you can do so if you don't want to hand-solder by referencing the BOM and PCB/Schematic files.
![PCB](https://i.imgur.com/XG6y08C.jpeg)
![PCB front](https://i.imgur.com/eVmpVP7.jpeg)

For the case, I provided the .step files in the folder named Case Step Files for each layer of the acrylic stack. I used M2 Screws with some washers and spacers to secure everything together (w/o washers M3 screws and spacers should work fine - might require a little bit of sanding).




