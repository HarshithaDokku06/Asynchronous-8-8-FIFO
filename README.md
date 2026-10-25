# 8×8 Asynchronous FIFO using Verilog

## Overview
This project implements an 8-bit-wide, 8-entry asynchronous FIFO using Verilog. It transfers data between independent read and write clock domains.

## Features
- 8 entries with 8-bit data width
- Independent read and write clocks
- Binary and Gray-code pointers
- Two-stage clock-domain synchronizers
- Full and empty status flags
- Protection against overflow and underflow
- Self-checking testbench for functional verification

## Tools
- Verilog/SystemVerilog simulator
- Verilator or Icarus Verilog

## Verification
The testbench checks FIFO reset, data ordering, full and empty conditions, overflow and underflow protection, and concurrent read/write operations.

## Learning Outcomes
- Asynchronous FIFO architecture
- Clock-domain crossing (CDC)
- Gray-code pointer synchronization
- Verilog design and functional verification

## Future Improvements
- Add assertions and functional coverage
- Verify different clock-frequency ratios
- Perform CDC analysis and synthesis
- Extend the design with parameterized FIFO depth and data width
