# Internship on VLSI Stick Diagrams & Layout Simulation

This repository contains all the work carried out during a self-learning internship focused on understanding the basics of **VLSI design using stick diagrams, layout implementation, and SPICE simulation**.

### 📘 About the Internship
The internship aimed to develop hands-on skills in custom layout design using open-source tools. It involved learning the concept of **stick diagrams**, translating them into transistor-level **layouts using Magic VLSI**, extracting **SPICE netlists**, and verifying circuit behavior using **Ngspice** simulations. The design flow followed **SCMOS rules** and was carried out in a **Linux (Ubuntu)** environment.

---

### 📂 Repository Structure
VLSI-Stick-Diagram-Layout-Internship
1. Extracted circuit files   - Intermediate .ext files from Magic extraction
2. Layouts                   - Layout screenshots
3. Layouts gridview          - Layout screenshots with grid enabled
4.  Magic circuit files      - Layout files saved in Magic
5. Ngspice outputs           - Output waveform images from Ngspice
6. Rendered layouts          - Rendered layout images (clean presentation)
7. Spice netlists            - Extracted .spice files for Ngspice simulation
8. Stick_diagrams            - Stick diagrams of all logic circuits
9. README.md                 - Main README file (this file)


---

### ✅ Circuits Covered
- Inverter  
- NAND (2-input, 3-input)  
- NOR (2-input, 3-input)  
- AND (2-input, 3-input)  
- OR (2-input, 3-input)  
- XOR, XNOR  
- Half Adder  
- 3-Stage Ring Oscillator  

---

### 🛠️ Tools Used
- Magic VLSI – For custom layout design  
- Ngspice – For SPICE-level simulation  
- SCMOS technology – For educational layout rules  
- Ubuntu Linux – Development environment  

---

### 📎 Notes
- The designs are **not intended for fabrication** and were developed solely for learning purposes.
- `.spice` files include manually added `.model` definitions and plotting parameters which where required for simulation compatibility.

---

### 📄 Report
The corresponding LaTeX report summarizes the entire workflow, including diagrams, layouts, simulation results, and methodology.  

[Internship Report](https://drive.google.com/file/d/1XE4tXopADcODvvVmT1WFogu72GVF1bqg/view?usp=drivesdk)


