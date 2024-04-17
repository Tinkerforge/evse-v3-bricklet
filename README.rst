EVSE Bricklet 3.0
=================

This repository contains the hardware design
files. The documentation generator configs can be found at
https://github.com/Tinkerforge/generators

The firmware for the EVSE Bricklet 3.0 is shared with the 
EVSE Bricklet 2.0: https://github.com/Tinkerforge/evse-v2-bricklet/

Repository Content
------------------

hardware/:
 * Contains KiCad project files and additionally schematics as PDF

Hardware
--------

The hardware is designed with the open source EDA Suite KiCad
(http://www.kicad.org). Before you are able to open the files,
you have to install the Tinkerforge kicad-libraries
(https://github.com/Tinkerforge/kicad-libraries). You can either clone
them directly in hardware/ or clone them in a separate folder and
symlink them into hardware/
(ln -s kicad_path/kicad-libraries project_path/hardware). After that you
can open the .pro file in hardware/ with KiCad and from there view and
modify the schematics and the PCB layout.
