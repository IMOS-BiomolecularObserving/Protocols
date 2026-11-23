---
# MIOP terms
methodology_category: sample extraction and purification
project: Integrated Marine Observing System (IMOS) National Reference Stations (NRS) - Marine Microbiome Initiative; Australian Microbiome (https://www.australianmicrobiome.com/)
purpose: biodiversity assessment objective [OBI:0001969]
analyses: DNA extraction [OBI:0000257]
geographic_location: Australia:Beagle Gulf [GAZ:00051048], Australia:Great Australian Bight [GAZ:00045604], Australia:Tasman Sea coastal waters of continental Australia [GAZ:00143737], Australia:Moreton Bay Marine Park [GAZ:00088305], Australia:East Australian Current [GAZ:00000352], Australia:Eastern Indian Ocean coastal waters of Western Australia [GAZ:00051147], Australia:Great Barrier Reef Marine Park [GAZ:00049080] # TODO: GAZ term for Bonney Coast (VBM) not yet identified
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149]
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: # names separated by commas
materials_required: vortexer [OBI:0400118], centrifuge [OBI:0400106], heating block [OBI:0400108], incubator [OBI:0000136], vacuum manifold [OBI:0001116], fume hood
skills_required: sterile technique, pipetting skills, standard molecular technique, safe handling of phenol and chloroform
time_required: 360 # batch of 12 Sterivex filters
personnel_required: 1
language: en
issued: # YYYY-MM-DD
audience: scientists
publisher: Integrated Marine Observing System (IMOS); CSIRO Environment, Marine Microbiome Initiative Facility, Hobart
hasVersion: 0.1.0
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_vol_we_dna_ext: 2000 # whole Sterivex filter extracted (= volume filtered)
samp_vol_we_dna_ext_unit: mL
nucl_acid_ext_lysis: physical | enzymatic | chemical
nucl_acid_ext_sep: phenol chloroform | column-based
nucl_acid_ext: # TODO: URL of this protocol once released
nucl_acid_ext_kit: Qiagen DNeasy PowerWater Sterivex Kit (50) (14600-50-NF)
nucl_acid_ext_modify: Kit lysis replaced by in-house CTAB/PVP phosphate lysis buffer with lysozyme and MT buffer (horizontal vortexing in the Sterivex housing), followed by phenol:chloroform:isoamyl alcohol extraction, proteinase K digestion and two chloroform:isoamyl alcohol extractions. Only the kit binding (Solution MR), wash (ethanol, Solution PW) and spin columns are used, on a vacuum manifold. DNA eluted in 80 uL 0.1x TE after 45 min at 37 degC.
dna_cleanup_0_1: 0
dna_cleanup_method: not applicable
concentration: not applicable # recorded per sample
concentration_method: Invitrogen Qubit Flex Fluorometer with Qubit 1X dsDNA HS Assay Kit
ratioOfAbsorbance260_280: not applicable
pool_dna_num: not applicable
nucl_acid_ext_method_additional: not applicable
---

# IMOS NRS DNA Extraction Protocol: Sterivex Filters (PowerWater with Phenol:Chloroform)

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
| Sharon Appleyard | | | yyyy-mm-dd |
| [Name] | [Affiliation] | [ORCID] | yyyy-mm-dd |

<!-- TODO: confirm author list, affiliations and ORCIDs. Sharon Appleyard is credited with the modifications in the 2016 AMMBI SOP. -->

### Related Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ---- | ------- | ------------ | ----------------- |
| IMOS NRS Seawater eDNA Sampling Protocol (Sterivex) | [IMOS_NRS_eDNA_Sampling_Protocol_Water_Sterivex.md](IMOS_NRS_eDNA_Sampling_Protocol_Water_Sterivex.md) | 0.1.0 | yyyy-mm-dd | Internal |
| SOP for AMMBI Pilot Project: DNA Extraction Protocol for Sterivex Samples (modified by S. Appleyard) | Pelagic_sampling_SOP_16122016.pdf | — | 2016-12-16 | Internal |
| National Reference Stations Biogeochemical Operations Manual (section 9.6) | <https://doi.org/10.26198/5c4a56f2a8ae3> | 5 | 2025-09 | Internal |
| Australian Microbiome Scientific Manual | <https://research.csiro.au/ambsm/> | — | — | Internal |
| DNeasy PowerWater Sterivex Kit Handbook | <https://www.qiagen.com> | — | — | External |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------- | ------------ | ------------------------ |
| 0.1.0 | yyyy-mm-dd | Draft: Nov 2026 Sterivex DNA extraction protocol converted to BeBOP format; duplicated step numbers corrected and chloroform steps clarified |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ---------------------- | ---------- |
| AMMBI | Australian Marine Microbial Biodiversity Initiative (precursor to the IMOS Marine Microbiome Initiative) |
| CI | Chloroform:isoamyl alcohol (24:1) |
| CTAB | Cetyltrimethylammonium bromide (hexadecyltrimethylammonium bromide) |
| IMOS | Integrated Marine Observing System |
| MMI | Marine Microbiome Initiative |
| NRS | National Reference Station(s) |
| PCI | Phenol:chloroform:isoamyl alcohol (25:24:1) |
| PPE | Personal protective equipment |
| PVP | Polyvinylpyrrolidone |
| RT | Room temperature |
| TE | Tris-EDTA buffer |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ---------------- | ---------- |
| Sterivex | Enclosed cartridge filter unit (Millipore Sterivex GP, 0.22 µm polyethersulfone membrane) with luer inlet and outlet |
| Horizontal vortexer | Vortex-Genie fitted with an adapter that holds Sterivex cartridges horizontally for in-housing lysis |
| Aqueous phase | Upper, water-based layer after phenol or chloroform extraction and centrifugation; contains the DNA |
| Filtration blank | Field control: 2 L of MilliQ water filtered through a Sterivex at the station; extracted alongside the samples |

## BACKGROUND

This document describes the protocol used by the CSIRO Marine Microbiome Initiative Facility to extract DNA from Sterivex filters collected at the IMOS National Reference Stations.

### Summary

DNA is extracted from whole 0.22 µm Sterivex filters (2 L seawater each). Lysis takes place inside the Sterivex housing with a CTAB/lysozyme buffer and MT buffer on a horizontal vortexer. The lysate is purified with phenol:chloroform:isoamyl alcohol, digested with proteinase K, extracted twice with chloroform:isoamyl alcohol and bound to silica spin columns from the Qiagen DNeasy PowerWater Sterivex Kit on a vacuum manifold. DNA is eluted in 80 µL 0.1x TE and quantified. An aliquot is sent to the Ramaciotti Centre for Genomics (UNSW Sydney) for sequencing as part of the Australian Microbiome, and the remainder is archived at −80 °C.

### Method Description and Rationale

Lysis inside the Sterivex housing avoids cutting the membrane out. Lysozyme and the CTAB/PVP buffer break down cell walls and bind polysaccharides and polyphenols, and horizontal vortexing with MT buffer adds mechanical disruption. Phenol:chloroform and chloroform:isoamyl extractions remove proteins and lipids, and proteinase K digests remaining proteins. The kit's silica columns provide a final purification. This modified method has been used consistently for the AMMBI/IMOS NRS time series since its inception (Brown et al. 2018), which keeps the long-term record comparable.

### Spatial Coverage and Environment(s) of Relevance

The protocol is applied to seawater samples from the IMOS National Reference Stations around Australia (Darwin, Yongala, Rottnest Island, North Stradbroke Island, Maria Island, Bonney Mooring, Kangaroo Island and Port Hacking 100). Environments: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], sea water [ENVO:00002149].

## PERSONNEL REQUIRED

- 1 laboratory technician.

### Safety

- Phenol and chloroform are toxic and corrosive. Handle them only in a fume hood, wearing a lab coat, safety glasses and gloves rated for phenol/chloroform.
- Dispose of organic waste as hazardous waste.
- Lysozyme and proteinase K can cause sensitisation, so avoid inhaling the powder.
- Sodium hydroxide (10 M) used in lysis buffer preparation is corrosive.

### Training Requirements

- Molecular laboratory technique, pipetting and use of a vacuum manifold.
- Training in phenol/chloroform handling and the fume hood.

### Time Needed to Execute the Procedure

- Lysis buffer preparation: allow 1 day (autoclaving stock solutions).
- Extraction: about 6 h for a batch of 12 filters, including 1 h lysis, 2 h proteinase K incubation and 45 min elution incubation.

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ----------- | ---------------------- | ------------ | -------- | ------ |
| **Durable equipment** | | | | |
| Horizontal vortexer | Vortex-Genie (Z258431) with vortex adapter (13000-V1-5) for Sterivex filters | Merck; Qiagen | 2 | 6 Sterivex per vortexer; 12 samples per batch |
| Heat block | For 2 mL microcentrifuge tubes | — | 1 | Set to 60 °C (the Nov 2026 source lists 56 °C; see Troubleshooting) |
| Oven or incubator | — | — | 1 | 65 °C (Solution MR) and 37 °C (elution) |
| Microcentrifuge | — | — | 1 | ≥13,000 rpm |
| Fume hood | — | — | 1 | For all PCI and CI steps |
| Vacuum manifold | QIAvac 24 Plus (19403) | Qiagen | 1 | |
| Vacuum pump or vacuum line | — | — | 1 | |
| Orbital shaker | — | — | 1 | To dissolve lysozyme |
| Fluorometer | Qubit Flex | Invitrogen | 1 | |
| **Consumable equipment** | | | | |
| Syringes | 3 mL (kit) | Qiagen | 1 per sample | To expel lysate from Sterivex |
| Microcentrifuge tubes | 2.0 mL, PCI-tolerant | — | ~6 per sample | Do not use the kit's 2 mL collection tubes for PCI steps |
| 5 mL tubes | Kit | Qiagen | 1 per sample | |
| Spin columns and tube extenders | Kit | Qiagen | 1 per sample | |
| Falcon tube | 50 mL | — | 1 per batch | For lysis buffer with lysozyme |
| Gloves | Phenol/chloroform-rated | — | — | |
| Qubit assay tubes | — | Invitrogen | 1 per sample + standards | |
| **Chemicals** | | | | |
| Lysis buffer | In-house CTAB/PVP sodium phosphate buffer, pH 7.0 | — | 25 mL per batch | See Lysis buffer preparation |
| Lysozyme | CAS 12650-88-3 | Thermo Scientific | 125 mg per batch | Final concentration 5 mg/mL |
| MT buffer | From FastDNA Spin Kit for Soil | MP Biomedicals | 0.125 mL per sample | |
| Proteinase K | 20 mg/mL | Roche | 20 µL per sample | |
| Phenol:chloroform:isoamyl alcohol | 25:24:1 (PCI) | Sigma-Aldrich | 1.8 mL per sample | |
| Chloroform:isoamyl alcohol | 24:1 (CI) | Sigma-Aldrich | 1.5 mL per sample | |
| DNeasy PowerWater Sterivex Kit (50) | 14600-50-NF | Qiagen | 1 kit per 50 samples | Solution MR (warm to 65 °C), ethanol and Solution PW, columns, syringes, tubes |
| TE buffer | 1x, molecular biology grade | Promega | — | Dilute to 0.1x with nuclease-free water for elution |
| Qubit 1X dsDNA HS Assay Kit | Q33231 | Invitrogen | 1 per batch | |
| Sodium phosphate monobasic dihydrate | NaH₂PO₄·2H₂O, CAS 13472-35-0 | Sigma-Aldrich | — | Lysis buffer |
| Sodium phosphate dibasic | Na₂HPO₄, CAS 7558-79-4 | Sigma-Aldrich | — | Lysis buffer |
| Sodium chloride | NaCl | — | 17.54 g per 200 mL | Lysis buffer |
| CTAB | Hexadecyltrimethylammonium bromide, CAS 57-09-0 | Sigma-Aldrich | 2 g per 200 mL | Lysis buffer |
| PVP K30 | Polyvinylpyrrolidone, CAS 9003-39-8 | Sigma-Aldrich | 4 g per 200 mL | Lysis buffer |
| Sodium hydroxide | 10 M NaOH | — | ~1 mL | pH adjustment |
| MilliQ water | — | — | — | |

## STANDARD OPERATING PROCEDURE

In the following SOP, the equipment names are those used in the table above. The method processes 12 filters per batch (2 horizontal vortexers × 6 Sterivex). Include each station's MilliQ filtration blank in the same batch as that station's samples.

### Preparation

**Lysis buffer (allow 1 day)**

1. Prepare and autoclave the following stock solutions:
   - 200 mM sodium phosphate monobasic dihydrate (NaH₂PO₄·2H₂O, MW 156.01)
   - 200 mM sodium phosphate dibasic (Na₂HPO₄, MW 141.96)
2. To make 200 mL of lysis buffer, combine:
   - 39 mL 200 mM NaH₂PO₄·2H₂O
   - 61 mL 200 mM Na₂HPO₄
   - 17.54 g NaCl
   - 2 g CTAB
   - 4 g PVP K30
3. Make up to 200 mL with MilliQ water.
4. Adjust to pH 7.0 with NaOH (start with about 1 mL of 10 M NaOH).

**Extraction day**

1. Weigh 125 mg lysozyme into a 50 mL Falcon tube and add 25 mL lysis buffer (final lysozyme concentration 5 mg/mL). Dissolve by gentle shaking on an orbital shaker.
2. Set the heat block to 60 °C and the oven to 65 °C.
3. Prepare 0.1x TE from 1x TE buffer.
4. Make sure the fume hood is available and phenol/chloroform waste containers are ready.

### Extraction

**Lysis**

1. Remove the Sterivex filters from −80 °C and take off the inlet cap. If a filter contains RNAlater, push it out with back pressure from a 3 mL syringe.
2. Using a pipette, add 1.875 mL lysis buffer (containing 5 mg/mL lysozyme) and 0.125 mL MT buffer through the inlet.
3. Recap the Sterivex and attach it to the horizontal vortexer with the inlet end facing out. Vortex at speed 5–7 for 60 min, turning the filter a couple of times during the hour.
4. Draw back the plunger of a 3 mL syringe, attach the syringe to the inlet end and push until pressure builds. Release the plunger so the buffer flows from the filter into the syringe. Repeat as needed to recover all of the ~2 mL of lysate.
5. Divide the lysate evenly between two 2.0 mL PCI-tolerant tubes (about 0.8–1.0 mL each). Do not use the kit's 2 mL collection tubes, which do not tolerate PCI.

**Phenol:chloroform extraction and proteinase K digestion**

6. In the fume hood, add 900 µL PCI to each tube. Invert several times and centrifuge at 13,000 rpm for 10 min at RT.
7. Combine the aqueous (upper) phases from both tubes in one new 2.0 mL tube (1.2–1.5 mL in total). Add 20 µL proteinase K and incubate on the heat block at 60 °C for 2 h.
8. During this incubation, set up the vacuum manifold: attach the spin columns to the VacValves and push a tube extender firmly into each column.
9. After incubation, divide each sample evenly between two new 2.0 mL tubes.
10. In the fume hood, add 500 µL CI to each tube. Invert several times and centrifuge at 13,000 rpm for 10 min at RT.
11. Transfer the aqueous phases from both tubes of each sample into one new 2.0 mL tube.
12. In the fume hood, add 500 µL CI to the pooled aqueous phase. Invert several times and centrifuge at 13,000 rpm for 5 min at RT.
13. During this spin, put Solution MR in the 65 °C oven. It needs at least 10 min at 65 °C before use.

**Column binding, washing and elution**

14. Transfer 1 mL of the aqueous phase to a 5 mL tube (kit).
15. Add 3 mL of warm Solution MR (65 °C) and mix by inversion.
16. While still warm, pour the contents of the 5 mL tube into the tube extender and spin column on the manifold.
17. Apply vacuum to pull the liquid through the column.
18. Keeping the column on the manifold, remove the tube extender and add 800 µL ethanol to the column. Apply vacuum to pull it through.
19. Add 800 µL Solution PW to the column. Apply vacuum to pull it through, then leave the vacuum on for another 2 min.
20. Turn off the vacuum, place the column in a new 2.0 mL tube and air dry on the bench for 10 min.
21. Add 80 µL 0.1x TE to the centre of the membrane and incubate at 37 °C for 45 min.
22. Centrifuge the column and tube at 13,000 rpm for 2 min at RT to elute the DNA.

### Quantification and Storage

1. Measure DNA concentration with the Qubit Flex and the Qubit 1X dsDNA HS Assay Kit, following the manufacturer's instructions. Record results in the sample log.
2. Send an aliquot of each extract to the Ramaciotti Centre for Genomics (UNSW Sydney) for sequencing under the Australian Microbiome. <!-- TODO: aliquot volume and plate format -->
3. Archive the remaining extract at −80 °C.

### Quality Control

- **Field filtration blanks:** each station's 2 L MilliQ filtration blank is extracted in the same batch as its samples and carried through to sequencing.
- **Extraction controls:** <!-- TODO: state whether extraction blanks (reagent-only) and/or positive controls are included per batch --> Not specified in the source protocol.
- **DNA yield:** DNA concentration is recorded for every extract. Filtration blanks are expected to have DNA below or near the assay's detection limit.

### Basic Troubleshooting Guide

- **Low DNA yield.** Check that the filter was pumped dry before freezing, the lysozyme was freshly dissolved, Solution MR was at 65 °C when added, and all the lysate was recovered from the Sterivex.
- **Phase carry-over.** Take the aqueous phase without touching the interphase. If in doubt, leave some aqueous phase behind rather than carrying over organic phase, which inhibits downstream PCR.
- **Tube volume at step 12.** The pooled aqueous phase (up to ~1.5 mL) plus 500 µL CI can exceed the 2.0 mL tube volume. If so, split the sample across two tubes for this step as well.
- **Proteinase K temperature.** The Nov 2026 source protocol gives 60 °C in the method but lists a 56 °C heat block under equipment. This protocol uses 60 °C, as in the method steps and the 2016 SOP. <!-- TODO: confirm -->
- **Capacity.** Throughput is limited by the horizontal vortexers (6 Sterivex each).

## REFERENCES

- Brown, M., van de Kamp, J., Ostrowski, M., Seymour, J., Ingleton, T., Messer, L., et al. (2018). Systematic, continental scale temporal monitoring of marine pelagic microbiota by the Australian Marine Microbial Biodiversity Initiative. *Scientific Data*, 5, 180130. <https://doi.org/10.1038/sdata.2018.130>
- Davies, C. (Ed.) (2025). *National Reference Stations Biogeochemical Operations Manual*, Version 5. Integrated Marine Observing System. <https://doi.org/10.26198/5c4a56f2a8ae3>
- Qiagen. *DNeasy PowerWater Sterivex Kit Handbook*.
- Australian Microbiome Scientific Manual. <https://research.csiro.au/ambsm/>

## APPENDIX A: DATASHEETS

- **MMI sample log (Hobart):** records sample receipt, storage location, extraction batch and DNA concentration. <!-- TODO: link -->
