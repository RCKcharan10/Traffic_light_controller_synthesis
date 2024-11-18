# EXP6 : Traffic Light Controller -Synthesize the Gate Level Netlist and tabulate Area and Power reports

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :

![Screenshot 2024-11-16 150921](https://github.com/user-attachments/assets/276b33a0-b909-49ab-b366-ffd6dcb8c050)

Area report:

![Screenshot 2024-11-16 150700](https://github.com/user-attachments/assets/58c24cb5-2543-45b4-8b1c-871e33c545f1)

Power Report:

![Screenshot 2024-11-16 150753](https://github.com/user-attachments/assets/4717d044-dd5b-4fce-bf71-8c1cc9d40683)

Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
