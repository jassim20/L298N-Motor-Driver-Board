# L298N Motor Driver Board

A dual H-bridge motor driver board designed in Altium Designer, fabricated and functionally tested by the designer.

**Status:** Original hardware revision (v1.0.0); native hardware source and manufacturing archives published. Physical fabrication and functional testing are designer-confirmed.

![L298N motor driver board — Altium 3D preview](Images/03-pcb-3d.png)

## Design Previews

[ Schematic ](Images/01-schematic.png) · [ 2D PCB layout ](Images/02-pcb-2d.png) · [ 3D PCB preview ](Images/03-pcb-3d.png)

Previews were captured from the original Altium design; they are not photographs of the fabricated hardware.

## Hardware Overview

| Item | Design information |
| --- | --- |
| Motor driver | L298N |
| Logic supply regulator | L7805CV |
| Protection diodes | 8 × 1N4007 |
| Control signals | EN1, EN2, IN1–IN4 |
| Motor outputs | OUT1–OUT4 |
| Power nets | VCC, +5, GND |
| PCB fabrication data | Top and bottom copper, solder masks, overlays, paste layers and board profile |
| NC drill | 55 plated round holes across 5 tool sizes |

The component inventory and net labels were extracted from the native schematic. The Gerber extension and drill reports support the manufacturing data above. Electrical operating limits and test conditions have not been independently established.

## Native Design Files

- [Altium project](Hardware/L298N.PrjPcb)
- [Schematic](Hardware/Schematic/Sheet1.L298N.SchDoc)
- [PCB layout](Hardware/PCB/PCB1.L298N.PcbDoc)
- [Output job](Hardware/Job1.OutJob)
- [Schematic inventory and review scope](Hardware/Schematic/README.md)

The schematic and PCB files are byte-for-byte copies of the original sources. The published project and output-job configuration use relative paths; unavailable external library references and stale generated-document references were removed from the project copy. External component libraries are not included. The portable project has not been independently opened or compiled after the path adjustments.

## Manufacturing

- [Gerber ZIP](Manufacturing/Gerber.zip)
- [NC Drill ZIP](Manufacturing/NC%20Drill.zip)
- [Fabrication ZIP](Manufacturing/L298N-Fabrication.zip)
- [Manufacturing notes](Manufacturing/README.md)

The manufacturing archives were supplied by the designer for v1.0.0. Their equivalence to the earlier exports and PCB has not been independently established. Their drill report lists 55 plated holes. Review the files in a fabrication viewer and confirm the board outline, drill format and manufacturer DFM requirements before ordering.

## Verification

- PCB fabricated and functionally tested, as reported by the designer.
- Native schematic and PCB source identity checked using Git blob hashes.
- [Historical DRC report](Documentation/Historical-DRC.txt) reports zero violations and zero waived violations. Its date field is 1/3/2026, predating the current PCB file. A fresh DRC and a complete schematic/ERC review of the current revision are not included.
- Visual schematic review: L298N SENSE A (pin 1) and SENSE B (pin 15) appear unconnected. Confirm their connection to ground or the appropriate current-sense return in both the physical board and the PCB before further fabrication. This observation is not a completed ERC or a determination of the tested hardware's wiring.
- Detailed test results, procurement BOM and independent electrical ratings are not included.

## Repository Structure

- Hardware/ — project configuration, schematic, PCB and output job
- Manufacturing/ — Gerber, NC drill and fabrication archive
- Images/ — schematic and 2D/3D design previews
- Documentation/ — review records
- README.md, CHANGELOG.md, LICENSE

## Copyright

**Copyright (c) 2026 jassim20. All rights reserved.** Original materials are published for portfolio and reference purposes. See [LICENSE](LICENSE) for usage terms and exceptions.

## Contact

[GitHub portfolio](https://github.com/jassim20) · [LinkedIn](https://www.linkedin.com/in/jassim-auda-7b9279207/)
