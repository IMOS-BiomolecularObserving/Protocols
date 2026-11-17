---
methodology_category: sample extraction and purification
project: general
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: []
broad_scale_environmental_context: []
local_environmental_context: []
environmental_medium: []
target: deoxyribonucleic acid (DNA) [NCIT:C449]
creator:
materials_required:
  - Hand held homogeniser and probes (Omni Tissue Homogeniser TH23478 and Omni Hard Tissue Tip PK/25)
  - Qiagen DNeasy Blood & Tissue Kit (Catalogue number 69504)
  - 1 x large beaker (e.g. 500 mL) for dirty probes
  - 200 µL tips (including ability to use cut/wide-bore tips)
  - Scissors (cleaned with 10% bleach, rinsed with water, dried in oven; stored in empty tip box)
  - Shaking heat block (e.g. Eppendorf Thermomixer Comfort)
  - Ice
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 180  # minutes (including thawing and incubation)
personnel_required: 1
language: en
issued: 2026-11-17
audience: scientists
publisher:
hasVersion: 1.0.0
license: CC0 1.0 Universal
maturity level: mature

samp_vol_we_dna_ext: 0.02
samp_vol_we_dna_ext_unit: mL
nucl_acid_ext_lysis: physical and enzymatic
nucl_acid_ext_sep: centrifugation (spin-column)
nucl_acid_ext_kit: Qiagen DNeasy Blood & Tissue Kit (Catalogue number 69504)
nucl_acid_ext_modify: Protocol adapted from Qiagen spin-column protocol; includes pre-homogenisation step and manual probe cleaning.
dna_cleanup_method: DNeasy Mini spin column
concentration_method: QubitFlex using Qubit 1x dsDNA HS Assay Kit (Invitrogen Q33231)
dna_cleanup_0_1: 1.0
nucl_acid_ext_method_additional: not applicable

---

# PROTOCOL INFORMATION

## Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are included in the YAML frontmatter above.

## Making eDNA FAIR (FAIRe)

- FAIRe terms are included in the YAML frontmatter above.

## Authors

| PREPARED BY  | AFFILIATION  | ORCID        | DATE       |
| ------------ | ------------ | ------------ | ---------- |
| [Name]       | [Affiliation]| [ORCID]      | 2026-11-17 |

### Related Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ---- | ------- | ------------- | ----------------- |
| Qiagen DNeasy Blood & Tissue Handbook | https://www.qiagen.com | Spin-column protocol | - | External |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------- | ------------- | ------------------------- |
| 1.0.0 | 2026-11-17 | Initial BeBOP formatting of DNA extraction method with template examples removed. |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ---------------------- | ---------- |
| ATL | Lysis Buffer (Qiagen) |
| AL  | Lysis Buffer (Qiagen) |
| AW1 | Wash Buffer 1 (Qiagen) |
| AW2 | Wash Buffer 2 (Qiagen) |
| AE  | Elution Buffer (Qiagen) |
| PK  | Proteinase K |

## BACKGROUND

This protocol describes the extraction of total DNA from animal tissues using mechanical homogenisation and the Qiagen DNeasy Blood and Tissue kit. It is optimized for high-quality DNA recovery suitable for biodiversity assessment and downstream omics analyses.

### Summary

Samples are thawed on ice, mechanically homogenised using an Omni hand-held homogeniser, and then processed via a standard spin-column protocol involving enzymatic lysis, silica-membrane binding, washing, and two-step elution.

### Method Description and Rationale

Mechanical homogenisation ensures uniform sample processing and maximal cell disruption. The use of a silica-based spin-column kit provides high-purity DNA by removing inhibitors and cellular debris through sequential washing steps.

## PERSONNEL REQUIRED

- 1 Technician / Researcher

### Safety

- 10% Bleach is corrosive; handle with care.
- Ethanol is flammable.
- Standard laboratory PPE (gloves, lab coat, eye protection) must be worn.

### Training Requirements

- Competency in sterile technique and pipetting.
- Safe operation of hand-held homogenisers and centrifuges.

### Time Needed to Execute the Procedure

- Thawing: ~60 minutes
- Extraction/Incubation: ~120–150 minutes

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ----------- | ---------------------- | ------------ | -------- | ------ |
| Homogeniser | Omni Tissue Homogeniser TH23478 | Omni | 1 | Use dedicated new probe per sample; probes reusable after cleaning |
| Homogeniser probe tips | Omni Hard Tissue Tip PK/25 | Omni | as needed | Clean between uses per protocol |
| Extraction Kit | DNeasy Blood & Tissue Kit | Qiagen (Cat. 69504) | 1 kit | Follow spin-column tissue protocol with adaptations below |
| Shaking heat block | Thermomixer Comfort | Eppendorf | 1 | Set to 56°C, 800 rpm intermittent mixing |
| Microcentrifuge | — | — | 1 | Capable of ≥20,000 x g |
| 2 mL microcentrifuge tubes | — | — | as needed | For spin columns and collection tubes |
| 1.7 mL tubes | Lab Advantage (or equivalent) | — | as needed | Used for elution when kit does not provide appropriate tubes |
| 200 µL pipette tips | Filtered tips | — | as needed | Use wide-bore tip for viscous samples if required |
| Scissors | Cleaned scissors | — | 1 set | Cleaned with 10% bleach, rinsed, dried in oven; stored in empty tip box |
| Large beaker | 500 mL | — | 1 | For soaking dirty probes |
| Ice | — | — | as needed | Keep thawed samples on ice |

## STANDARD OPERATING PROCEDURE

In the following SOP, use the exact names of equipment as noted above.

### Preparation

1. Turn on shaking incubator (Eppendorf Thermomixer Comfort) and preheat to 56°C.
2. Check ATL and AL buffers for precipitates. If precipitates are present, warm bottles in a 56°C oven for 10 min to dissolve.
3. Prepare a clean workspace and ensure ice is available for thawed samples.
4. Prepare cleaning stations for probes (beakers with bleach solution, MQ/demineralised water, 70% ethanol) — see "Cleaning method for probes" below.

### Extraction

1. Thaw samples at 4°C or on ice. Once thawed, keep the sample on ice until ready to process. (Samples may take over an hour to thaw.)
2. Vortex the sample briefly prior to homogenisation.
3. Homogenisation:
   - Place sample on ice during homogenisation.
   - If sample tube is more than half full, transfer to a larger tube to prevent overflow when using the homogeniser.
   - Set the Omni Tissue Homogeniser to medium speed and homogenise for approximately 15 seconds. Repeat this homogenisation step 3 times.
4. After homogenisation, remove the probe, separate the probe into inner and outer parts and place into a beaker designated for dirty probes for later cleaning. Use a new probe for each sample.
5. Aliquot 20 µL homogenised sample into a 2 mL microcentrifuge tube. If sample is very thick/viscous, cut the end off a 200 µL tip to widen the bore and aid transfer (use cleaned scissors).
6. Return remaining homogenised sample to the freezer.
7. To the 20 µL aliquot, add 180 µL Buffer ATL.
8. Add 20 µL Proteinase K.
9. Vortex briefly to mix.
10. Place tubes in the pre-heated Eppendorf Thermomixer Comfort at 56°C, 800 rpm with intermittent mixing.
11. Incubate for 1.5–2 hours. Vortex every 30 minutes. Samples should appear clear when digestion is complete.
12. Vortex sample 15 seconds after incubation.
13. Add 200 µL Buffer AL to each sample. Mix by vortexing.
14. Add 200 µL 96–100% ethanol. Mix by vortexing.
15. Pipette the full lysate/ethanol mix into the DNeasy Mini spin column placed in a 2 mL collection tube.
16. Centrifuge ≥ 6,000 x g (≈8,000 rpm) for 1 minute. Discard flow-through and collection tube.
17. Place spin column into a new 2 mL collection tube.
18. Add 500 µL Buffer AW1 to the column.
19. Centrifuge ≥ 6,000 x g (≈8,000 rpm) for 1 minute. Discard flow-through and collection tube.
20. Place spin column into a new 2 mL collection tube.
21. Add 500 µL Buffer AW2 to the column.
22. Centrifuge ≥ 20,000 x g (≈14,000 rpm) for 3 minutes. Empty the collection tube but do not discard the tube.
23. Perform an additional centrifugation ≥ 20,000 x g (≈14,000 rpm) for 1 minute to remove residual wash buffer.
24. Transfer the spin column to 1.7 mL tubes (Lab Advantage or equivalent) for elution (the kit may not provide these).
25. Pipette 100 µL Buffer AE directly onto the membrane.
26. Incubate at room temperature for 15 minutes (note: protocol suggests 1 min; extended incubation used here to improve yield).
27. Centrifuge ≥ 6,000 x g (≈8,000 rpm) for 2 minutes to elute DNA (first elution).
28. For a second elution, add a further 50 µL Buffer AE directly to the membrane.
29. Incubate at room temperature for 15 minutes.
30. Centrifuge ≥ 6,000 x g (≈8,000 rpm) for 2 minutes (second elution).

## POST-EXTRACTION QC

1. Measure DNA concentration using a Qubit Flex with the Qubit 1x dsDNA HS Assay Kit (Invitrogen Q33231) according to manufacturer instructions.
2. Record yield and any notes about sample appearance.

## QUALITY CONTROL

- Include negative extraction controls (blank buffer processed through the entire workflow) to monitor contamination.
- Include positive control tissue samples, where appropriate, to confirm extraction success.
- Acceptance criteria: successful control amplification or expected concentration range as determined for downstream application; no detectable DNA in negative extraction controls above background.

### Basic Troubleshooting Guide

- Low yield: ensure complete digestion (incubation time, vortexing every 30 min), verify Proteinase K activity, ensure ethanol added is 96–100% and mixed thoroughly, check binding/wash step centrifugation speeds.
- Column clogging/slow flow: reduce initial input volume or centrifuge longer; ensure lysate is not overloaded on the column; pre-clarify viscous samples if necessary.
- Contamination detected in negative controls: review probe cleaning, workstation cleanliness, use fresh tips and gloves, process fewer samples per batch, decontaminate surfaces with 10% bleach followed by 70% ethanol.

## CLEANING METHOD FOR HOMOGENISER PROBES

Probes can be reused after thorough cleaning:

1. Separate the inner and outer parts of the probe.
2. Soak both parts in 5% bleach (prepare 25 mL bleach in 500 mL water) for 10 minutes in a large beaker.
3. During the bleach soak, clean off any visible material from the inside and outside of the probe. Use a brush designed for cleaning drinking straws to clean interior surfaces thoroughly.
4. Rinse probes thoroughly with deionised (demineralised) or Milli-Q (MQ) water. Leave to soak in this water for 10 minutes.
5. Perform a final rinse in 70% ethanol (e.g., 350 mL ethanol in 500 mL water).
6. Place the wet probes in a clean beaker (pre-rinsed with ethanol) and leave to dry. Loosely cover beaker with foil while drying.
7. Store dried probes in a clean container until next use. Use a new probe for each sample and clean between uses as described.

## REFERENCES

- Qiagen DNeasy Blood & Tissue Kit Handbook — spin-column protocol (follow kit instructions; adaptations described above).
- Qubit 1x dsDNA HS Assay Kit, Invitrogen Q33231 — manufacturer instructions for concentration measurement.
