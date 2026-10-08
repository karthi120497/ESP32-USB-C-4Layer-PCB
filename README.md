# ESP32 with USB-C – 4-Layer PCB

A 4-layer ESP32 development board designed using EasyEDA. The board integrates USB-C connectivity, USB-to-UART communication, power management, reset and boot controls, status LEDs, and GPIO expansion headers.

This project demonstrates practical PCB design skills including schematic design, component selection, placement, multilayer routing, power distribution, grounding, signal routing, and PCB design-rule verification.

---

## Project Overview

The ESP32 development board provides a complete hardware platform for ESP32-based embedded applications.

### Main Features

- ESP32 module
- USB-C connector
- USB-to-UART interface
- 4-layer PCB
- 5V power selection
- 3.3V power selection
- 5V to 3.3V voltage regulation
- Reset button
- Boot/User button
- Power LED
- User LED
- GPIO headers
- Serial signal handling
- Ground and power planes
- Via stitching
- Dedicated ESP32 antenna area

---

## Schematic Design

The schematic is divided into multiple functional blocks to simplify the design and debugging process.

### USB-C Interface

The USB-C section provides:

- USB power input
- USB D+ and D− communication
- CC connections
- ESD/protection components
- Power filtering

### USB-to-UART Interface

The USB-to-UART section provides the communication interface between the USB-C port and ESP32 for:

- Firmware programming
- Serial communication
- Debugging

### Power Management

The power section includes:

- 5V power selection
- 3.3V power selection
- 5V-to-3.3V regulation
- Input and output filtering
- Power indication

### ESP32 Module

The ESP32 is the main controller of the board.

The module interfaces with:

- USB-UART
- Reset circuit
- Boot/User button
- GPIO headers
- Power supply
- Status LED

### Reset and Boot Circuit

Dedicated push buttons are provided for:

- ESP32 reset
- Boot/programming mode
- User input

### GPIO Headers

The header connectors provide access to ESP32 GPIO signals and power connections for connecting external sensors, modules, and peripherals.

---

# 4-Layer PCB Design

The PCB uses a 4-layer stack-up to improve power distribution, grounding, signal integrity, and overall routing flexibility.

### Layer Configuration

| Layer | Purpose |
|---|---|
| Top Layer | Components and signal routing |
| Inner Layer 1 | Ground / power distribution |
| Inner Layer 2 | Power / signal routing |
| Bottom Layer | Signal routing and ground |

---

## PCB Placement

Component placement was organized according to functional blocks.

### Placement Considerations

- USB-C connector positioned at the board edge
- USB-to-UART section placed close to the USB interface
- ESP32 module positioned in the RF section
- Decoupling capacitors placed close to IC power pins
- Power regulation components grouped together
- Reset and Boot buttons positioned for easy access
- GPIO headers arranged around the board
- Antenna area kept clear from unnecessary copper and components

---

## PCB Routing

The PCB layout focuses on clean and practical routing.

### Routing Considerations

- Short USB differential signal paths
- Proper power routing
- Dedicated ground plane
- Short decoupling paths
- Logical separation between power and signal sections
- Appropriate trace widths
- Via stitching for ground connectivity
- Controlled routing around the ESP32 RF section
- Reduced unnecessary routing length

---

## Design Verification

The PCB layout was reviewed for:

- Design Rule Check (DRC)
- Clearance
- Track width
- Via placement
- Component spacing
- Power connectivity
- Ground connectivity
- Silkscreen placement
- PCB outline
- Routing quality

---

## Skills Demonstrated

This project demonstrates experience in:

- Schematic capture
- Component selection
- PCB component placement
- 4-layer PCB design
- Multilayer routing
- Power distribution
- Ground-plane design
- USB routing
- UART interface design
- GPIO breakout
- Decoupling
- Via stitching
- DRC verification
- PCB layout optimization
- Design documentation

---

## Software Used

- EasyEDA
- EasyEDA Schematic Editor
- EasyEDA PCB Layout Editor

---

## Project Images

### Schematic

<img width="4698" height="3326" alt="SCH_Schematic1_1-P1_2026-10-08" src="https://github.com/user-attachments/assets/1498a1ea-f8f9-4db9-bb57-005a2491db1c" />


### PCB Layout

<img width="2160" height="746" alt="PCB_PCB1" src="https://github.com/user-attachments/assets/0d7c06eb-258b-4d9e-8a00-347c5b1bfa75" />

<img width="2160" height="746" alt="PCB_PCB2" src="https://github.com/user-attachments/assets/1f550698-a78c-4ac3-a4a6-ed28837eec0b" />

<img width="2160" height="746" alt="PCB_PCB3" src="https://github.com/user-attachments/assets/afce835b-5c6e-4f96-b5c1-08ff224d6d6e" />

<img width="2160" height="746" alt="PCB_PCB4" src="https://github.com/user-attachments/assets/5c558691-2698-4317-85dc-83a5567d1508" />

### 3D

<img width="2160" height="924" alt="3D_PCB1_2026-10-08" src="https://github.com/user-attachments/assets/887d9637-e83b-4191-a8eb-31f25d02fca7" />






---

