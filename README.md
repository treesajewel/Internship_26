# Internship_26
# 8-Bit to 4-Bit Converter using Cadence Virtuoso (MobEx)

## Project Overview

This project implements an **8-Bit to 4-Bit Converter** designed and verified using the **Cadence Virtuoso (MobEx)** VLSI Design Environment. The project demonstrates the complete ASIC physical design flow, beginning from RTL design and simulation through synthesis, floorplanning, placement, clock tree synthesis, routing, and final signoff.

The objective of this project is to convert 8-bit input data into a 4-bit output while following a standard VLSI implementation methodology. The design has been functionally verified using Verilog testbenches and implemented through the Cadence physical design flow.

---

## Objectives

- Design an efficient 8-Bit to 4-Bit Converter.
- Verify the RTL functionality using Verilog simulation.
- Perform synthesis using the Cadence design flow.
- Complete the physical implementation using Cadence Virtuoso (MobEx).
- Analyze timing, routing, and final implementation results.

---

## Tools Used

- **Cadence Virtuoso (MobEx)**
- **Verilog HDL**
- **Git**
- **GitHub**

---

## Project Flow

The project follows the standard ASIC implementation flow:

1. RTL Design
2. Functional Simulation
3. Logic Synthesis
4. Floorplanning
5. Power Planning
6. Placement
7. Clock Tree Synthesis (CTS)
8. Routing
9. Signoff

---

## Working Principle

The converter accepts an **8-bit input** and processes it to produce a **4-bit output** according to the implemented conversion logic. The design was first verified at the RTL level using Verilog simulation before being synthesized and physically implemented using the Cadence Virtuoso (MobEx) environment.

---

## Repository Structure

```
Internship_26/
│
└── 8 bit to 4 bit converter/
    │
    ├── Synthesis/
    ├── Floorplanning/
    ├── Powerplan/
    ├── Placement/
    ├── Clock Tree Synthesis/
    ├── Routing/
    ├── Signoff/
    ├── Simulation/
    ├── verilog.v
    ├── testbench.v
    └── README.md
```

---

## Folder Description

| Folder/File | Description |
|-------------|-------------|
| **Simulation** | RTL simulation results and waveform screenshots |
| **Synthesis** | Logic synthesis reports and generated netlists |
| **Floorplanning** | Core layout, die planning, and floorplan screenshots |
| **Powerplan** | Power ring and power distribution implementation |
| **Placement** | Standard cell placement results |
| **Clock Tree Synthesis** | Clock network generation and CTS reports |
| **Routing** | Global and detailed routing implementation |
| **Signoff** | Final timing verification and implementation reports |
| **verilog.v** | Verilog source code |
| **testbench.v** | Verilog testbench used for functional verification |

---

## Features

- Designed using **Cadence Virtuoso (MobEx)**
- Verilog HDL implementation
- Functional simulation
- Complete ASIC physical design flow
- Timing-aware implementation
- Organized project documentation

---

## Applications

- Digital communication systems
- FPGA and ASIC design learning
- Data width conversion
- Embedded systems
- Digital electronics
- VLSI design education

---

## Verification

The functionality of the design was verified through Verilog simulation using the provided testbench before proceeding to synthesis and physical implementation.

---

## Results

- RTL simulation completed successfully.
- Logic synthesis completed successfully.
- Floorplanning and power planning implemented.
- Standard cell placement completed.
- Clock Tree Synthesis (CTS) completed.
- Routing completed successfully.
- Signoff verification completed.

---


## Future Scope

- Support configurable input and output widths.
- Optimize power consumption.
- Improve timing performance.
- Increase design scalability.
- Extend the design for larger digital systems.

---

## Author

**Treesa Jewel**

---

## License

This project is developed for educational and internship purposes.
