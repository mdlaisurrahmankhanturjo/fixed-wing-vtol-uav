# 🛩 Fixed-Wing VTOL UAV — Design, Simulation & Control

[![DOI](https://img.shields.io/badge/DOI-10.1109/ECCE.2025.11013869-blue)](https://ieeexplore.ieee.org/document/11013869)
![Tools](https://img.shields.io/badge/Tools-SOLIDWORKS%20%7C%20ANSYS%20%7C%20MATLAB%20%7C%20XFLR5-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Last Commit](https://img.shields.io/github/last-commit/mdlaisurrahmankhanturjo/mdlaisurrahmankhanturjo)

![VTOL UAV](https://github.com/mdlaisurrahmankhanturjo/mdlaisurrahmankhanturjo/blob/main/images/vtol_display_image.jpg?raw=true)

## 📖 Overview
This project presents the complete design, simulation, and implementation of a **Fixed-Wing Vertical Take-Off and Landing (VTOL) UAV** with **tilt-rotor and thrust vectoring capabilities**.  
By combining fixed-wing efficiency with VTOL versatility, the aircraft achieves **superior flying qualities** and **novel transition strategies**.

Published as a **peer-reviewed paper at IEEE ECCE 2025** — [Control System Design of a Fixed Wing VTOL UAV](https://ieeexplore.ieee.org/document/11013869) — featuring:
- Optimized aerodynamic design via **CFD simulations** in SOLIDWORKS
- **Thrust vectoring** for enhanced maneuverability
- Fabrication using **3D-printed PLA** and **carbon fiber tubes**
- Integration of a **Speedy Bee F405 fixed-wing flight controller** (STM32 MCU)
- Applications in **surveillance, cargo delivery, and precision agriculture**

---

## 🛠 Skills & Tools
**CAD & Simulation:** SOLIDWORKS, ANSYS Fluent, XFLR5, MATLAB  
**Embedded Systems:** Arduino, STM32, PCB Design  
**Aerospace Engineering:** Aerodynamics, Flight Control, VTOL Transition  
**Project Management:** Research, Documentation, Presentation

---

## 📄 Documentation
- [Thesis Report](https://github.com/mdlaisurrahmankhanturjo/mdlaisurrahmankhanturjo/blob/main/docs/vtol_uav/final_thesis_report.pdf)
- [Presentation Poster](https://github.com/mdlaisurrahmankhanturjo/mdlaisurrahmankhanturjo/blob/main/docs/vtol_uav/poster.pdf)
- [IEEE ECCE 2025 Paper](https://ieeexplore.ieee.org/document/11013869)

---

## 📸 Gallery
![VTOL UAV Flight](https://github.com/mdlaisurrahmankhanturjo/mdlaisurrahmankhanturjo/blob/main/images/vtol_uav_gallery/flight_test.jpg?raw=true)

---

## 🔬 How to Reproduce
1. **Simulation Setup**
   - MATLAB R2023a or later
   - XFLR5 for aerodynamic analysis
   - ANSYS Fluent 2022+ for CFD
2. **CAD Models**
   - Open `.SLDPRT` / `.SLDASM` in SOLIDWORKS 2022+
3. **Firmware**
   - Flash [`code/flight_controller/code.ino`](https://github.com/mdlaisurrahmankhanturjo/mdlaisurrahmankhanturjo/blob/main/code/vtol_uav/code.ino.txt) to Arduino-compatible board
   - For STM32, use `embedded/stm32_code/` with STM32CubeIDE
4. **Flight Testing**
   - Follow safety protocols in [`docs/design_notes.md`](https://github.com/mdlaisurrahmankhanturjo/mdlaisurrahmankhanturjo/blob/main/docs/vtol_uav/design_notes.md)

---

## 🏆 Key Innovations
- Hybrid **fixed-wing + tilt-rotor** design with thrust vectoring
- Aerodynamic surfaces optimized for **low-speed stability** and **efficient cruise**
- Modular fabrication for rapid prototyping
- Control system tuned for **smooth VTOL-to-cruise transitions**

---

## 📚 Cite This Work
If you use this project or reference its methods in your research, please cite:

**Md Laisur Rahman Khan Turjo, et al.**  
"Control System Design of a Fixed Wing VTOL UAV," *2025 IEEE International Conference on Electrical, Computer and Communication Engineering (ECCE)*, Dhaka, Bangladesh, 2025.  
[DOI: 10.1109/ECCE.2025.11013869](https://ieeexplore.ieee.org/document/11013869)

```bibtex
@inproceedings{turjo2025vtol,
  author    = {Md Laisur Rahman Khan Turjo and others},
  title     = {Control System Design of a Fixed Wing VTOL UAV},
  booktitle = {2025 IEEE International Conference on Electrical, Computer and Communication Engineering (ECCE)},
  year      = {2025},
  address   = {Dhaka, Bangladesh},
  doi       = {10.1109/ECCE.2025.11013869}
}
