---
# MIOP terms
methodology_category: sample collection
project: Integrated Marine Observing System (IMOS) National Reference Stations (NRS) - Marine Microbiome Initiative; Australian Microbiome (https://www.australianmicrobiome.com/)
purpose: biodiversity assessment objective [OBI:0001969], time series design [OBI:0500020]
analyses: environmental material collection process [OBI:0600012], filtration [OBI:0302885]
geographic_location: Australia:Beagle Gulf [GAZ:00051048], Australia:Great Australian Bight [GAZ:00045604], Australia:Tasman Sea coastal waters of continental Australia [GAZ:00143737], Australia:Moreton Bay Marine Park [GAZ:00088305], Australia:East Australian Current [GAZ:00000352], Australia:Eastern Indian Ocean coastal waters of Western Australia [GAZ:00051147], Australia:Great Barrier Reef Marine Park [GAZ:00049080] # TODO: GAZ term for Bonney Coast (VBM) not yet identified
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149]
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: # names separated by commas
materials_required: Niskin bottle, peristaltic pump, filtration [OBI:0302885]
skills_required: sterile technique, small vessel field sampling experience
time_required: # TODO: minutes (integer) for sampling and filtration of one station visit
personnel_required: 1
language: en
issued: # YYYY-MM-DD
audience: scientists
publisher: Integrated Marine Observing System (IMOS); CSIRO Environment, Marine Microbiome Initiative Facility, Hobart
hasVersion: 0.1.0
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
samp_category: sample
env_broad_scale: marine biome [ENVO:00000447]
env_local_scale: marine photic zone [ENVO:00000209]
env_medium: sea water [ENVO:00002149]
habitat_natural_artificial_0_1: 0
samp_collect_method: Niskin bottle cast from small vessel to pre-determined depths (2-4 depths per station)
samp_collect_device: Niskin bottle (5 L)
samp_size: 2000 # volume filtered; record actual volume if filter blocks
samp_size_unit: mL
samp_store_temp: -80
samp_store_sol: not applicable # filters stored dry
samp_mat_process: Seawater from each depth was transferred to a rinsed ~4 L container (>=3 L) and kept on ice in the dark. On shore, 2 L was filtered through a Sterivex GP 0.22 um filter using a peristaltic pump (~200 mL/min); the filter was pumped dry for ~1 min, capped and stored at -80 degC. A 2 L MilliQ water filtration blank was processed in parallel.
filter_passive_active_0_1: 1
prefilter_material: not applicable
size_frac_low: not applicable
size_frac: 0.22
filter_diameter: not applicable # Sterivex cartridge
filter_material: polyethersulfone
---

# IMOS NRS Seawater eDNA Sampling Protocol (Sterivex)

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
| Dion Frampton | CSIRO | | 2015-05 |
| Jodie van de Kamp | CSIRO | | 2019-08 |
| Bronwyn Holmes | CSIRO | | 2025-09 |
| [Name] | [Affiliation] | [ORCID] | yyyy-mm-dd |

<!-- TODO: confirm author list, affiliations and ORCIDs. Names above are those credited for the microbial sampling protocol in the NRS BGC Operations Manual v5 (section 6.7). -->

### Related Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ---- | ------- | ------------ | ----------------- |
| IMOS NRS DNA Extraction Protocol: Sterivex Filters (PowerWater with phenol:chloroform) | [IMOS_NRS_DNA_Extraction_Protocol_Sterivex_PowerWater-PCI.md](IMOS_NRS_DNA_Extraction_Protocol_Sterivex_PowerWater-PCI.md) | 0.1.0 | yyyy-mm-dd | Internal |
| National Reference Stations Biogeochemical Operations Manual (sections 5.5, 5.5.10, 6.7, 6.8, 6.10, 7.2) | <https://doi.org/10.26198/5c4a56f2a8ae3> | 5 | 2025-09 | Internal |
| Transport Contact Details NRS Sampling | IMOS_NRS_BGC TransportContactDetailsNRSSampling_Sept25.pdf | — | 2025-09 | Internal |
| Australian Microbiome Scientific Manual | <https://research.csiro.au/ambsm/> | — | — | Internal |
| GO-SHIP Repeat Hydrography Manual | Hood et al. (2010) | 1 | 2010 | External |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------- | ------------ | ------------------------ |
| 0.1.0 | yyyy-mm-dd | Draft: NRS BGC Manual v5 microbial sampling and filtration converted to BeBOP format |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ---------------------- | ---------- |
| AMMBI | Australian Marine Microbial Biodiversity Initiative (precursor to the IMOS Marine Microbiome Initiative) |
| BGC | Biogeochemical |
| eDNA | Environmental DNA |
| IMOS | Integrated Marine Observing System |
| LN2 | Liquid nitrogen |
| MMI | Marine Microbiome Initiative |
| NRS | National Reference Station(s) |
| DAR, YON, ROT, NSI, MAI, VBM, KAI, PHB | NRS codes: Darwin, Yongala, Rottnest Island, North Stradbroke Island, Maria Island, Bonney Mooring, Kangaroo Island, Port Hacking 100 |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ---------------- | ---------- |
| Niskin bottle | Water sampling bottle closed at depth by a messenger, used to collect seawater from discrete depths |
| Sterivex | Enclosed cartridge filter unit (Millipore Sterivex GP, 0.22 µm polyethersulfone membrane) with luer inlet and outlet |
| Filtration blank | Field control: 2 L of MilliQ water filtered through a Sterivex with the same tubing and handling as the seawater samples |

## BACKGROUND

This document describes the protocol used by IMOS National Reference Stations (NRS) to collect, filter and store seawater for microbial (including phytoplankton) genomics.

### Summary

Seawater is collected monthly at each NRS with Niskin bottles at 2–4 fixed depths. On return to shore, 2 L from each depth is filtered through a 0.22 µm Sterivex filter with a peristaltic pump, alongside a 2 L MilliQ filtration blank. Filters are stored at −80 °C and transported frozen to the CSIRO Marine Microbiome Initiative Facility, Hobart, for DNA extraction (see Related Protocols) and sequencing as part of the Australian Microbiome. The protocol applies to coastal and shelf waters around Australia and targets prokaryotic and eukaryotic microbial communities.

### Method Description and Rationale

Microbial cells are captured on a 0.22 µm membrane, which retains most bacteria, archaea and protists. Filtering a fixed 2 L volume with a closed Sterivex cartridge limits contamination and makes samples comparable across stations and over time. Pumping the filter dry before freezing removes residual seawater that interferes with downstream DNA extraction. The method has been used consistently for the AMMBI/IMOS NRS time series (Brown et al. 2018), which keeps the long-term record comparable.

### Spatial Coverage and Environment(s) of Relevance

The protocol is applied at the IMOS National Reference Stations around Australia:

| SITE | CODE | NOMINAL DEPTH | LONGITUDE | LATITUDE | MICROBIAL SAMPLING DEPTHS (m) |
| ---- | ---- | ------------- | --------- | -------- | ----------------------------- |
| Darwin | DAR | 20 m | 130.7827 | −12.417467 | 0, 17 |
| Yongala | YON | 29 m | 147.26 | −19.306 | 0, 20, 26 |
| Rottnest Island | ROT | 50 m | 115.41667 | −32 | 0, 20 |
| North Stradbroke Island | NSI | 60 m | 153.58022 | −27.388917 | 0, 20 |
| Maria Island | MAI | 90 m | 148.23333 | −42.596667 | 0, 20, 50, 85 |
| Bonney Mooring | VBM | 100 m | 141.271 | −38.4086 | 0, 20, 50, 85 |
| Kangaroo Island | KAI | 110 m | 136.448 | −35.836 | 0, 20, 50, 100 |
| Port Hacking 100 | PHB | 100 m | 151.25 | −34.083333 | 0, 25, 50, 100 |

Depths are those in use since 1 January 2025. Environments: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209], sea water [ENVO:00002149].

## PERSONNEL REQUIRED

- Field sampling: NRS field team (at least 2 people for small boat operations, as required by each operator's risk assessment). <!-- TODO: confirm minimum field crew -->
- Filtration: 1 technician.

### Safety

- Each station completes a risk assessment before any sampling trip.
- **Field:** follow vessel safety procedures. Carry laminated mini-MSDS sheets for all hazardous materials on board.
- **Filtration:** 5–10% bleach is corrosive and 70% ethanol is flammable. Wear gloves and eye protection.
- **Cryogenics:** if liquid nitrogen or a dry shipper is used for storage or transport, wear cryo-gloves and a face shield and work in a well-ventilated area (NRS BGC Manual section 6.9).

### Training Requirements

- Small vessel operations and Niskin bottle deployment.
- Sterile handling of filters and peristaltic pump operation.

### Time Needed to Execute the Procedure

- Sampling: one Niskin cast per depth, carried out as the last activity on station. <!-- TODO: add typical time -->
- Filtration: about 10–15 min per 2 L sample at ~200 mL/min, plus tubing flushes and cleaning. <!-- TODO: confirm -->

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ----------- | ---------------------- | ------------ | -------- | ------ |
| **Durable equipment** | | | | |
| Niskin bottle | 5 L Niskin bottle with bronze messengers | — | 1 per depth | Leak test before sampling (NRS BGC Manual 5.5.1) |
| Peristaltic pump | Pump, pump head and tubing with Sterivex luer attachment | — | 1 | New tubing supplied annually by the MMI team |
| Volumetric cylinders or bottles | 2 L plastic | — | 1 per depth + 1 for blank | |
| Seawater containers | Plastic, dark or covered, ~4 L | — | 2–4 (1 per depth) | Label with depth |
| Funnel | Plastic, fits seawater containers | — | 1 | |
| Esky | Large | — | 1 | With ice |
| **Consumable equipment** | | | | |
| Sterivex filter | Sterivex GP 0.22 µm (SVGPL10RC) | Millipore | 1 per depth + 1 for blank | With inlet and outlet caps |
| Snap-lock bags | Large (holds up to 4 Sterivex) | — | 1 per station | Labelled "NRS samples", station, date. Small individual bags only if caps run out |
| Cryo marker pen | — | — | 1 | Withstands −80 °C and LN2 |
| Gloves | Single-use laboratory gloves (e.g. latex) | — | — | |
| Ice | — | — | — | |
| **Chemicals** | | | | |
| MilliQ or deionised water | — | — | 2 L per station | Filtration blank |
| Bleach | 5–10% | — | 200 mL per pump line | Tubing cleaning |
| Ethanol | 70% | — | 200 mL per pump line | Tubing cleaning |

## STANDARD OPERATING PROCEDURE

In the following SOP, the equipment names are those used in the table above.

### Preparation

1. Complete the station risk assessment and the gear checklist (NRS BGC Manual section 5).
2. Check that enough Sterivex filters are available (one per depth plus one blank), along with caps, labelled snap-lock bags, cryo marker pens and gloves.
3. Leak test each Niskin bottle before sampling (NRS BGC Manual 5.5.1): with the top valve closed, open the spigot and check for flow. Record any leak on the field log sheet.
4. Prepare 2 L of MilliQ water in a clean 2 L volumetric cylinder for the filtration blank.

### Sampling

1. Conduct Niskin bottle casts to the station's pre-determined depths (2–4 depths; see Spatial Coverage). Make this cast as close as possible to the last activity on station.
2. For each depth, rinse the funnel and the seawater container (labelled with that depth) with ~0.5 L of the retrieved seawater and discard the rinse.
3. Fill the container with at least 3 L of seawater. Repeat for every depth.
4. Keep the containers in an esky surrounded by ice and, where possible, out of direct sunlight to minimise temperature changes before filtration.
5. Record station, date, time and depths on the field log sheet.

### Filtration

Wear gloves at all times during filtration and when handling Sterivex filters.

1. Fill a 2 L volumetric cylinder with seawater from each depth and label the cylinders by depth. Fill another cylinder with 2 L of MilliQ water for the filtration blank.
2. Place one end of the tubing in a cylinder and run the tubing through the pump head, with the luer fitting attached at the outlet end but no Sterivex yet.
3. Flush ~200 mL of sample (or MilliQ water for the blank) through the tubing at about 200 mL/min on older pumps, or 300 rpm on newer pumps.
4. Lift the tubing out of the cylinder, holding it in the air without touching any surface, and let the pump empty the tubing completely.
5. Put the tubing back in the cylinder and top the cylinder up to exactly 2 L with water from the same depth (or MilliQ water for the blank).
6. Label each Sterivex with station, depth and date, e.g. `MAI_0M_16052024`.
7. Attach the Sterivex to the luer fitting in the correct flow orientation, without touching the luer end.
8. Pump 2 L through the filter, measured by the cylinder emptying. If the filter blocks before 2 L has passed, stop the pump and record the actual volume filtered on the field log sheet and on the Sterivex (see Troubleshooting).
9. Once 2 L has passed, keep the pump running for ~1 min to dry the filter. Removing all remaining water from the filter housing is critical, because residual water interferes with DNA extraction.
10. Disconnect the filter from the tubing and flick it several times to remove as much residual water from the housing as possible.
11. Repeat steps 2–10 for each depth and for the MilliQ blank.

### Sample Preservation

1. Cap both ends of each filter with the inlet and outlet caps. Use individual snap-lock bags only if no caps are available.
2. Put the capped filters from one station into a larger snap-lock bag labelled "NRS samples", station and date.
3. Keep the bag on ice in the dark until it can be frozen.

### Storage

1. Store the filters at −80 °C as soon as possible after processing.
2. Ship the filters frozen to the CSIRO Marine Microbiome Initiative Facility, Hobart, following the current *Transport Contact Details NRS Sampling* document. Send them as soon as possible so analysis can be completed within the six-month IMOS reporting deadline.
3. On arrival in Hobart, log the filters and store them at −80 °C until extraction.

### Sampling Equipment Cleaning

1. **Pump tubing:** run 200 mL of 5–10% bleach through each line and leave it in the tubing for 10 min before pumping it out. Follow with 3 × 200 mL MilliQ or distilled water rinses per line, then 200 mL of 70% ethanol to dry the tubing and prevent biofilm growth. Make sure all the ethanol has passed through.
2. **Niskin bottles:** at the end of each trip, rinse inside and out with fresh water while cocked open. Leave to dry in a clean place for about 3 days before closing.
3. **Messengers:** wash with fresh water and store somewhere open and airy so they dry completely.

### Quality Control

- **Field filtration blank:** since 1 January 2025, one 2 L MilliQ water blank is filtered per station visit with the same tubing, pump and handling as the samples. It is extracted and sequenced with the samples to detect contamination introduced during sampling, filtration and extraction.
- **Niskin leak test:** any leak is recorded on the field log sheet.
- **Volume filtered:** the actual volume is recorded for every filter. Volumes under 2 L are noted on the filter and the field log.
- **Filter dryness:** filters are pumped dry and flicked before capping. Water left in the housing reduces extraction efficiency.
- **Cold chain:** samples are kept on ice in the dark until frozen, and shipped frozen.

### Basic Troubleshooting Guide

- **Blocked Sterivex filters.** These are more common in turbid water or during blooms.
  - Watch the outlet: a change from a steady stream to a slow drip means the filter is starting to block.
  - Take the intake line out of the cylinder so excess water can drain from the filter.
  - If water still will not drain, try lowering the pump speed. **Do not** increase the flow rate: this can exceed the Sterivex pressure limit and break the filter or housing.
  - Record the actual volume filtered.
- **Degraded or dirty pump tubing.** Ask the MMI team for new tubing. Direct questions about pump heads, batteries and faults to the Marine Microbiome team.
- **Leaking Niskin bottle.** Record it on the field log sheet. <!-- TODO: state whether the sample is retained or re-collected -->

## REFERENCES

- Brown, M., van de Kamp, J., Ostrowski, M., Seymour, J., Ingleton, T., Messer, L., et al. (2018). Systematic, continental scale temporal monitoring of marine pelagic microbiota by the Australian Marine Microbial Biodiversity Initiative. *Scientific Data*, 5, 180130. <https://doi.org/10.1038/sdata.2018.130>
- Davies, C. (Ed.) (2025). *National Reference Stations Biogeochemical Operations Manual*, Version 5. Integrated Marine Observing System. <https://doi.org/10.26198/5c4a56f2a8ae3>
- Hood, E.M., Sabine, C.L., & Sloyan, B.M. (Eds.) (2010). *The GO-SHIP Repeat Hydrography Manual: A Collection of Expert Reports and Guidelines*, Version 1. IOCCP Report 14, ICPO Publication Series 134.

## APPENDIX A: DATASHEETS

- **NRS field log sheet:** records station, date, time, depths, Niskin leak tests and volume filtered per Sterivex.
- **NRS filter sheet:** records filtration details per sample.
- **Transport Contact Details NRS Sampling (Sept 2025):** shipping addresses and contacts for frozen genomics samples.
- **Video demonstrations of NRS post-sampling procedures:** <https://www.youtube.com/channel/UCXp5vxj2TaCatkura7vMYOA>
