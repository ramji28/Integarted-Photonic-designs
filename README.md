# Integrated Photonic Design Portfolio

This repository contains Jupyter notebooks showcasing my work in **integrated photonics design**.

Please visit my website www.rpraksh.com for interactive post with explanation

## Contents
## 🧩 Passive Components

These are the basic on-chip elements for routing and manipulating light.

- **Directional Coupler** – Design and simulation of a compact Si directional coupler.
- **Y-Branch Splitter** – Power splitting using adiabatic Y-junctions.
- **Ring Resonator** – Resonant filtering and wavelength-selective behavior.
- **Bragg Grating** – Wavelength reflection and filtering with periodic structures.
- **Mach–Zehnder Interferometer (MZI)** – Phase-controlled interferometric filter (Circuit modeling using SAX).

---

## 💡 Optical I/O Components

Coupling light between the chip and the outside world.

- **Grating Coupler** – Vertical coupling of light using surface gratings.
- **Edge Coupler** – Efficient fiber-to-chip coupling at the facet.

---

## ⚙️ Active Components

These devices allow **dynamic control** of light using electrical, thermal, or phase-change mechanisms.

- **Thermo-Optic MZI Phase Shifter**– Tunable phase control using local heating.
- **Ring Resonator Phase-Change Switch** – Non-volatile optical switching using GST layers.
- [**Photodetector**] – On-chip detection using Ge or Si-based absorption.

Each of these components explores both **device-level simulations** (using MEEP) and **compact modeling** for system integration.

---

## 🔁 Photonic Circuit Modeling

At the circuit level, I use **SAX** and **GDSFactory’s netlist tools** to assemble and simulate multi-component photonic circuits.

- **MZI Circuit Simulation** – Example of a interferometric system modeled using SAX.
- **Thermo-Optic MZI Phase Shifter** – Tunable phase control using local heating using SAX.
