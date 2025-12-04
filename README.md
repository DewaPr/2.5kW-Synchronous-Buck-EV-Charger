# 2.5kW-Synchronous-Buck-EV-Charger

This repository contains the complete design files for a 2.5kW onboard battery charger for electric vehicles. The design features a two-stage approach with an active Power Factor Correction (PFC) front-end and a DC-DC converter back-end.

![EV Charger PCB Image](placeholder.png)
*(To Be Added, Please check https://www.linkedin.com/in/dewapramudya/ -> Project for updated image)*

---

## Key Features
* **Power Rating:** 2.5 kW Max Output
* **Input Voltage:** 85-265V AC (Universal Input)
* **Output Voltage:** 250VDC, suitable for 70S LiFePO4
* **Output Current:** 1-10A
* **Control Strategy:** Two-stage conversion:
    1.  **AC-DC:** Active Power Factor Correction (PFC) using a Boost Topology.
    2.  **DC-DC:** Synchronous Buck Converter for current and voltage regulation.
* **Efficiency:** 92% peak efficiency.
* **Safety:** Includes protections for over-voltage, over-current, and over-temperature.

## Hardware
The hardware is designed for high power density and thermal performance.

* **PFC Stage:** High-frequency boost converter using High Voltage Mosfets.
* **DC-DC Stage:** **High-frequency Synchronous Buck Converter** to step down the high voltage from the PFC bus. It uses **MOSFETs in a synchronous configuration** to minimize losses.
* **Magnetics:** Custom-designed transformer and inductors for the specified power and frequency.

All hardware design files (schematics, PCB layout) are in the `/hardware` directory.

## Demonstration
more image and testing on my LinkedIn: [dewapramudya](https://linkedin.com/in/dewapramudya)

## Project Status: Complete
---
*Created by [Your Name], [Year]*
