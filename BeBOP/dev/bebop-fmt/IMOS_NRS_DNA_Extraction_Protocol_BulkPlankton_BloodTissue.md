---
# MIOP terms
methodology_category: sample extraction and purification
project: Integrated Marine Observing System (IMOS) National Reference Stations (NRS) - zooplankton genomics (Zoogen); Australian Microbiome (https://www.australianmicrobiome.com/)
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: Australia:Beagle Gulf [GAZ:00051048], Australia:Great Australian Bight [GAZ:00045604], Australia:Tasman Sea coastal waters of continental Australia [GAZ:00143737], Australia:Moreton Bay Marine Park [GAZ:00088305], Australia:East Australian Current [GAZ:00000352], Australia:Eastern Indian Ocean coastal waters of Western Australia [GAZ:00051147], Australia:Great Barrier Reef Marine Park [GAZ:00049080] # TODO: GAZ term for Bonney Coast (VBM) not yet identified
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149] # TODO: consider a more specific ENVO material term for bulk zooplankton
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: # names separated by commas
materials_required: homogenizer, centrifuge [OBI:0400106], vortexer [OBI:0400118], thermomixer (shaking heat block)
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 180 # including thawing (~60 min) and lysis (90-120 min)
personnel_required: 1
language: en
issued: # YYYY-MM-DD
audience: scientists
publisher: Integrated Marine Observing System (IMOS); CSIRO Environment, Marine Microbiome Initiative Facility, Hobart
hasVersion: 0.1.0
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_vol_we_dna_ext: 20 # homogenised zooplankton slurry
samp_vol_we_dna_ext_unit: uL
nucl_acid_ext_lysis: physical | enzymatic | chemical
nucl_acid_ext_sep: column-based
nucl_acid_ext: # TODO: URL of this protocol once released
nucl_acid_ext_kit: Qiagen DNeasy Blood & Tissue Kit (69504)
nucl_acid_ext_modify: Whole sample homogenised with a hand-held homogeniser (Omni TH, hard tissue tip) before subsampling 20 uL of slurry; lysis 1.5-2 h at 56 degC, 800 rpm; elution incubations extended from 1 min to 15 min; two-step elution (100 uL + 50 uL Buffer AE). # TODO: NRS BGC Manual v5 (section 9.6) states 2 x 100 uL elution - confirm which is current
dna_cleanup_0_1: 0
dna_cleanup_method: not applicable
concentration: not applicable # recorded per sample
concentration_method: Invitrogen Qubit Flex Fluorometer with Qubit 1X dsDNA HS Assay Kit (Q33231)
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: not applicable
---

# IMOS NRS DNA Extraction Protocol: Bulk Plankton (DNeasy Blood & Tissue)

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit <https://orcid.org/> to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ----------- | ----------- | ----- | ---- |
| [Name] | [Affiliation] | [ORCID] | yyyy-mm-dd |

<!-- TODO: add authors. The method follows Berry et al. (2019). -->

### Related Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ---- | ------- | ------------ | ----------------- |
| IMOS NRS Bulk Plankton eDNA Sampling Protocol (Drop Net) | [IMOS_NRS_eDNA_Sampling_Protocol_BulkPlankton_DropNet.md](IMOS_NRS_eDNA_Sampling_Protocol_BulkPlankton_DropNet.md) | 0.1.0 | yyyy-mm-dd | Internal |
| National Reference Stations Biogeochemical Operations Manual (section 9.6) | <https://doi.org/10.26198/5c4a56f2a8ae3> | 5 | 2025-09 | Internal |
| DNeasy Blood & Tissue Handbook: Purification of Total DNA from Animal Tissues (Spin-Column Protocol) | <https://www.qiagen.com> | — | — | External |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------- | ------------ | ------------------------ |
| 0.1.0 | yyyy-mm-dd | Draft: bulk plankton DNA extraction protocol converted to BeBOP format |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ---------------------- | ---------- |
| AE | Elution buffer (Qiagen) |
| AL | Lysis buffer (Qiagen) |
| ATL | Tissue lysis buffer (Qiagen) |
| AW1, AW2 | Wash buffers 1 and 2 (Qiagen) |
| IMOS | Integrated Marine Observing System |
| MQ | MilliQ (ultrapure) water |
| NRS | National Reference Station(s) |
| RT | Room temperature |
| Zoogen | Zooplankton genomics sample: the unpreserved, frozen bulk zooplankton sample |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ---------------- | ---------- |
| Bulk plankton | Whole mixed plankton community from a net haul, extracted as a single homogenised sample |
| Homogenate (slurry) | Bulk plankton sample after mechanical homogenisation |

## BACKGROUND

This document describes the protocol used by the CSIRO Marine Microbiome Initiative Facility to extract DNA from bulk zooplankton samples collected at the IMOS National Reference Stations.

### Summary

The frozen bulk zooplankton sample (5 mL cryovial) is thawed and homogenised with a hand-held homogeniser. A 20 µL subsample of the homogenate is digested with proteinase K in Buffer ATL and purified on a silica spin column with the Qiagen DNeasy Blood & Tissue Kit. DNA is eluted in two steps in Buffer AE, quantified and archived at −80 °C. The resulting DNA is suitable for metabarcoding of zooplankton and other eukaryotic communities.

### Method Description and Rationale

Homogenising the whole sample before subsampling makes the small extraction volume representative of the community and reduces bias from large or patchy organisms. The DNeasy Blood & Tissue spin-column chemistry (proteinase K lysis, silica binding, washing and elution) is widely used, reproducible and gives inhibitor-free DNA from animal tissue. Extending the elution incubation to 15 min and eluting twice improves yield. The method follows Berry et al. (2019).

### Spatial Coverage and Environment(s) of Relevance

The protocol is applied to bulk zooplankton samples from the IMOS National Reference Stations around Australia (Darwin, Yongala, Rottnest Island, North Stradbroke Island, Maria Island, Bonney Mooring, Kangaroo Island and Port Hacking 100). Environments: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209].

## PERSONNEL REQUIRED

- 1 laboratory technician.

### Safety

- Bleach (5–10%) is corrosive and ethanol is flammable.
- Buffers AL and AW1 contain guanidine salts: do not mix them with bleach.
- Keep fingers clear of the rotating homogeniser probe and switch it off before removing the probe.
- Wear a lab coat, gloves and eye protection.

### Training Requirements

- Molecular laboratory technique and pipetting.
- Safe use of a hand-held homogeniser and centrifuge.

### Time Needed to Execute the Procedure

- Thawing: up to ~60 min.
- Homogenisation and extraction: about 2–2.5 h, including a 1.5–2 h lysis.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ----------- | ---------------------- | ------------ | -------- | ------ |
| **Durable equipment** | | | | |
| Hand-held homogeniser | Omni Tissue Homogeniser (TH23478) | Omni International (via Capella Science Pty Ltd) | 1 | |
| Homogeniser probes | Omni Hard Tissue Tip (PK/25) | Omni International | 1 clean probe per sample | Reusable after cleaning (see Equipment Cleaning) |
| Shaking heat block | Thermomixer Comfort | Eppendorf | 1 | 56 °C, 800 rpm |
| Oven | — | — | 1 | 56 °C, to dissolve buffer precipitates |
| Microcentrifuge | — | — | 1 | ≥20,000 × g |
| Vortex mixer | — | — | 1 | |
| Scissors | — | — | 1 | Cleaned with 10% bleach, rinsed with water, oven dried and stored in an empty tip box |
| Beaker | ~500 mL | — | 2 | One for used probes, one clean (ethanol-rinsed) for drying probes |
| Brush | Drinking-straw cleaning brush | — | 1 | For the inside of the probe |
| Fluorometer | Qubit Flex | Invitrogen | 1 | |
| **Consumable equipment** | | | | |
| Pipette tips | 200 µL (filter tips) | — | — | Cut the end off for viscous samples |
| Microcentrifuge tubes | 2 mL | — | 1 per sample | |
| Elution tubes | 1.7 mL | Lab Advantage | 1 per sample | Not supplied with the kit |
| Qubit assay tubes | — | Invitrogen | 1 per sample + standards | |
| Gloves | Single-use laboratory gloves | — | — | |
| Ice | — | — | — | |
| Aluminium foil | — | — | — | To cover drying probes |
| **Chemicals** | | | | |
| DNeasy Blood & Tissue Kit | 69504 | Qiagen | 1 kit (50 preps) | Buffers ATL, AL, AW1, AW2, AE; proteinase K; DNeasy Mini spin columns; 2 mL collection tubes |
| Ethanol | 96–100% | — | 200 µL per sample | |
| Ethanol | 70% | — | ~500 mL | Final probe rinse |
| Bleach | 5% (25 mL in 500 mL water) and 10% | — | — | Probe soak; cleaning scissors |
| Demineralised or MilliQ water | — | — | — | Rinsing |
| Qubit 1X dsDNA HS Assay Kit | Q33231 | Invitrogen | 1 per batch | |

## STANDARD OPERATING PROCEDURE

In the following SOP, the equipment names are those used in the table above.

### Preparation

1. Turn on the Thermomixer and preheat to 56 °C.
2. Check Buffers ATL and AL for precipitates. If any are present, warm the bottles in a 56 °C oven for 10 min.
3. Set up the probe-cleaning beakers (5% bleach, MilliQ water, 70% ethanol), see Equipment Cleaning.
4. Have ice ready for the thawed samples.

### Extraction

**Homogenisation**

1. Thaw the samples. They can take more than an hour. Once thawed, keep them on ice until processing.
2. Vortex the sample before homogenising.
3. Keep the sample on ice while homogenising. If the tube is more than half full, transfer the sample to a larger tube so it does not overflow.
4. Homogenise with the hand-held homogeniser at medium speed for about 15 s. Repeat 3 times.
5. Remove the probe, separate it into its inner and outer parts and place them in the beaker of used probes. Use a clean probe for each sample.
6. Transfer 20 µL of homogenate to a 2 mL microcentrifuge tube. For thick samples, cut the end off a 200 µL tip with the cleaned scissors to widen the bore.
7. Return the remaining homogenate to the −80 °C freezer.

**Lysis**

8. Add 180 µL Buffer ATL to the 20 µL aliquot.
9. Add 20 µL proteinase K.
10. Vortex to mix.
11. Place in the preheated Thermomixer at 56 °C and 800 rpm with intermittent mixing.
12. Incubate for 1.5–2 h, vortexing every 30 min, until the sample looks clear.
13. Vortex for 15 s.
14. Add 200 µL Buffer AL and mix by vortexing.
15. Add 200 µL ethanol (96–100%) and mix by vortexing.

**Binding and washing**

16. Pipette the mixture into a DNeasy Mini spin column in a 2 mL collection tube.
17. Centrifuge at ≥6,000 × g (8,000 rpm) for 1 min. Discard the flow-through and collection tube.
18. Place the spin column in a new 2 mL collection tube.
19. Add 500 µL Buffer AW1.
20. Centrifuge at ≥6,000 × g (8,000 rpm) for 1 min. Discard the flow-through and collection tube.
21. Place the spin column in a new 2 mL collection tube.
22. Add 500 µL Buffer AW2.
23. Centrifuge at ≥20,000 × g (14,000 rpm) for 3 min. Empty the collection tube but keep it.
24. Centrifuge again at ≥20,000 × g (14,000 rpm) for 1 min to remove any remaining liquid.

**Elution**

25. Place the spin column in a 1.7 mL tube (Lab Advantage; not supplied with the kit).
26. Pipette 100 µL Buffer AE directly onto the membrane.
27. Incubate at RT for 15 min (the kit protocol suggests 1 min).
28. Centrifuge at ≥6,000 × g (8,000 rpm) for 2 min.
29. For a second elution, add another 50 µL Buffer AE to the membrane. <!-- TODO: NRS BGC Manual v5 section 9.6 states 2 x 100 uL; confirm current volume -->
30. Incubate at RT for 15 min.
31. Centrifuge at ≥6,000 × g (8,000 rpm) for 2 min.

### Quantification and Storage

1. Measure DNA concentration with the Qubit Flex and the Qubit 1X dsDNA HS Assay Kit (Invitrogen Q33231). Record results in the sample log.
2. Archive the extracts at −80 °C.

### Equipment Cleaning (Homogeniser Probes)

Probes can be reused after cleaning.

1. Separate the inner and outer parts of the probe. Soak them in 5% bleach (25 mL bleach in 500 mL water) in a large beaker for 10 min.
2. During the soak, remove any material from the inside and outside of the probe. Use a drinking-straw brush to clean inside the probe cover.
3. Rinse the probes thoroughly with demineralised or MilliQ water, then leave them to soak in this water for 10 min.
4. Give the probes a final rinse in 70% ethanol (350 mL ethanol in 500 mL water).
5. Place the wet probes in a clean, ethanol-rinsed beaker to dry, loosely covered with foil.

### Quality Control

- A clean, bleach-decontaminated probe is used for each sample to prevent cross-contamination.
- Samples should look clear after the proteinase K incubation. Extend the incubation if tissue is still visible.
- DNA concentration is recorded for every extract.
- <!-- TODO: state whether extraction blanks (reagent-only), probe/equipment blanks or positive controls are included per batch --> Controls are not specified in the source protocol.

### Basic Troubleshooting Guide

- **Sample overflows during homogenisation.** Transfer it to a larger tube before homogenising (tube no more than half full).
- **Viscous homogenate is hard to pipette.** Use a wide-bore tip made by cutting the end off a 200 µL tip with the cleaned scissors.
- **Precipitate in Buffer ATL or AL.** Warm the bottle at 56 °C for 10 min and mix before use.
- **Incomplete lysis.** Extend the 56 °C incubation and vortex every 30 min.
- **Spin column clogs.** The homogenate may contain undigested material or too much tissue. Make sure the lysate is clear before adding Buffer AL, and avoid aspirating large particles.
- **Low yield.** Check that the subsample was taken from well-homogenised material and that the elution incubation was at least 15 min.

## REFERENCES

- Berry, T.E., Saunders, B.J., Coghlan, M.L., Stat, M., Jarman, S., et al. (2019). Marine environmental DNA biomonitoring reveals seasonal patterns in biodiversity and identifies ecosystem responses to anomalous climatic events. *PLOS Genetics*, 15(2), e1007943. <https://doi.org/10.1371/journal.pgen.1007943>
- Davies, C. (Ed.) (2025). *National Reference Stations Biogeochemical Operations Manual*, Version 5. Integrated Marine Observing System. <https://doi.org/10.26198/5c4a56f2a8ae3>
- Qiagen. *DNeasy Blood & Tissue Handbook*: Purification of Total DNA from Animal Tissues (Spin-Column Protocol).

## APPENDIX A: DATASHEETS

- **MMI sample log (Hobart):** records sample receipt, storage location, extraction batch and DNA concentration. <!-- TODO: link -->
