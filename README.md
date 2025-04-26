# EEE3088F_PCB_Project_PTXNYA001_MNGAMO004
This repository details the progress of a Micromouse Power Board which was assigned by the EEE3088F teaching staff of the University of Cape Town. This project was completed in collaboration between Nyakallo Peete and Amos Manganye.
# Micro-Mouse Power Subsystem

![Made with KiCad](https://img.shields.io/badge/Made%20with-KiCad-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## Overview

This repository contains the design files, schematics, and documentation for the **Power Subsystem** of the 2025 Micro-Mouse Project, developed as part of the EEE3088F course.

The Power Subsystem is responsible for:
- Accepting 9V input from a USB-C Power Delivery (PD) source.
- Charging a 3.7V 800mAh LiPo battery with selectable charging modes.
- Supplying regulated 3.3V and 5V outputs to system modules and motors.
- Controlling system power states through a low-leakage ON/OFF switch.
- Monitoring battery voltage and current via an I²C bus.
- Driving four motors (primary and auxiliary) for micro-mouse navigation.

---

## Features

- Provides regulated 5V and 3.3V outputs to supply all system modules, including processors, sensors, and external loads.
- Powers four motors (bidirectionally) via integrated motor driver outputs for primary and auxiliary drive control.
- Supports charging of a 3.7V 800mAh LiPo battery from a 9V USB-C input.
- Offers two selectable battery charging modes: low current mode (for extended battery life) and high current mode (for faster charging).
- Includes an ON/OFF control system that completely disables power rails when not in use, reducing standby current to less than 30μA.
- Enables real-time battery voltage and current monitoring through an I²C interface for improved system diagnostics and safety.
- Provides jumper-based power isolation and multiple test points throughout the system to simplify testing, debugging, and future upgrades.
- Designed for compact size, robustness, low cost, and manufacturability using JLCPCB basic part components.

---

## Tools Used

- KiCad 9.0 for schematic and PCB layout
- EasyEDA for footprints
- GitHub for version control and project documentation
- JLCBPB for manufacturing

---

## Authors

- **Amos Manganye**
- **Nyakallo Peete**

---

## Acknowledgements

- University of Cape Town (UCT) — Department of Electrical Engineering
- EEE3088F Teaching Staff

---

