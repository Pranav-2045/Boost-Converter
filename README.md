# DC-DC Boost Converter

This repository contains the design files, PCB layout, and testing results for a custom-built DC-DC boost converter.

## Project Overview

This project involved the complete lifecycle of a DC-DC boost converter, from initial design calculations and component selection to PCB fabrication and final testing. The goal was to create an efficient and reliable circuit capable of stepping up a lower DC input voltage to a higher, regulated DC output voltage.

---

## Features

* **Custom PCB Design:** All circuit components are integrated onto a professionally designed and fabricated printed circuit board.
* **Boost Conversion:** Efficiently converts a lower DC input voltage to a higher DC output voltage.
* **Regulated Output:** Provides a stable output voltage under varying load conditions.
* **Compact Footprint:** PCB is small and optimized for small space
---

## Design and Implementation

### Schematic Design

The circuit schematic was designed using EasyEDA. It features a mosfet,diode,gate driver with IC (TL494), an inductor, output capacitors, and load resistors"].

### PCB Layout

The PCB was laid out with careful consideration for signal integrity, power traces, and thermal management. Key design choices included:

* **Optimized Power Paths:** Wide traces for high current paths to minimize voltage drop and heat generation.
* **Component Placement:** Strategic placement of components to reduce EMI and improve efficiency.
* **Ground Planes:** Solid ground planes for improved signal integrity and thermal dissipation.

### Component Selection

Components were chosen based on their electrical characteristics, availability, and cost-effectiveness. Particular attention was paid to the selection of the boost controller IC, inductor, and low ESR capacitors for optimal performance.

---

## Testing and Results

The fabricated PCB was thoroughly tested to validate its performance against the design specifications.

### Test Setup

* **Input Power Supply:**  "Bench power supply"
* **Load:**  "Resistor bank"
* **Measurement Equipment:** Digital Multimeter (DMM), Oscilloscope

### Performance Validation

Testing involved:

* **Voltage Regulation:** Measuring the output voltage stability under varying input voltages and load conditions.
* **Efficiency Measurement:** Calculating the conversion efficiency at different load points.
* **Thermal Performance:** Monitoring component temperatures during operation.



