# Digital-Design-through-Verilog-HDL
# Digital Design through Verilog HDL

A structured collection of Verilog codes and testbenches, organized chapter-wise like a textbook.  
This repository is designed for students, learners, and engineers to practice and understand **Digital Design concepts through Verilog HDL**.

---

## 📚 Chapters

1. [Number Systems](./01_Number_Systems)
2. [Boolean Algebra](./02_Boolean_Algebra)
3. [Logic Gates](./03_Logic_Gates)
4. [Combinational Circuits](./04_Combinational_Circuits)
5. [Sequential Circuits](./05_Sequential_Circuits)  
   - Latches  
   - Flip-Flops  
   - Counters  
   - Registers  
   - FSM (Moore / Mealy)  

---

## ▶️ Running the Code

You can simulate using **Icarus Verilog** and view waveforms in **GTKWave**.

```bash
# Compile
iverilog design.v tb_design.v -o design.out

# Run
vvp design.out

# View waveform (if VCD enabled in testbench)
gtkwave dump.vcd
