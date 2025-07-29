# 🚀 Dynamic Motion Sensing System – Project Work

**Author:** Yashodhan Vishvesh Deshpande  
**Degree:** B.Eng. in Electronics Engineering  
**Institution:** Hochschule Hamm-Lippstadt, Germany  
**Supervisor:** Prof. Dr.-Ing. Ali Hayek  
**Completion Date:** 25 August 2024  

---

## 📘 Project Overview

This project implements a real-time **Dynamic Motion Sensing System** using FPGA-based hardware and embedded software. It integrates a 3-axis accelerometer with a MicroBlaze soft-core processor and communicates results via Bluetooth and an OLED RGB display.

The project was developed using the **Xilinx Vivado 2023.1** and **Vitis Unified Software Platform**, targeting the **Digilent Nexys A7-100T** development board.

---

## 🔍 Objectives

- Design a motion sensing embedded system using Pmod modules  
- Interface sensors (Pmod ACL) and actuators (OLED RGB, BLE) via SPI/UART  
- Implement custom logic on MicroBlaze soft processor  
- Transmit real-time sensor data to OLED and Bluetooth terminal  
- Analyze FPGA resource usage, power, and timing performance  

---

## 🧩 System Architecture

**Inputs:**  
- 📟 Pmod ACL – 3-axis Accelerometer (SPI)

**Processing Node:**  
- 🧠 Nexys A7-100T FPGA Board with MicroBlaze processor

**Outputs:**  
- 🖥️ Pmod OLED RGB Display (SPI)  
- 📶 Pmod BLE Bluetooth Module (UART)

**Software Stack:**  
- HDL: Vivado block design using IP integrator  
- Firmware: C-based logic using Vitis SDK  
- Communication: SPI (OLED, ACL), UART (BLE)

---

## 🗂️ Repository Structure
.
├── helloworld.c # Main C source code for Vitis
├── Final_vitis_code.txt # Code summary in text format
├── ip.zip # IP cores for Vivado block design
├── Yashodhan_Vishvesh_Deshpande_ProjectWork_Documentation_2024.pdf
├── Yashodhan_Vishvesh_Deshpande_ProjectWork_Presentation_2024.pdf
└── Yashodhan_Vishvesh_Deshpande_ProjectWork_Presentation_2024.pptx
