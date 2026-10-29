# Hardware release checklist

This checklist is a guide for future review of the `Pedals_5` design artifacts. **All items start unchecked** because this repository does not contain evidence that they have been signed off.

## 1. Design review

- [ ] Confirm the intended hardware revision, board purpose and requirements.
- [ ] Review schematic and reference designs against component datasheets.
- [ ] Check power rails, protection, signal interfaces and connector pinouts.
- [ ] Confirm component footprints, polarity and lifecycle/availability.
- [ ] Run and record electrical-rule checks (ERC) in the original ECAD project.

## 2. PCB and mechanical review

- [ ] Run and archive PCB design-rule check (DRC) results.
- [ ] Verify fabrication stack-up, copper weights, clearances and drill sizes with the board house.
- [ ] Confirm the PCB outline, mounting holes and STEP model against the mechanical assembly.
- [ ] Check silkscreen references, orientation, solder-mask openings and test access.

## 3. Manufacturing data

- [ ] Inspect every exported Gerber layer and the board outline using an independent viewer.
- [ ] Confirm that all required plated/non-plated drill files are provided.
- [ ] Supply a reviewed BOM with manufacturer part numbers.
- [ ] Supply assembly drawings and, when applicable, pick-and-place data.
- [ ] Record the revision identifier and keep all exports consistent with the approved source.

## 4. Verification

- [ ] Define and document electrical and functional test procedures.
- [ ] Validate power-up behavior and expected operating conditions.
- [ ] Validate interface behavior under nominal and applicable fault conditions.
- [ ] Document test equipment, results, known limitations and approver.

## 5. Release handoff

- [ ] Bundle the approved project sources and manufacturing outputs.
- [ ] Record release date, changelog, reviewer and hardware revision.
- [ ] Obtain project/team sign-off before sending files to fabrication.

**Current status:** These actions have not been verified from repository contents. Mark an item complete only with supporting evidence.
