# Ngspice Simulation Outputs

This folder contains the simulation output waveforms generated using **Ngspice** for the CMOS logic circuits designed in Magic VLSI.

Each simulation verifies the logical functionality of the layout by using the corresponding `.spice` netlist (extracted via `ext2spice` command from Magic). Missing model definitions and plotting parameters were manually added to the SPICE files to enable proper simulation.

### Contents:
- Waveform images for:
  - Inverter
  - NAND (2-input, 3-input)
  - NOR (2-input, 3-input)
  - AND (2-input, 3-input)
  - OR (2-input, 3-input)
  - XOR, XNOR
  - Half Adder
  - 3-Stage Ring Oscillator

All simulations were run in a **Linux environment (Ubuntu)** using **Ngspice**, and the outputs confirm the expected behavior of each digital circuit.

> Note: The SCMOS model was used for educational purposes and may not reflect fabrication-ready characteristics.
