# Hi-Fi Microphone PCB

A custom PCB for the high-fidelity microphone project by DIY Perks, redesigned from the original stripboard version for a cleaner and more reliable build.

![PCB Front](<mic_base/Other Files/mic_base_pcb.png>)
![PCB Back](<mic_base/Other Files/mic_base_pcb_back.png>)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [PCB Design](#pcb-design)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Credits](#credits)

## Overview

This project provides a dedicated PCB for the Hi-Fi microphone circuit originally demonstrated by [DIY Perks](https://www.youtube.com/watch?v=LoQu3XXIayc). While the original build used a stripboard, this KiCad project offers a custom-designed PCB, making the assembly process more straightforward and the final product more durable and professional.

## Features

- **Dedicated PCB Design**: Eliminates complex wiring on stripboard, improving reliability.
- **Compact & Clean Layout**: Components are organized for a tidy and space-efficient build.
- **Easy Assembly**: Through-hole components and clear labeling simplify the soldering process.
- **Professional Finish**: Achieve a high-quality result comparable to commercial products.

## PCB Design

The project was designed in KiCad and consists of a single two-layer board.

- **[Schematic PDF](<mic_base/Other Files/mic_base_schematic.pdf>)**
- **[PCB Layout PDF](<mic_base/Other Files/mic_base_layout.pdf>)**

### PCB Renders

|                       Front View                      |                        Back View                          |                         Initial Design                        |
| :---------------------------------------------------: | :-------------------------------------------------------: | :-----------------------------------------------------------: |
| ![PCB Front](<mic_base/Other Files/mic_base_pcb.png>) | ![PCB Back](<mic_base/Other Files/mic_base_pcb_back.png>) | ![Initial PCB Design](<mic_base/Other Files/initial_pcb.png>) |

## Project Structure

```
hi-fi-mic/
├── Imports/                  # Custom 3D models, footprints, and symbols
├── Other Files/              # Documentation (PDFs) and images
├── mic_base.kicad_pcb        # KiCad PCB layout file
├── mic_base.kicad_pro        # Main KiCad project file
├── mic_base.kicad_sch        # KiCad schematic file
└── README.md                 # This file
```

## Getting Started

### Hardware Assembly

1.  **Manufacture the PCB**: Use the KiCad project files to export Gerbers and order the board from a PCB fabrication service.
2.  **Gather Components**: Refer to the schematic for the complete Bill of Materials (BOM).
3.  **Solder Components**: Assemble the board, starting with the lowest-profile components first.
4.  **Testing**: Follow the testing and calibration steps shown in the original [DIY Perks video](https://www.youtube.com/watch?v=LoQu3XXIayc).

### Opening the Project

1.  Install [KiCad](https://www.kicad.org/) 7.0 or later.
2.  Open the `mic_base.kicad_pro` file to access the schematic and PCB layout.

## Credits

- **Original Circuit Concept**: [DIY Perks](https://www.youtube.com/c/DIYPerks)
- **PCB Redesign**: This project.
