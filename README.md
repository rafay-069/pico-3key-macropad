# pico-3key-macropad
# 3-Key Pico Macropad

A custom 3-key mechanical macropad powered by a Raspberry Pi Pico, designed as a hardware warm-up project for Hack Club's Half-Life.

## Overview
This board connects three mechanical keyboard switches directly to the GPIO pins of a Raspberry Pi Pico with a shared ground plane. It is designed on a 2-layer PCB and exported for manufacturing via JLCPCB.

## Pinout & Wiring
- **Switch 1 (U2):** Pico GPIO 1 (Physical Pin 2)[cite: 4, 5]
- **Switch 2 (U3):** Pico GPIO 2 (Physical Pin 4)[cite: 4, 5]
- **Switch 3 (U4):** Pico GPIO 3 (Physical Pin 5)[cite: 4, 5]
- **Ground (GND):** Pico GND (Physical Pin 3 - Shared)[cite: 4, 5]

## Repository Contents
- `Gerber_PCB1_2026-10-03.zip`: Complete fabrication archive containing all copper, solder mask, silkscreen, and drill layers[cite: 2].
- `Screenshot 2026-10-03 140124.png`: Full schematic circuit diagram[cite: 5].
- `Screenshot 2026-10-03 140146.png`: 2D PCB layout showing trace routing and component footprints[cite: 4].
- `Screenshot 2026-10-03 140215.png`: 3D render preview of the board[cite: 3].

## Bill of Materials (BOM)

### Components
| Item | Description | Quantity |
| :--- | :--- | :--- |
| Custom PCB | 2-layer fabricated board (JLCPCB minimum order) | 5 pcs |
| Microcontroller | Raspberry Pi Pico (RP2040)[cite: 5] | 1 |
| Switches | Cherry MX style mechanical switches[cite: 5] | 3 |
| Keycaps | 1U standard mechanical keycaps | 3 |
| Headers | 2.54mm male pin headers | 1 set |
| Data Cable | Micro-USB to USB-A/C cable (data transfer & power) | 1 |

### Tools & Assembly Supplies
| Item | Purpose | Quantity |
| :--- | :--- | :--- |
| Heat-Resistant Working Mat | Silicone insulation soldering mat to protect the workspace surface | 1 |
| Soldering Iron Kit | 60W temperature-controlled iron with solder wire | 1 |
| Desoldering Wick / Pump | Solder removal braid for correcting bridge errors | 1 |
| Isopropyl Alcohol (IPA 90%+) | Board cleaning solvent to remove flux residue post-soldering | 1 bottle |
| Flush Cutters | Wire snips to trim through-hole header legs flush with the PCB | 1 |
