# Pedals_5 — EV Pedal Electronics

Hardware design documentation and engineering exports for the `Pedals_5` PCB revision.

**Repository type:** hardware design archive · **Status:** design artifacts published; verification and production release not documented

## Overview

This repository provides PCB design deliverables for an electric-vehicle pedal electronics project. The current publication includes an original project archive, manufacturing Gerber files, an exported electrical schematic and a mechanical STEP model.

It is intended for design review and traceability. **It is not presented as a tested or production-approved hardware release.**

## Files and documentation

| Path | Description |
| --- | --- |
| [`design/RTE_35_Pedals_5.zip`](design/RTE_35_Pedals_5.zip) | Original project ZIP archive. Inspect the ZIP to identify editable files and software requirements. |
| [`manufacturing/gerbers/Pedals_5_Gerbers.zip`](manufacturing/gerbers/Pedals_5_Gerbers.zip) | PCB Gerber export archive; verify completeness and layer assignments before fabrication. |
| [`docs/schematic/Pedals_5_Schematic.pdf`](docs/schematic/Pedals_5_Schematic.pdf) | Electrical schematic export (PDF). |
| [`mechanical/Pedals_5_PCB.step`](mechanical/Pedals_5_PCB.step) | PCB 3D mechanical export (STEP). |
| [`docs/HARDWARE_RELEASE_CHECKLIST.md`](docs/HARDWARE_RELEASE_CHECKLIST.md) | Checklist for an engineering review and fabrication handoff; not evidence of completed checks. |

All four original design/export files were **relocated without altering their binary contents**; filenames were normalized for navigation.

## Design review workflow

1. **Electrical:** review the schematic, component ratings and intended electrical interfaces.
2. **Mechanical:** open the STEP file in a CAD viewer to check the board envelope and integration.
3. **PCB manufacturing:** load the Gerbers in a dedicated viewer. Confirm the stack-up, drill files, board outline and fabrication notes with your manufacturer.
4. **Project sources:** inspect the ZIP and open applicable editable project files in the appropriate ECAD application.
5. **Release readiness:** use the [hardware release checklist](docs/HARDWARE_RELEASE_CHECKLIST.md) and retain test and review evidence.

## Engineering release status

| Area | Evidence in this repository |
| --- | --- |
| Schematic export | Available |
| Gerber archive | Available |
| 3D STEP export | Available |
| Project ZIP archive | Available |
| Approved BOM and assembly files | Not separately documented |
| ERC / DRC reports | Not separately documented |
| Test results and validated requirements | Not documented |
| Approved production release | Not documented |

*Not documented* means the repository does not establish the result; it does **not** mean the activity was never performed.

## Usage and licensing

The design files are published for reference and review. There is currently **no LICENSE file**, so public visibility must not be interpreted as a grant of redistribution, modification or commercial-use rights.

Do not manufacture or deploy the design without checking the source project, relevant safety requirements, actual assembly configuration and evidence from appropriate engineering testing.

---

**Maintainer:** [Jazzi25](https://github.com/Jazzi25) · **Revision:** `Pedals_5` (as named by source artifacts)
