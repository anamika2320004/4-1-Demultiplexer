# 4:1 Demultiplexer (DEMUX) Verilog Project

## Project Overview
This project demonstrates a **4:1 Demultiplexer (DEMUX)** implemented in Verilog. A demultiplexer takes a single input and routes it to one of four output lines based on a 2-bit select line.

**Learning Outcomes:**
- Conditional routing in Verilog
- Understanding 2-bit select lines
- Module reuse in larger digital designs

## Circuit Description
- **Inputs:**
  - `d` : Single data input
  - `sel[1:0]` : 2-bit select line to choose the output
- **Outputs:**
  - `y[3:0]` : 4 output lines, only one active at a time

**Truth Table:**

| sel | Output (y3 y2 y1 y0) |
|-----|---------------------|
| 00  | 0001                |
| 01  | 0010                |
| 10  | 0100                |
| 11  | 1000                |

## Files Included
- `txt file` : 4:1 Demultiplexer module and testbench


## Simulation
The testbench cycles through all select lines and prints the active output.  
Run the simulation in **EDA Playground** or any Verilog simulator.

**Example Output:**
sel=00, y=0001
sel=01, y=0010
sel=10, y=0100
sel=11, y=1000

## How to Run
1. Open `txt file` in a Verilog simulator or EDA Playground.
2. Run the simulation.
3. Observe the console output to verify correct demultiplexer behavior.
