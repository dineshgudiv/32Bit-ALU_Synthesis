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
![WhatsApp Image 2024-11-18 at 11 41 05_80d4d56c](https://github.com/user-attachments/assets/399e5bce-b13b-4071-bf23-2e1e3e8f833b)


#### Area report:
![WhatsApp Image 2024-11-18 at 11 41 05_6e187946](https://github.com/user-attachments/assets/9277e2ed-0dbe-4074-81c7-1fe547662ee2)

#### Power Report:
![WhatsApp Image 2024-11-18 at 11 41 05_56828132](https://github.com/user-attachments/assets/60d990e3-3cc1-4a52-a110-bfe04aacfb90)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
