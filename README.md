
# 8-bit Up/Down Counter with Synchronous Reset and Load (VHDL - Xilinx ISE 8.1)

This project demonstrates the design and simulation of an 8-bit Up/Down Counter with synchronous reset and load functionality using VHDL in Xilinx ISE 8.1.

![Screenshot 2025-06-13 124028](https://github.com/user-attachments/assets/277b6176-ce72-4fda-9bbf-750b1ff8cbdd)

## 🛠️ Project Features
- 8-bit Counter (`count[7:0]`)
- Synchronous Reset
- Synchronous Load
- Up/Down Counting Control (`up_down`)
- Testbench simulation with waveform analysis

---

## 📁 Files Included
- `up_down_counter_SyncRst.vhd` – Main VHDL code for the counter
- `tb_up_down_counter.vhd` – Testbench file for simulation
- `RTL_Schematic.png` – RTL view from ISE
- `Technology_Map.png` – Implemented schematic diagram
- `Simulation_Waveform.png` – Functional simulation waveform
- `Fitter_Report.txt` – Resource utilization summary
- `Timing_Report.txt` – Clock-to-output and path delay information

---

## 📷 Key Outputs

### ✅ RTL Schematic
Visual structure of the VHDL module, automatically generated by ISE.
![Screenshot 2025-06-13 124127](https://github.com/user-attachments/assets/537b2292-2d3b-46c3-8ea1-d458df389d5e)

### ✅ Implemented Schematic
Post-implementation logic view showing gate-level mapping.
![Screenshot 2025-06-13 124230](https://github.com/user-attachments/assets/161beabc-8fa3-4e22-9482-79a4ba55aee7)

### ✅ Simulation Waveform
Testbench-driven waveform showing:
- Synchronous reset
- Load operation
- Up and down counting sequences
![Screenshot 2025-06-13 132655](https://github.com/user-attachments/assets/be6a980a-66bc-4c8b-aa06-af5f08426ad8)
---

## 📊 Fitter Report Summary (Xilinx ISE)
- Slices used: 16 out of 960
- 4-input LUTs: 28 used
- IOBs: 18 used
- Design meets the resource constraints for Spartan-3/Artix-7 family
![Screenshot 2025-06-13 123741](https://github.com/user-attachments/assets/e54ee8fd-a84b-476c-adc6-88fe90bf5544)
---

## ⏱ Timing Report Highlights
- Minimum period: 6.755 ns (≈148 MHz)
- Clock-to-output delay: 6.291 ns
- Slack: Positive (timing met)
![Screenshot 2025-06-13 124826](https://github.com/user-attachments/assets/12b3d7f5-b593-4376-8915-d895e135e0ce)
---

## ▶️ How to Simulate
1. Open Xilinx ISE 8.1.
2. Add both `.vhd` files to a new project.
3. Set `tb_up_down_counter.vhd` as the top module for simulation.
4. Run Behavioral Simulation.
5. Observe the waveform and verify logic behavior.

---

## 📌 Tools Used
- **Xilinx ISE 8.1**
- **VHDL**
- **ISE Simulator**

---

## 👨‍💻 Author
Developed by **Sandeep Kumar** – Final Year ECE Student | VLSI Enthusiast

📩 Email: [sandycndy@outlook.com](mailto:sandycndy@outlook.com)  
🔗 LinkedIn: [linkedin.com/in/sandycndy](https://www.linkedin.com/in/sandeepkumar2612/)

---

## 📎 License
This project is open-source and available for educational and non-commercial use.
```

