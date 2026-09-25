a running log, one short entry per week: what got done, what's next

# RISC-V Single-Cycle CPU Project

This document tracks the main design decisions and progress for our CPU design.

## Architecture Overview
The CPU consists of three main hardware modules:
* **ALU**: Handles mathematical operations like ADD and SUB.
* **Register File**: Stores 32 registers for temporary data.
* **Control Unit**: Decodes instructions and generates control signals.

> **Note:** The ALU was tested first using the `alu_tb.v` testbench to ensure flags are set correctly.

## Next Steps
- [x] Complete ALU design
- [ ] Implement Register File
- [ ] Connect Control Unit to Datapath

PLACEHOLDER STUFF FOR NOW JUST TESTING THE GITHUB  

