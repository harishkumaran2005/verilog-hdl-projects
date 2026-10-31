# Verilog HDL Projects

A collection of digital logic design implementations written in Verilog HDL, simulated using ModelSim.

## Projects

| Project | Description | Files |
|---------|-------------|-------|
| [4-Bit ALU](./alu4/) | Arithmetic Logic Unit supporting ADD, SUB, AND, OR, XOR | `alu4.v`, `alu4_tb.v` |
| [8-Bit Full Adder](./full_adder_8bit/) | Ripple-carry 8-bit adder built from 1-bit full adder cells | `full_adder_8bit.v`, `full_adder_8bit_tb.v` |

## Tools Used

- **Language**: Verilog HDL (IEEE 1364)
- **Simulator**: ModelSim
- **Timescale**: `1ns / 1ps`

## Repository Structure

```
verilog-hdl-projects/
+-- alu4/
¦   +-- alu4.v               # 4-bit ALU design module
¦   +-- alu4_tb.v            # Testbench for the 4-bit ALU
¦   +-- README.md
+-- full_adder_8bit/
¦   +-- full_adder_8bit.v    # 8-bit full adder design module
¦   +-- full_adder_8bit_tb.v # Testbench for the 8-bit full adder
¦   +-- README.md
+-- README.md
```

## How to Simulate

Each project folder contains a design file and a testbench. To simulate:

1. Open **ModelSim**
2. Compile the design file first, then the testbench
3. Run the simulation on the testbench module

## Author

**harishkumaran2005**
GitHub: https://github.com/harishkumaran2005
