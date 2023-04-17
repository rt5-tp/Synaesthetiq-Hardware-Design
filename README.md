# SynaesthetiQ Hardware

SynaesthetiQ's hardware centre's around a pair of flexible LED Matrices which have been wrapped around a 3D printed core, palced on top of this core is a 30W RGB COB LED.

![Matrcies on Core](./MatricesOnCore.png)
![Big LED Demo](./BigLEDDemo.png)

## AuxBoard

SynaesthetiQ has an Auxillary Board which provides power to both of the matrices, the big led, Raspberry Pi 4B and a fan for cooling. This board is detailed in the [AuxBoard KiCAD project](./AuxBoard/). This board distributes power provided by an ATX power supply while also providing Back Powering protection from the RPI and polyfuse protection to each of the four areas of supply on the board. AuxBoard provides levelshifting from the 3.3v of the RPI's logic to the 5v of the matrices and the big LED.

### Schematic
![AuxBoard Schematic](./AuxBoardSchematic.png)
### PCB Layout
![PCB Layout](./AuxBoardPlacement.png)
### Final PCB's
Below is two of the eventual three PCBs made for the project.
![Final PCB's](./FinalPCBs.png)

## PMOS Switch

Exists to test the functionality of the PMOS Switch circuit being used.

## ZVD Sim

Is a KiCAD project which simulates the Back powering protection built into the SynaesthetiQ AuxBoard.