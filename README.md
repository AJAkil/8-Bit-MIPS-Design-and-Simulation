# 8-Bit-MIPS-Design and Simulation
A project involving the design of an 8-bit MIPS CPU as per specification.

## Tools Used
* **Logisim** For designing the processor.
* **Python** For writing the assembler from scratch.

## Files
* **circuit/circuit.circ** - This file is the circuit file for **Logisim** software.
* **Assembler.py** - The assembler for generating hex-codes for the circuit to process the MIPS assembly code.
* **script.sh** - The script to run the assembler with the desired input.
* **input.txt** - The input file containing the mips assembly codes.
* **MIPS.pdf** - The specification of the MIPS project.

## How to Run
Put the assembly codes that needs to be run in the 8-bit MIPS processor in the file **input.txt** or create a file with the 
same name. Run the assembler with **script.sh** script. The required hex-codes will be generated from the assembler. Open up the circuit file in **Logisim** and load the hex codes in the logisim circuit to run the simulation.

## Note
There are some implementation bugs in this version of the assembler that causes malformed hex-codes to be generated for some inputs. Edit the assembler if you face such problems. Bug is to be fixed soon.


