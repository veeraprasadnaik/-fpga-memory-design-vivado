 # 📁 Repository Name

**vivado-ram-rom-design**

---

# 📖 README

## 🧠 Overview

This repository contains the complete design, implementation, and verification of **RAM (Random Access Memory)** and **ROM (Read Only Memory)** using **Xilinx Vivado**. The project demonstrates how memory components are modeled in **Verilog HDL**, simulated, synthesized, and implemented on FPGA hardware.

---

## 🎯 Objectives

* Design and implement RAM and ROM modules using Verilog
* Perform functional simulation to verify correctness
* Synthesize the design using Vivado
* Implement the design on FPGA
* Analyze timing and resource utilization

---

## 🛠️ Tools & Technologies

* Xilinx Vivado Design Suite
* Verilog HDL
* FPGA (Basys / Artix-7 or similar boards)

---

## 📂 Project Structure

```
vivado-ram-rom-design/
│── src/
│   ├── ram.v
│   ├── rom.v
│── sim/
│   ├── ram_tb.v
│   ├── rom_tb.v
│── constraints/
│   ├── design.xdc
│── docs/
│   ├── screenshots/
│── README.md
```

---

## ⚙️ Implementation Steps

### 1. Design Entry

* Created RAM and ROM modules using Verilog HDL
* Defined inputs, outputs, and memory behavior

### 2. Simulation

* Developed testbenches for RAM and ROM
* Verified read/write operations using waveform analysis

### 3. Synthesis

* Converted HDL code into gate-level netlist
* Checked synthesis reports for logic utilization

### 4. Implementation

* Performed placement and routing
* Generated bitstream file

### 5. Hardware Testing

* Programmed FPGA using Vivado
* Verified functionality on hardware

---

## 🧩 Features

* Parameterized RAM design
* ROM initialized with predefined data
* Separate testbenches for validation
* Fully synthesizable code

---

## 📊 Results

* Successful simulation and waveform verification
* Efficient resource utilization
* Correct read/write operations observed in RAM
* Accurate data retrieval in ROM

---

## 📌 Applications

* Embedded systems
* FPGA-based memory design
* Digital system design learning

---

## 👤 Author

**K Veera Prasad Naik**

---

## 📜 Description

This project demonstrates the complete workflow of designing RAM and ROM in Vivado, including coding, simulation, synthesis, implementation, and hardware verification. It is intended for students and beginners in FPGA and digital design to understand memory design concepts practically.

---

## ⭐ Contribution

Feel free to fork this repository, improve the design, or add new memory architectures.

---
