# FIRST_CYC1000_IO_BOARD_ATLAS_3D_CASE

Cyc1000 3D case

The first free 3D model in GITLAB:
https://gitlab.com/fpga-boards/cyc1000-case

Description


This repository contains the FreeCAD source files needed to print a case for the FPGA project created by the Iniciativa Atlas group.
The carrier board developed by the group is very versatile and can be used with several configurations, ideally a Cyc1000 FPGA and a Raspberry Pi. The first one can be replaced by any other board compatible with the Arduino MKR pinout. On the other hand, any model of Pi can be used and, moreover, using an adapter board, any other microcontroller could be plugged in to configure the FPGA board.
The case provided in this repository was created for a Cyc1000 and a Sipeed Maix Bit mounted on an adapter PCB.



Changing the design


It is quite easy to change the case to fit any other configuration if you are used to FreeCAD. I've tried to identify all the parts clearly but this was my first case design and probably the quality and the organization of parts can be improved.
The concept of this case is to have a common chassis that can be used for different hardware combinations doing the lesser number of changes. For instance, to adapt the design to another microcontroller board, the steps are the following:


First, it is necessary to rework the "Rear" piece. Try to remove the boolean operations that create the holes neede for the Maix Bit and introduce new ones matching your device connectors.
Then you will need to modify the top cover, removing the boolean operation that makes the screen visible.
Finally, you can remove the part that holds the screen (if you are not using one).
Generate the STL files of the parts that you have modified.


Printing

The output folder contains all the STL files needed to create a Cyc1000 plus Maix Bit case. If you modify the project, as said before, you will only need to generate the new or modified parts.


