# Exp-5: 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :

![Screenshot 2024-11-23 001403](https://github.com/user-attachments/assets/ff2eb31f-c0db-4ba0-8cde-3f339726e3fc)




#### Area report:


![Screenshot 2024-11-23 001459](https://github.com/user-attachments/assets/2b7f2ab0-6ab2-4943-92c9-97a0ef64a0c4)


#### Power Report:

![Screenshot 2024-11-23 001551](https://github.com/user-attachments/assets/dcc36a1e-7491-445e-b958-995fc015f3eb)




#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
