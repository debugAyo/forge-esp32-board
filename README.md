\#forge-esp32-board



A custom, compact ESP32 development board designed in KiCad for Hack Club Forge. 



The goal of this project is to build an everyday prototyping board tailored to breadboard use with built-in USB-C, clean power regulation, and standard 2.54mm header spacing.



\# Hardware Features



\*\*MCU:\*\* ESP32 module (integrated Wi-Fi \& Bluetooth)

\*\*Power \& Data:\*\* USB-C port with 5V to 3.3V LDO regulator

\*\*Controls:\*\* Tactile buttons for hardware Reset (`EN`) and Boot (`GPIO0`)

\*\*Form Factor:\*\* Dual 8-pin headers arranged for direct breadboard mounting

\*\*Design Tool:\*\* KiCad 8 / 9



\## Project Status



\[x] Schematic design \& electrical check

\[x] PCB layout \& component placement

\[ ] Trace routing \& GND copper pours (In Progress)

\[ ] Design Rules Check (DRC) verification

\[ ] Fabrication \& assembly



\## Repository Layout



```text

├── hardware/          # KiCad schematic, board file, and component libraries

├── gerbers/           # Production files for PCB fab (added once routed)

└── README.md

