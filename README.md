# Buck (Step-Down) Converter PCB Design

## Overview
This repository contains the hardware design files for a switch-mode step-down (buck) DC-DC converter. The project focuses on high-efficiency voltage conversion, low output ripple, and careful layout considerations for switching nodes. Manufacturing (gerber) files are available to make a copy of your own with a PCB fabricator (JLCPCB, PCBWay etc.).

## Features
- 12V DC supply, delivering a 5V stable output.
- Schematic capture and PCB layout created in KiCad.
- Optimized power stage layout to minimize parasitic inductance and EMI.
- Thermal management considerations for switching components.

## Repository Structure
- `/schematic`: KiCad schematic files (.sch / .kicad_sch).
- `/layout`: PCB layout files (.kicad_pcb).
- `/gerber`: Manufacturing outputs and BOM.
