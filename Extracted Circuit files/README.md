#  Extracted Circuit Files (`.ext`)

This folder contains the **intermediate `.ext` files** generated using the `extract all` command in **Magic VLSI**. These files represent the extracted circuit-level information from the physical layouts, including devices, connectivity, nodes, and ports.

### Purpose:
The `.ext` files act as a bridge between layout design and SPICE simulation. They capture the electrical structure of the circuit and are used by Magic’s `ext2spice` tool to generate SPICE-compatible netlists.

### Circuits Included:
- Inverter
- NAND (2-input, 3-input)
- NOR (2-input, 3-input)
- AND (2-input, 3-input)
- OR (2-input, 3-input)
- XOR, XNOR
- Half Adder
- 3-Stage Ring Oscillator

### ⚙️ Tools Used:
- **Magic VLSI** for layout and extraction  
- **SCMOS technology** (for learning purposes only)

> These files are not directly used for simulation but are an essential step in the layout-to-SPICE workflow.

