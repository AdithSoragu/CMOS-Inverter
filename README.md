# CMOS Inverter Design and Layout using Cadence Virtuoso

## Overview

This project demonstrates the complete design flow of a CMOS Inverter using Cadence Virtuoso. The project includes schematic design, testbench creation, transient and DC analysis, layout implementation, parasitic extraction, DRC verification, and LVS verification.

The CMOS inverter is one of the most fundamental building blocks in VLSI design and digital integrated circuits. This project was implemented using the GPDK180 technology library in Cadence Virtuoso.

---

# Project Objectives

- Design a CMOS inverter using PMOS and NMOS transistors
- Create the schematic in Cadence Virtuoso
- Perform transient and DC simulations
- Design the physical layout of the inverter
- Verify layout correctness using DRC
- Verify schematic-layout equivalence using LVS
- Perform parasitic extraction

---

# Software and Tools Used

- Cadence Virtuoso
- Cadence ADE L
- Spectre Simulator
- Assura DRC/LVS
- Quantus Extraction Tool

---

# Technology Used

- GPDK180 Technology
- CMOS 180nm Process

---

# CMOS Inverter Introduction

A CMOS inverter is a NOT gate implemented using complementary MOS transistors.

The circuit consists of:
- One PMOS transistor
- One NMOS transistor

### Operation

- When input is LOW:
  - PMOS turns ON
  - NMOS turns OFF
  - Output becomes HIGH

- When input is HIGH:
  - PMOS turns OFF
  - NMOS turns ON
  - Output becomes LOW

Thus, the output is always the inverse of the input.

---

# Schematic Design

The CMOS inverter schematic was designed using:
- PMOS transistor
- NMOS transistor
- Input and output ports
- VDD and GND connections

### Transistor Dimensions

| Transistor | Width | Length |
|------------|-------|--------|
| PMOS | 2u | 180nm |
| NMOS | 2u | 180nm |

---

# Schematic Screenshot

Add your schematic image here:

```text
Screenshots/Schematic.png
```

---

# Testbench Design

A separate testbench was created for simulation purposes.

The testbench includes:
- DC voltage source
- Pulse input source
- Load capacitor
- CMOS inverter symbol

---

# Simulation Performed

## 1. Transient Analysis

Transient simulation verifies the switching operation of the inverter.

### Observation
- Output waveform is complementary to input waveform
- Proper inversion operation achieved

---

## 2. DC Analysis

DC sweep analysis was performed to observe the voltage transfer characteristics.

### Observation
- Output voltage decreases as input voltage increases
- Proper CMOS switching behavior obtained

---

# Waveform Results

The simulation waveforms show:
- Input pulse waveform
- Output inverted waveform
- DC transfer characteristics

---

# Layout Design

The CMOS inverter layout was designed using Cadence Virtuoso Layout XL.

The layout includes:
- PMOS active region
- NMOS active region
- Polysilicon gates
- Metal1 routing
- Contacts and vias
- VDD and GND rails

---

# DRC Verification

Design Rule Check (DRC) was performed using Assura.

### Result

```text
No DRC errors found
```

The layout successfully satisfies all design rules.

---

# LVS Verification

Layout Versus Schematic (LVS) verification was performed.

### LVS Result

```text
Schematic and Layout Match
```

### Verification Summary

- No net mismatches
- No device mismatches
- No pin mismatches
- No parameter mismatches

---

# Truth Table

| Input | Output |
|------|------|
| 0 | 1 |
| 1 | 0 |

---

# Applications

CMOS inverters are widely used in:
- Digital IC Design
- Logic Gates
- Buffer Circuits
- Clock Drivers
- Microprocessors
- CMOS Logic Families
- Memory Circuits

---

# Advantages of CMOS Inverter

- Low power consumption
- High switching speed
- High noise immunity
- Small chip area
- High reliability

---

# Results

The CMOS inverter was successfully:
- Designed using Cadence Virtuoso
- Simulated using Spectre
- Verified using DRC and LVS
- Extracted using Quantus
- Validated through waveform analysis

The layout perfectly matches the schematic and satisfies all design rules.

---

# Learning Outcomes

Through this project, the following concepts were learned:

- CMOS inverter operation
- Cadence Virtuoso schematic design
- Analog and digital simulation
- Layout design methodology
- DRC verification
- LVS verification
- Parasitic extraction
- VLSI physical design flow

---

# Conclusion

This project successfully demonstrates the complete CMOS inverter design flow using Cadence Virtuoso. The schematic, simulation, layout, DRC, LVS, and extraction processes were completed successfully. The inverter shows correct switching behavior and proper layout implementation in 180nm CMOS technology.

---

# Author

Adith Soragu

