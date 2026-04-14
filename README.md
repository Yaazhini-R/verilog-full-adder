# Full Adder using Verilog HDL

**Overview**
This project implements a Full Adder using Verilog HDL.  
A Full Adder performs addition of three 1-bit binary inputs and produces Sum and Carry outputs.

**Inputs & Outputs**
- Inputs: A, B, Cin  
- Outputs:  
  - Sum  
  - Carry  

**Logic**
- Sum = A XOR B XOR Cin  
- Carry = (A AND B) OR (B AND Cin) OR (A AND Cin)

**Simulation**
The design is verified using a testbench that checks all possible input combinations.

**Tools Used**
- Xilinx Vivado

**Output**
(Add waveform screenshot here)

**Learning Outcome**
- Understanding of combinational circuits  
- Verilog HDL design  
- Testbench creation and simulation  
