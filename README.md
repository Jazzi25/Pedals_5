# EV Pedal Assembly — Hardware Design Files

> Hardware design exports and mechanical documentation for the `Pedals_5` revision.

This repository collects the available PCB/manufacturing exports, a schematic PDF, a 3D STEP model and a project ZIP archive. It is intended as a **design-artifact archive**, not a verified, ready-to-manufacture release or a complete source-code repository.

## Repository contents

| File | Format | Purpose |
| --- | --- | --- |
| [`RTE_35_Pedals_5.zip`](RTE_35_Pedals_5.zip) | ZIP | Project archive; inspect its contents before assuming which editable source files it includes. |
| [`Gerber for PCB.PcbDoc.zip`](Gerber%20for%20PCB.PcbDoc.zip) | ZIP | Export named as the PCB Gerber package; verify the actual layer and drill-file set before ordering boards. |
| [`Schematic PDF_[No Variations] (1).pdf`](Schematic%20PDF_%5BNo%20Variations%5D%20%281%29.pdf) | PDF | Exported electrical schematic for design review. |
| [`STEP_[No Variations] for PCB.PcbDoc.step`](STEP_%5BNo%20Variations%5D%20for%20PCB.PcbDoc.step) | STEP | 3D CAD export for mechanical inspection and integration. |

The original export filenames are intentionally preserved to avoid breaking references to existing artifacts.

## Reviewing the design

1. **Electrical:** Open the schematic PDF and review the intended connections, component ratings and power interfaces.
2. **Mechanical:** Open the STEP file in a compatible CAD viewer and verify physical envelope and mounting clearances against the target assembly.
3. **PCB manufacturing:** Inspect the Gerber ZIP using a Gerber viewer. Confirm the layer mapping, board outline, drill data and fabrication requirements.
4. **Editable project:** Inspect the project ZIP and its tool/version requirements before attempting modifications.

## Release and verification status

**Not documented in this repository:** completed electrical validation, PCB design-rule results, functional test results, a reviewed BOM, an assembly package or an approved fabrication stack-up. Absence of these records does not establish that the checks were not performed; it means they cannot be verified from the published file list.

Before fabrication, use the [hardware release checklist](docs/HARDWARE_RELEASE_CHECKLIST.md). This is a checklist of **pending verification**, not a claim of completed testing.

## Scope

- **Included:** existing design exports and project archive.
- **Not present as standalone files:** firmware source, bill of materials, test reports and build instructions.
- **License:** no license is declared. Do not assume permission to redistribute, modify or commercially use these files.

---

**Note:** The archive documents a design revision. Specifications and validation should be established from reviewed source files and test evidence, not inferred from filenames alone.
