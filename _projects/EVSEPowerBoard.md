---
layout: page
title: EVSEPowerBoard
description: No description available
full_name: mpek29/EVSEPowerBoard
img: assets/img/projects/EVSEPowerBoard/main.png
importance: 1
git: https://github.com/mpek29/EVSEPowerBoard
github: https://github.com/mpek29/EVSEPowerBoard
category: Other
subcategory: General
---


The **EVSEPowerBoard** is a **three-phase AC power board** for **EV charging stations** delivering up to **22 kW**.  
It handles the **power switching, measurement, and safety logic** according to **IEC 61851-1 / SAE J1772** standards.  
Designed for integration with a high-level controller such as the **EVSEControlBoard**, it provides a complete open-source hardware platform for AC charging.

## 🎯 Purpose

- 🔋 **Power Management**: Controls and monitors power delivery up to 22 kW.  
- ⚙️ **Safety & Protection**: Integrated GFCI, relay monitoring, and over-current detection.  
- 📡 **Signal Interface**: Generates and reads Control Pilot (CP) and proximity signals.  
- 🧠 **Microcontroller-Based**: Embedded STM32 for real-time logic and communication.  
- 🔌 **Flexible Integration**: Works standalone or as part of a smart charger system.

## 📝 Features

| 🏷️ Feature | 🔍 Description |
|-------------|----------------|
| ⚡ **Three-Phase Power Switching** | 35 A relay with mirror contacts and PWM coil control |
| 🧮 **Integrated Power Metering** | Shunt-based voltage, current, and energy measurement on all phases |
| ⚠️ **Ground Fault Detection** | GFCI for 5/6 mA DC and 20/30 mA AC faults |
| 🔄 **Control Pilot Generation** | IEC 61851-1 / SAE J1772 compliant |
| 📶 **Zero-Cross Output** | TTL signal synchronized to L1 for PLC modem |
| 🧰 **Communication Interfaces** | UART, RS485/ModBus, GPIO, SPI LCD connector |
| 💾 **FRAM Storage** | Non-volatile energy and status data |
| 🔋 **Power Supply** | 110/230 V AC → 12 V DC onboard or external input |
| 🧩 **Programming Port** | TagConnect TC2030 for STM32 debug and firmware upload |
| 🧱 **Reinforced Isolation** | 4 kV barrier meeting IEC 61851-1 creepage and clearance rules |

## 📐 PCB Design Preview

| 📜 Schematic | 🖥️ PCB Layout | 🏗️ 3D |
|-----------|-----------|-----------|
| {% include image.html path="assets/img/projects/EVSEPowerBoard/schematic.png" width="100%" %} | {% include image.html path="assets/img/projects/EVSEPowerBoard/pcb_layout.png" width="100%" %} | {% include image.html path="assets/img/projects/EVSEPowerBoard/3d.png" width="100%" %} |

