---
layout: page
title: BCHDecoderVHDL
description: 🧮 BCH decoder FPGA design
full_name: mpek29/BCHDecoderVHDL
img: assets/img/projects/BCHDecoderVHDL/main.png
importance: 1
git: https://github.com/mpek29/BCHDecoderVHDL
github: https://github.com/mpek29/BCHDecoderVHDL
category: Other
subcategory: General
---


**BCHDecoderVHDL** is an open-source project aimed at designing a **BCH error-correcting decoder in VHDL**, built for **FPGA implementation using an Avalon interface**. This hardware module is integrated into a **SoC system based on an Intel Cyclone V** and deployed on a **DE0-CV development board running at 25 MHz**.

## 🎯 Purpose  

- 🧮 **Error Correction**: Implements BCH decoding for binary data error detection and correction.  
- 🔗 **Avalon Interface Compatibility**: Designed to connect seamlessly to Avalon-compliant systems.  
- 🧩 **Quartus Integration**: Ready for integration into Intel Quartus projects targeting DE0-CV boards.  
- 🧠 **CPU Exploitation**: Enables communication with a Nios II or other Avalon master for data exchange.  

## 📝 Features  

| 🏷️ Feature | 🔍 Description |
|-----------|----------------|
| 🧮 **BCH Decoder** | Implements syndrome calculation, Berlekamp-Massey algorithm, Chien Search |
| 🔗 **Avalon Interface** | Supports Avalon-MM or Avalon-ST as needed |
| ⚙️ **VHDL Design** | Modular, synthesizable VHDL code |
| 🧠 **CPU-Controlled** | Controlled by an Avalon master processor |
| 🧪 **VHDL Testbench** | Comes with a simulation testbench for functional validation |
| 🧱 **DE0-CV Ready** | Optimized for 25 MHz operation on DE0-CV |
| 🖥️ **Quartus Project** | Integrated via Qsys / Platform Designer |
| 📦 **Open-source** | Fully modifiable and extensible HDL source code |

## 📐 Design Architecture Preview  

| 🔧 Decoder Core | 🔗 Avalon Interface | 🖥️ Quartus System |
|------------------|----------------------|--------------------|
| {% include image.html path="assets/img/projects/BCHDecoderVHDL/bch_core.png" width="100%" %} | {% include image.html path="assets/img/projects/BCHDecoderVHDL/avalon_iface.png" width="100%" %} | {% include image.html path="assets/img/projects/BCHDecoderVHDL/qsys_layout.png" width="100%" %} |

## 🗂️ Project Structure

```bash
BCHDecoderVHDL/
├── src/ # VHDL source files (core, control, interface)
├── sim/ # VHDL testbenches
├── qsys/ # Qsys/Platform Designer files
├── quartus_project/ # Quartus project targeting DE0-CV
├── sw/ # Nios II C code
└── assets/img/ # Documentation images
```

## 📦 Use Cases

- ✅ Embedded communication systems
- ✅ FPGA-based secure data transmission
- ✅ Educational demonstration of error-correcting codes

