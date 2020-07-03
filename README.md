kicad-footprints-bee
====================

This repository contains KiCad footprints used by [bees](https://github.com/beecourse).

Installation
------------
Clone this repository to a directory of your choice.
Open a project in KiCad and (in the project window) go to _Tools_ > _Edit PCB Footprints_.
In the appearing _Footprint Editor_ go to _Preferences_ > _Manage Footprint Libraries_.
Via _Browse Libraries_ select every .pretty folder you want to add (use CTRL key to select multiple folders).

Hints on footprint creation
---------------------------
Before creating a new part, please check if it already exists in the [official footprint library](https://github.com/KiCad/kicad-footprints).
Please adhere to the [KiCad library convention](http://kicad-pcb.org/libraries/klc/).
KLC compliance can be checked with the python script `check_kicad_mod.py`, which is included in the [KiCad library utils](https://github.com/KiCad/kicad-library-utils).
If the .pretty folder you want to create already exists in the official KiCad footprint library, please append the suffix "-bee" to prevent errors on library import.
