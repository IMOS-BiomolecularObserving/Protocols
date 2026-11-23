---
# MIOP terms
methodology_category: sample collection
project: Integrated Marine Observing System (IMOS) National Reference Stations (NRS) - zooplankton genomics (Zoogen); Australian Microbiome (https://www.australianmicrobiome.com/)
purpose: biodiversity assessment objective [OBI:0001969], time series design [OBI:0500020]
analyses: environmental material collection process [OBI:0600012]
geographic_location: Australia:Beagle Gulf [GAZ:00051048], Australia:Great Australian Bight [GAZ:00045604], Australia:Tasman Sea coastal waters of continental Australia [GAZ:00143737], Australia:Moreton Bay Marine Park [GAZ:00088305], Australia:East Australian Current [GAZ:00000352], Australia:Eastern Indian Ocean coastal waters of Western Australia [GAZ:00051147], Australia:Great Barrier Reef Marine Park [GAZ:00049080] # TODO: GAZ term for Bonney Coast (VBM) not yet identified
broad_scale_environmental_context: marine biome [ENVO:00000447]
local_environmental_context: marine photic zone [ENVO:00000209]
environmental_medium: sea water [ENVO:00002149] # TODO: consider a more specific ENVO material term for bulk zooplankton
target: deoxyribonucleic acid (DNA) [NCIT:C449], environmental DNA [NCIT:C169106]
creator: # names separated by commas
materials_required: zooplankton drop net, fine mesh screen
skills_required: sterile technique, small vessel field sampling experience
time_required: # TODO: minutes (integer) for sampling and on-shore processing
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
env_medium: sea water [ENVO:00002149] # TODO: see environmental_medium above
habitat_natural_artificial_0_1: 0
samp_collect_method: Vertical free-fall drop net from surface to a timed depth (~1.0 m/s); the third of three drops is kept unpreserved for genomics
samp_collect_device: Zooplankton drop net with steel collar and cod end
samp_size: "missing: not provided" # TODO: net mouth area x drop depth (volume filtered), if available
samp_size_unit: "missing: not provided"
samp_store_temp: -80
samp_store_sol: not applicable # frozen without preservative
samp_mat_process: The net contents were washed into the cod end with seawater and kept on ice in a black jar. On shore, the sample was poured through a pre-wetted fine mesh screen, rinsed lightly with site seawater, scraped off the mesh with a bleach-cleaned metal spatula, drained of as much water as possible and placed into a 5 mL cryovial (max. two-thirds full), then stored at -80 degC.
filter_passive_active_0_1: 0 # passive net filtration
prefilter_material: not applicable
size_frac_low: "missing: not provided" # TODO: drop net mesh size (um)
size_frac: not applicable
filter_diameter: not applicable
filter_material: not applicable
---

# IMOS NRS Bulk Plankton eDNA Sampling Protocol (Drop Net)

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

<!-- TODO: add authors. Sampling follows the NRS BGC Operations Manual v5 (ed. C. Davies). -->

### Related Protocols

| PROTOCOL NAME | LINK | VERSION | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ---- | ------- | ------------ | ----------------- |
| IMOS NRS DNA Extraction Protocol: Bulk Plankton (DNeasy Blood & Tissue) | [IMOS_NRS_DNA_Extraction_Protocol_BulkPlankton_BloodTissue.md](IMOS_NRS_DNA_Extraction_Protocol_BulkPlankton_BloodTissue.md) | 0.1.0 | yyyy-mm-dd | Internal |
| National Reference Stations Biogeochemical Operations Manual (sections 5.4, 6.6, 6.8, 6.10, 7.1) | <https://doi.org/10.26198/5c4a56f2a8ae3> | 5 | 2025-09 | Internal |
| Set up of Zooplankton Drop net (NRS documentation) | — | — | — | Internal |
| Transport Contact Details NRS Sampling | IMOS_NRS_BGC TransportContactDetailsNRSSampling_Sept25.pdf | — | 2025-09 | Internal |

### Protocol Revision Record

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------- | ------------ | ------------------------ |
| 0.1.0 | yyyy-mm-dd | Draft: NRS BGC Manual v5 zooplankton sampling and genomics sample preparation converted to BeBOP format |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ---------------------- | ---------- |
| BGC | Biogeochemical |
| IMOS | Integrated Marine Observing System |
| LN2 | Liquid nitrogen |
| NRS | National Reference Station(s) |
| Zoogen | Zooplankton genomics sample: the unpreserved, frozen bulk zooplankton sample |
| DAR, YON, ROT, NSI, MAI, VBM, KAI, PHB | NRS codes: Darwin, Yongala, Rottnest Island, North Stradbroke Island, Maria Island, Bonney Mooring, Kangaroo Island, Port Hacking 100 |

### Glossary

| SPECIALISED TERM | DEFINITION |
| ---------------- | ---------- |
| Drop net | Weighted plankton net with a steel collar, dropped vertically in free fall and closed by hauling the rope once the target depth is reached |
| Cod end | Collecting container at the end of the plankton net |
| Bulk plankton | Whole mixed plankton community from a net haul, processed as a single sample |

## BACKGROUND

This document describes the protocol used by IMOS National Reference Stations (NRS) to collect, process and store bulk zooplankton for genomics.

### Summary

At each monthly NRS visit, three vertical drop-net hauls are made. Two are preserved in formalin for composition and biomass analysis (not covered here). The third is kept unpreserved on ice for genomics. On shore, the genomics sample is concentrated on a fine mesh, transferred to a 5 mL cryovial and frozen at −80 °C before being shipped frozen to the CSIRO Marine Microbiome Initiative Facility, Hobart, for DNA extraction (see Related Protocols).

### Method Description and Rationale

The drop net samples the water column from the surface down to a fixed depth, so it captures the integrated mesozooplankton community. Timing the free fall gives a consistent sampling depth on small vessels without a depth sensor. Freezing the sample unpreserved avoids formalin, which degrades DNA. Removing as much water as possible before freezing concentrates the biomass and avoids excess ice in the cryovial.

### Spatial Coverage and Environment(s) of Relevance

The protocol is applied at the IMOS National Reference Stations around Australia:

| SITE | CODE | NOMINAL DEPTH | LONGITUDE | LATITUDE |
| ---- | ---- | ------------- | --------- | -------- |
| Darwin | DAR | 20 m | 130.7827 | −12.417467 |
| Yongala | YON | 29 m | 147.26 | −19.306 |
| Rottnest Island | ROT | 50 m | 115.41667 | −32 |
| North Stradbroke Island | NSI | 60 m | 153.58022 | −27.388917 |
| Maria Island | MAI | 90 m | 148.23333 | −42.596667 |
| Bonney Mooring | VBM | 100 m | 141.271 | −38.4086 |
| Kangaroo Island | KAI | 110 m | 136.448 | −35.836 |
| Port Hacking 100 | PHB | 100 m | 151.25 | −34.083333 |

<!-- TODO: add the drop depth used at each station --> Environments: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209].

## PERSONNEL REQUIRED

- Field sampling: NRS field team (at least 2 people for small boat operations, as required by each operator's risk assessment). <!-- TODO: confirm -->
- On-shore sample processing: 1 technician.

### Safety

- Each station completes a risk assessment before any sampling trip.
- Follow vessel safety procedures for deploying and hauling the drop net.
- Formaldehyde (37%) is used on the two formalin replicates, though not on the genomics sample. It is toxic and carcinogenic, so carry the MSDS, wear gloves and eye protection, and work in a ventilated area.
- 10% bleach (for cleaning the spatula) is corrosive.

### Training Requirements

- Small vessel operations and drop net deployment.
- Clean handling of genomics samples, avoiding contact with organic material and cross-contamination.

### Time Needed to Execute the Procedure

- Sampling: about 1 min drop time per 50 m of depth plus hauling and rinsing, per haul. <!-- TODO: confirm -->
- On-shore processing: about 15 min per sample. <!-- TODO: confirm -->

## EQUIPMENT

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ----------- | ---------------------- | ------------ | -------- | ------ |
| **Durable equipment** | | | | |
| Zooplankton drop net | Drop net with steel collar and cod end | — | 1 | See *Set up of Zooplankton Drop net*. <!-- TODO: mouth diameter and mesh size --> |
| Rope | 12 mm silver rope | — | Length suited to station depth | |
| Stopwatch | — | — | 1 | Times the drop |
| Winch or pot hauler | — | — | 1 | |
| Esky | — | — | 1 | With ice |
| Fine mesh screen | — | — | 1 | For concentrating the sample on shore |
| Metal spatula | — | — | 1 | Cleaned with 10% bleach and rinsed with distilled or site water before use |
| Squirt bottle | — | — | 1 | Filled with site seawater |
| **Consumable equipment** | | | | |
| Black jar | Large, black plastic | — | 1 per station | For the genomics haul |
| Waterproof labels | — | — | 1 per sample | |
| Cryovial | 5 mL, external screw thread with silicone seal | — | 1 per station | |
| Cryo marker pen | — | — | 1 | Withstands −80 °C and LN2 |
| Gloves | Single-use laboratory gloves (e.g. latex) | — | — | |
| Paper towel | — | — | — | Helps draw water through gelatinous samples |
| Ice | — | — | — | |
| **Chemicals** | | | | |
| Bleach | 10% | — | — | Cleaning the metal spatula |
| Site seawater | — | — | — | Rinsing; e.g. water left over in the microbial sample containers after filtration |

## STANDARD OPERATING PROCEDURE

In the following SOP, the equipment names are those used in the table above.

### Preparation

1. Complete the station risk assessment and the gear checklist (NRS BGC Manual section 5).
2. Check the drop net, cod end and rope. Make sure the rope is long enough for the station depth.
3. Pack the large black jar, waterproof labels, stopwatch, ice and esky.
4. Before the first drop, wet the net thoroughly with the deck hose so it falls efficiently, and check that the cod end is attached.

### Sampling

1. Three samples are collected with the drop net at each station visit. The first two are preserved in formalin (composition and biomass). The **third** is kept unpreserved for genomics.
2. Lower the net over the side and let it free fall at about 1.0 m/s. Start the stopwatch as soon as the collar hits the water. Time the drop to the required depth (e.g. 50 m = 50 s).
3. When the time is reached, haul on the rope to close the net.
4. Haul the net on deck with a winch or pot hauler. The net is no longer sampling, so hauling speed does not matter.
5. Wash the net contents into the cod end with seawater from the deck hose. Reduce the volume in the cod end as much as possible.
6. Record the time, drop time and site code on a waterproof label and on the field sheet.

### Sample Preservation

1. For the third (genomics) haul, empty the cod end into the large black jar. **Do not add formalin.**
2. Label the jar on the outside with site and date, and put a waterproof label inside with date, time of drop and site.
3. Keep the black jar on ice in the esky until processing on shore.

### On-Shore Sample Processing

Wear gloves at all times when handling the genomics sample, the fine mesh and the cryovials.

1. Label a 5 mL cryovial with the cryo marker pen, following the NRS sample coding.
2. Pre-wet the fine mesh screen with site seawater. You can use water left over in the microbial sample containers after filtration.
3. Pour the chilled black-jar sample through the fine mesh screen. Use the squirt bottle of seawater to concentrate the sample to one side.
4. Rinse lightly with seawater and scrape the sample off the mesh with the cleaned metal spatula, avoiding contact with any other organic material. Repeat the light rinsing and scraping until the whole sample is collected. Pressing a paper towel under the mesh can help draw water through gelatinous samples. Remove as much water as possible.
5. Transfer as much of the sample as possible into the labelled 5 mL cryovial, filling it **no more than two-thirds**. If there is more material than fits, a well-mixed subsample of the whole is still representative of the community.

### Storage

1. Store the cryovial at −80 °C until transport.
2. Ship the samples frozen to the CSIRO Marine Microbiome Initiative Facility, Hobart, following the current *Transport Contact Details NRS Sampling* document. Send them as soon as possible to meet the six-month IMOS reporting deadline.
3. On arrival in Hobart, log the samples and store them at −80 °C until extraction.

### Sampling Equipment Cleaning

1. **Drop net:** after each trip, rinse the whole net with fresh water, dry it in the shade and store it out of the sun. If needed, soak in enzymatic detergent for 2 h to remove dried slime.
2. **Metal spatula:** clean with 10% bleach before each use and rinse with distilled or site water.

### Quality Control

- The genomics haul is never in contact with formalin.
- Gloves are worn and the bleach-cleaned spatula is used at all handling steps.
- Samples are kept on ice in the dark until frozen, and shipped frozen.
- Haul time, drop time and site are recorded for every sample.
- <!-- TODO: state whether any field blanks or equipment blanks are collected for zooplankton genomics --> No field controls are specified in the source protocol.

### Basic Troubleshooting Guide

- **Net does not fall cleanly.** Make sure it is thoroughly wet before the first drop.
- **Gelatinous samples hard to drain on the mesh.** Press a paper towel under the mesh to draw water through.
- **Too much material for one cryovial.** Mix well and fill the cryovial no more than two-thirds. A well-mixed subsample is representative.
- **Dried slime on the net.** Soak in enzymatic detergent for 2 h.

## REFERENCES

- Davies, C. (Ed.) (2025). *National Reference Stations Biogeochemical Operations Manual*, Version 5. Integrated Marine Observing System. <https://doi.org/10.26198/5c4a56f2a8ae3>

## APPENDIX A: DATASHEETS

- **NRS field log sheet:** records station, date, haul times, drop times and site codes.
- **Transport Contact Details NRS Sampling (Sept 2025):** shipping addresses and contacts for frozen zooplankton genomics samples.
- **Video demonstrations of NRS post-sampling procedures:** <https://www.youtube.com/channel/UCXp5vxj2TaCatkura7vMYOA>
