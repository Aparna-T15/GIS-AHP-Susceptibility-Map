# GIS-Based Site Suitability Analysis for Primary Health Centre Construction in Araku Valley Using AHP

A GIS-based site suitability study applying the Analytical Hierarchy Process (AHP) and Weighted Linear Combination (WLC) to identify potentially suitable locations for constructing a Primary Health Centre (PHC) in Araku Valley, Andhra Pradesh, India.

## Project overview

The report describes a multi-criteria decision analysis workflow that combines mapped environmental and accessibility criteria to create a PHC site-suitability map. The study area is Araku Valley in Visakhapatnam District, Andhra Pradesh.

- **Project type:** GIS, remote sensing, and spatial multi-criteria decision analysis
- **Study area:** Araku Valley, Andhra Pradesh, India
- **Methods described:** AHP, criteria reclassification, rasterization, and Weighted Linear Combination
- **Primary deliverable:** PDF report

## Criteria described in the report

- **Land conditions:** preference for flat, barren land and exclusion of water bodies.
- **Slope:** slope below 3% is stated as a criterion.
- **Road distance:** target distance of approximately 1–2 km from roads.
- **Geology:** preference order stated as Charnockite > Khondalite > Migmatite.
- **Existing health facilities:** a 500 m buffer around existing hospitals.

The methodology section also describes land-use/land-cover, geomorphology, road proximity, and slope as inputs to the weighted suitability analysis.

## Workflow

1. Define the site-selection objective and evaluation criteria.
2. Collect and prepare spatial datasets for the study area.
3. Derive relevant layers, including land use/land cover, slope, road distance, and geology/geomorphology.
4. Rasterize and reclassify criteria to a common suitability scale.
5. Use pairwise comparisons in AHP to determine criterion weights.
6. Check the consistency ratio of the pairwise comparison matrix.
7. Combine weighted criteria using the Weighted Linear Combination method to produce a suitability surface.

The report states a consistency ratio of **0.09**, below the 0.1 threshold used in the report.

## Data sources mentioned

- **Landsat 8 imagery:** USGS EarthExplorer
- **Cartosat DEM:** Bhuvan portal
- **Road network:** digitized from satellite imagery, with the HCMGIS plugin referenced
- **Geology:** Bhukosh

Refer to the PDF for the maps, criteria descriptions, AHP calculations, references, and results section.

## Repository contents

```text
.
├── README.md
└── GISProject_HospitalConstructionSusceptiilityMap_AHP.pdf
```

## Limitations and reproducibility

This repository contains the report and summary documentation only. It does not include the source spatial datasets, GIS project files, processing scripts, or the underlying suitability rasters. Therefore, the analysis is not fully reproducible from this repository alone.

This README summarizes the methods and criteria as described in the report; it does not independently validate the selected locations or the underlying data. Consult the report and its cited sources before using the results for planning decisions.

## Citation

**Gaddam, Samanyu; Sajay, S. S.; Singh, Eshna; Yasaswini, B.; Chari, K. Sharath Kumar; and Aparna, T.** *Site Suitability Analysis for the Construction of PHC in Araku Valley Using AHP.* Project report.

## License and attribution

Before making this repository public, confirm that you have permission to publish the report and any maps or third-party materials it contains. Add a license only if you have the right to license the report and its contents. Public visibility does not automatically grant reuse rights.
