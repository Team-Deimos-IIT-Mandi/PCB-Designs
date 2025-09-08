# R&D Team PCB Designs

![R&D Team](https://img.shields.io/badge/R&D-Team-purple?style=for-the-badge)
![Innovation](https://img.shields.io/badge/Innovation-First-blue?style=for-the-badge)

## 🔬 Mission Statement
Research and develop fully custom, efficient, and compact PCB solutions for advanced robotic systems.

## 🖼️ Design Gallery

<div align="center">

### Power Distribution Network - 3D View
![PDN 3D View](Power%20Distribution/3D_PCB1_2025-08-20.png)

### Schematic Overview
![PDN Schematic](Power%20Distribution/SCH_Schematic1_1-P1_2025-08-20.png)

### Integrated Drive PCB
![Integrated Drive PCB schematic](ESP32%20Custom%20Boards/ESP32-schematic.jpg)
*Integrated PCB for drive with CAN*

</div>

## 🚀 Current Projects

### 1. Power Distribution Network (PDN)
**Status**: ✅ Completed Design Phase

Custom Power Distribution PCB designed for robust power management in robotic systems.

#### Features:
- **Input**: 24V DC input with XT90 connector
- **Output**: 5V regulated output via buck converter
- **Protection**: 
  - Reverse polarity protection
  - Surge protection circuitry
  - 60A fuse protection
- **Additional**: EMI filters for clean power delivery

#### Files:
- `PCB_PCB1_2025-08-20.pdf` - PCB layout documentation
- `3D_PCB1_2025-08-20.png` - 3D visualization
- `SCH_Schematic1_1-P1_2025-08-20.png` - Schematic diagram

### 2. Custom ESP32 Development Board
**Status**: 🔄 In Development

Creating a specialized ESP32 development board optimized for robotic applications with minimal external wiring.

#### Features:
- **Core**: ESP32-WROOM-32 module
- **Connectivity**: 
  - Onboard CAN bus headers (SN65HVD230)
  - Motor driver connection headers
- **Sensors**: Integrated current sensing capability
- **Design Goal**: Reduce wiring complexity in robotic systems

#### Target Applications:
- Rover control systems
- Motor control nodes
- Sensor data acquisition
- Wireless communication hubs

## 📋 Design Guidelines

### PCB Design Standards:
- **Layer Count**: Minimum 4-layer for complex designs
- **Trace Width**: Follow IPC standards
- **Via Size**: 0.2mm minimum drill, 0.4mm pad
- **Component Selection**: Prefer automotive/industrial grade components

### Documentation Requirements:
- Complete schematic with proper annotations
- 3D PCB visualization
- Assembly drawings
- BOM with supplier information
- Design review checklist

## 🛠️ Tools & Software

- **Primary**: KiCad 7.x
- **Secondary**: Altium Designer (for complex designs)
- **3D Modeling**: KiCad 3D Viewer, FreeCAD
- **Simulation**: LTSpice, KiCad Spice

## 📈 Future Roadmap

### Q4 2025 Goals:
- [ ] Complete ESP32 custom board prototyping
- [ ] PDN testing and validation
- [ ] Motor driver integration board
- [ ] Sensor fusion PCB development

### 2026 Vision:
- Develop modular PCB ecosystem
- Implement advanced power management
- Create standardized connector systems
- Establish automated testing protocols

## 🔍 Testing Protocols

All designs undergo rigorous testing phases:
1. **Design Rule Check (DRC)**
2. **Electrical Rule Check (ERC)**
3. **Thermal simulation**
4. **EMI/EMC pre-compliance testing**
5. **Prototype validation**

## 📞 R&D Team Contact

For technical discussions, design reviews, or collaboration opportunities, please reach out to the R&D team leads.

---

*R&D Team - Team Deimos IIT Mandi*  
*Last Updated: September 2025*
