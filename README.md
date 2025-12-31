# Drought Assessment using Sentinel-2 and QGIS

## Overview
This project presents a satellite-based drought assessment for Tiruchirappalli District, Tamil Nadu, using Sentinel-2 surface reflectance imagery and QGIS.

The analysis focuses on vegetation health as an indicator of agricultural drought conditions.
---

## 📊 Key Outputs

### NDVI Map
![NDVI Map](outputs/ndvi_map_trichy.png)

### Drought Severity Classification
![Drought Severity Map](outputs/drought_severity_map_trichy.png)

## Study Area
Tiruchirappalli District, Tamil Nadu, India.

## Data Used
- Sentinel-2 MSI Level-2A (Surface Reflectance)
- Bands used: Band 4 (Red), Band 8 (NIR)

## Methodology
- Sentinel-2 imagery was clipped to the study area boundary.
- NDVI was calculated using Red and NIR bands.
- NDVI values were reclassified into drought severity categories.
- Non-vegetated areas were masked to avoid misinterpretation.
- Final thematic maps were produced using QGIS (Long Term Release).

## Outputs
- NDVI vegetation health map
- Drought severity classification map

## Tools
- QGIS (Long Term Release)
- Satellite Remote Sensing (Sentinel-2)

## 2025 Update
This project is an updated implementation of a Master's thesis on drought assessment.
Key workflows were re-executed in QGIS to ensure reproducibility and alignment with current GIS industry practices.
