# DC/DC Buck Converter — Altium Design

A custom DC/DC buck converter designed end-to-end in Altium Designer:
schematic capture, PCB physical layout, bill of materials, and a
compensation network sized to meet specified efficiency and operational
targets.

**Designer:** Hadassah Faur

---

## Overview

A buck converter steps a higher input voltage down to a lower, regulated
output by switching a power transistor at high frequency and filtering the
result through an LC network. The compensation network shapes the control
loop's frequency response to keep the regulator stable across operating
conditions while still responding quickly to load changes.

This project covers the full design flow: component selection from
real-world performance constraints, schematic capture, PCB layout, and BOM
generation for fabrication.

## Design Deliverables

- **Schematic** — Full converter topology including power stage, feedback
  network, and compensation network
- **PCB layout** — Physical board design with attention to power-stage
  layout, return paths, and component placement
- **Bill of Materials (BOM)** — Component selection with part numbers
- **Compensation network design** — Frequency-domain shaping of the control
  loop for stability and transient response

## Tools

- **Altium Designer** — Schematic capture and PCB layout

## Skills Demonstrated

- Power-electronics design (buck topology)
- Component selection against efficiency and performance targets
- Control-loop compensation
- PCB physical design and layout
- BOM generation and design documentation
