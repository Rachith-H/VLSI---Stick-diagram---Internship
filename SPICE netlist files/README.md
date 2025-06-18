# SPICE Netlists

This folder contains the **SPICE netlist files** extracted from the corresponding layouts using the `ext2spice` command in **Magic VLSI**. Each file represents a transistor-level circuit description suitable for simulation and functional verification.

These netlists are compatible with **Ngspice**, an open-source SPICE simulator, and have been manually completed with the necessary `.model` definitions where required.

### Circuits Covered:
- Inverter
- NAND (2-input, 3-input)
- NOR (2-input, 3-input)
- AND (2-input, 3-input)
- OR (2-input, 3-input)
- XOR, XNOR
- Half Adder
- 3-Stage Ring Oscillator

### 📌 Notes:
- All netlists were extracted using **SCMOS rules**, intended for educational use only.
- Each `.spice` file can be directly simulated in **Ngspice** to verify the logical behavior of the layout.

> To run a simulation:  
> `ngspice filename.spice`

Make sure the necessary model definitions are included before running the simulation.
