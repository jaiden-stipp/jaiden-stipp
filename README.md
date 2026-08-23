# Hi, I'm Jaiden Stipp


I build hardware systems

Student at the University of Washington Tacoma graduating Spring 2027

## Featured projects

### [RV32I Core](https://github.com/jaiden-stipp/RV32I)

A custom 32-bit RISC-V processor that grew from a single-cycle core into a 5-stage pipelined CPU and FPGA SoC.

- IF/ID/EX/MEM/WB pipeline with forwarding and load-use hazard detection
- Branch and jump control, unified instruction/data memory, alignment checks, and performance counters
- Directed assembly tests for ALU operations, memory access, branches, jumps, forwarding, hazards, and misaligned accesses
- FPGA SoC integration with on-chip RAM, memory-mapped GPIO, seven-segment debug output, and a bare-metal C flow

**Focus:** SystemVerilog, RISC-V, CPU microarchitecture, pipelining, verification, FPGA SoC design

### [Stigmergy](https://github.com/jaiden-stipp/Stigmergy)

An FPGA ant-colony simulation that visualizes emergent behavior in real time over VGA.

- Parameterized simulation with 64 ants moving through an 80 × 60 world
- Food and home pheromone maps, random wall obstacles, nest/food rendering, and pheromone trails
- Seven-segment output reports food returned to the nest
- Targets the Terasic DE2-115 and Intel Cyclone IV E

**Focus:** SystemVerilog, FPGA design, state machines, memory-mapped display logic, VGA, hardware visualization

### [RTLDeck](https://github.com/jaiden-stipp/RTLDeck)

An offline desktop workspace for learning and developing with Verilog/SystemVerilog.

- Runs genuine Icarus Verilog, Verilator, and Yosys workflows
- Provides VCD waveform inspection, RTL schematics, lint diagnostics, project health checks, and source-to-waveform cross-probing
- Bundles the HDL toolchain for a lower-friction Windows/Linux workflow
- Includes an integration-focused test suite covering simulation, VCD generation, synthesis elaboration, persistence, learning projects, and large-waveform performance

**Focus:** Electron, React, Verilog/SystemVerilog, Icarus Verilog, Verilator, Yosys, VCD, desktop tooling

### [FPGA Car Parking System](https://github.com/jaiden-stipp/Car-Parking)

A 35-space FPGA parking controller that combines finite-state-machine control with real hardware timing.

- Automatic servo gate control with PWM
- Occupancy tracking with full-capacity protection
- Button synchronization/debouncing and timed gate close behavior
- Seven-segment occupancy display, availability LEDs, and near-capacity warning blink

**Focus:** Verilog, FSM design, PWM, debouncing, timing, GPIO, seven-segment displays

## Additional work

- [UART](https://github.com/jaiden-stipp/UART) — transmitter and receiver FSMs 
- [RTL Challenges](https://github.com/jaiden-stipp/RTL-Challenges) — short practice designs
- [Mecanum Wheel Car Project](https://github.com/jaiden-stipp/Mecanum-Wheel-Car-Project) — C++ object-oriented simulator for direction-aware mecanum-drive movement


