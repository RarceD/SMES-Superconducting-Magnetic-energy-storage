# SMES-Superconducting-Magnetic-energy-storage
My final project at university:

## 1.0 INTRODUCCTION ##
Superconducting magnetic energy storage (SMES) systems store energy in the magnetic field created by the flow of direct current in a superconducting coil which has been cryogenically cooled to a temperature below its superconducting critical temperature.


## 2.0 POWER AND CONSIDERATION ##
### This system is able to control:

|Energy  | 1   | MJ  | 
|:-----: | :-: | :-: |
|Power   | 2,4 | MVA | 
|Seconds | 1,2 | kV  | 

### Calculate the current:
Using the: E = 1/2 * L * I^2 formula we can obtein the current inside the inductance.

### Vector control:
The control is done with a dsPIC24 processor using 3D vector control:

<img src="https://github.com/RarceD/SMES-Superconducting-Magnetic-energy-storage/blob/master/Imagenes/controlVectorial.JPG" alt="drawing" width="400"/>


### Topology control:
<img src="https://github.com/RarceD/SMES-Superconducting-Magnetic-energy-storage/blob/master/Imagenes/Topology.JPG" alt="drawing" width="400"/>

## 3.0 PCB DESIGN ##
I have used KiCad for designing the 2 layers board, this PCB handle the power and the isolated signals from the dsPIC.

<img src="https://github.com/RarceD/SMES-Superconducting-Magnetic-energy-storage/blob/master/Imagenes/PCB.JPG" alt="drawing" width="400"/>