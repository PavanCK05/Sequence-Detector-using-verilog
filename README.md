# Sequence-Detector-using-verilog

## 📌 Project Overview
This project focuses on designing and implementing a **Sequence Detector** using **Verilog HDL**.  
A sequence detector is a digital circuit that monitors a binary input stream and generates an output when a **predefined sequence of bits** (e.g., `1010`) is detected.

The system is designed using **Finite State Machines (FSMs)**, with both **Moore** and **Mealy** machine models implemented. The project includes **Verilog modules and testbenches**, simulated using tools such as **ModelSim/Vivado**.

---

## ✨ Features
- Detects predefined sequences in an input bitstream.  
- Implements both **Moore** and **Mealy** FSM-based designs.  
- Includes **testbenches** for verification.  
- Demonstrates **overlapping and non-overlapping** sequence detection.  
- Modular and efficient design for FPGA/ASIC deployment.  

---

## 🛠️ Methodology
1. **Finite State Machine Design**  
   - States defined for partial sequence progress.  
   - Transitions mapped based on input bits.  
   - Output generated on successful detection.  

2. **Verilog Implementation**  
   - Modules written in Verilog for FSM logic.  
   - Clock-driven synchronous design with reset handling.  

3. **Simulation & Testing**  
   - Testbenches simulate input streams.  
   - Waveforms analyzed to confirm correct detection.  

---

## 📊 Results
- Successfully detects sequences like `1010` in **real-time input streams**.  
- Both **Moore** and **Mealy** designs validated through simulation.  
- Demonstrated **accuracy, efficiency, and low latency**.  

---

## 💡 Applications
- **Digital Communication Systems** – detecting start/end markers, error detection.  
- **Protocol Verification** – checking UART, SPI, or I2C sequences.  
- **Pattern Recognition** – identifying binary patterns in sensor/embedded data.  
- **Control Systems** – triggering events based on input sequences.  

---

## 📌 Conclusion
This project successfully demonstrates how **Verilog HDL** can be used to implement **sequence detectors** using FSMs. The design is modular, efficient, and highly adaptable for various **digital logic and embedded applications**.  

---

## 🚀 Future Work
- Extend design to support **user-configurable sequences**.  
- Implement **parameterized FSMs** for different sequence lengths.  
- Deploy on FPGA boards for hardware validation.  
- Explore **low-power optimized designs**.  

---

## 👩‍💻 Author
**PAVAN C K**  
Department of Electronics and Telecommunication  
Dr. Ambedkar Institute of Technology, Bengaluru, India  

---
