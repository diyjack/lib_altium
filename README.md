lib_altium: Altium Design Library
=================
_________________

I just figured out ways to improve the design experience with Altium and created my own design library.

source/ is the directory holding all files to generate the integrated libraries.

Some explanations
1. Altium has three kinds of library files:
1) Schematic / Capture Library: *.schlib
2) PCB Library: *.pcblib
3) Integrated Library: *.intlib

2. Integrated libraries are single portable lib files generated by library projects with schematic lib and pcb lib. 

Intention
1. Get all of my previous work organized.
2. Automatic part number input.
3. Beautiful part symbols.

basic01_resistors
basic02_capacitors
basic03_inductors