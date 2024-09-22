# FIC Opensource Altium Library (FIC_OAL)
## Overview
Welcome to the FIC Opensource Altium Library (FIC_OAL)! This repository contains a collection of component footprints and 3D models designed for use with Altium Designer.

## Contributing
Contributions are welcome! If you'd like to add to or improve the library:
1. Please request components you need to be added to the library by creating an issue.

## Features
- **Comprehensive Footprints**: Includes a variety of component footprints, designed for accuracy and manufacturability.
- **Standardized Layouts**: All components follow IPC and industry standards for design consistency.
- **3D Models**: Where applicable, 3D models are provided for enhanced design visualization.
- **Courtyard & Silkscreen Optimization**: Footprints are optimized for spacing and placement, ensuring error-free assembly.

## How to Use

This convention ensures a consistent naming structure for all symbols in the library, making it easier to search, categorize, and identify components.

### 1. Passive Components
- Resistor: `RES_`
- Capacitor: `CAP_`
- Inductor/Ferrite Bead:
  - Inductor: `IND_`
  - Ferrite Bead: `FB_`

### 2. Connectors
- Prefix: `CON_`
- Format: `CON_[NUM PINS]_[PITCH]_[V/H/A][S/D/T/F][M/F][TYPE]`
  - NUM PINS: Number of pins (e.g., 08 for an 8-pin connector)
  - PITCH: Pin pitch in hundredths of millimeters (e.g., 254 for 2.54 mm pitch, 350 for 3.50 mm)
  - V/H/A (Optional): Orientation—V for vertical, H for horizontal, A for angled
  - S/D/T/F (Optional): Number of rows—S for single, D for double, T for triple, F for four
  - M/F (Optional): Gender—M for male, F for female
  - TYPE:
    - PHD: Pin Header
    - TBRC: Terminal Block Rising Clamp
    - TBPL: Terminal Block Pluggable
    - TBSC: Terminal Block Spring Clamp
    - TBBA: Terminal Block Barrier

### 3. Semiconductors
- Bipolar Junction Transistor (BJT): `BJT_`
- Field-Effect Transistor (FET): `FET_`
- Silicon-Controlled Rectifier (SCR): `SCR_`
- Triac: `TRI_`
- Optocoupler: `OPT_`

### 4. Crystals and Oscillators
- Crystal: `XTAL_`
- Oscillator: `OSC_`

### 5. Diodes and LEDs
- Diode: `DIO_`
- Light-Emitting Diode (LED): `LED_`

### 6. Switches and Buttons
- Switch: `SWC_`
- Button: `BTN_`

### 7. Relays
- Relay: `RLY_`

### 8. Integrated Circuits (ICs)
- Microcontroller: `MCU_`
- Analog-to-Digital Converter: `ADC_`
- Digital-to-Analog Converter: `DAC_`
- Interface IC: `INF_`
- Memory: `MEM_`
- Operational Amplifier (OpAmp): `OPA_`
- Sensor ICs: `SEN_`
- Buffer ICs: `BUF_`

### 9. Mechanical Parts
- Mechanical Component: `MEC_`

### 10. Displays
- Display Components: Naming convention depends on display type (not specified in detail here)

### 11. Power Components
- Power Modules and Power ICs: `PWR_`

## Feedback & Support

If you have any issues, suggestions, or feedback, feel free to open an issue on GitHub. I look forward to your contributions and feedback!
