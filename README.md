# 32Bit-ALU_Synthesis

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
![WhatsApp Image 2024-11-17 at 11 52 56 PM (3)](https://github.com/user-attachments/assets/ab316aac-fcd1-4c16-9ebc-8aafc54d058a)

#### Area report:
![WhatsApp Image 2024-11-17 at 11 52 56 PM (2)](https://github.com/user-attachments/assets/fa4a55d4-3f68-4d97-ad51-856b1773bb72)

#### Power Report:
![WhatsApp Image 2024-11-17 at 11 52 56 PM (1)](https://github.com/user-attachments/assets/fb18a0a1-63e5-4997-bc65-2d67b09c255e)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
