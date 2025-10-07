---
layout: page
title: Multi-Source Remote Sensing for Urban Energy
description: Energy Modeling Using Earth Observation-based Urban Building Stock Information
img: assets/img/urban_morphology.jpg
importance: 2
category: energy_modeling
related_publications: li2024building_heights
---

## Stage 2: City-Scale Urban Structure for Energy Modeling

This project scales up from individual satellite tracks to comprehensive city-wide urban morphology mapping, leveraging multiple Earth observation data sources to create detailed building stock information for energy demand modeling.

### Project Overview

While ICESat-2 provides valuable point measurements, comprehensive urban energy modeling requires wall-to-wall coverage of urban morphology. This project develops a high-performance computing workflow to map urban structure across thousands of settlements using complementary remote sensing technologies.

### Key Innovations

- **HPC Workflow Development**: Created a scalable high-performance computing pipeline capable of processing urban morphology data for 10,000+ settlements simultaneously.

- **Multi-Source Integration**: Innovative fusion of Synthetic Aperture Radar (SAR) and optical imagery to extract comprehensive urban form features including height, footprint, and compactness measures.

- **Energy-Relevant Features**: Direct extraction of urban morphology parameters specifically linked to energy demand patterns, enabling physics-based energy modeling.

- **Extreme Weather Analysis**: Integration of morphology data with Land Surface Temperature, Nighttime Lights (NTL), and population data to analyze spatial energy patterns under extreme weather conditions.

### Technical Methodology

The workflow encompasses:

1. **Data Acquisition**: Systematic collection of Sentinel-1 SAR, Sentinel-2 optical, and ancillary datasets
2. **Preprocessing Pipeline**: Automated radiometric and geometric correction across multiple data sources
3. **Feature Extraction**: Deep learning-based extraction of building heights, footprints, and morphological indicators
4. **Quality Assessment**: Comprehensive validation using airborne LiDAR and field surveys
5. **Energy Model Integration**: Direct coupling with urban energy consumption models

### Multi-Source Data Integration

**Synthetic Aperture Radar (SAR)**:
- Building height estimation through interferometric and polarimetric analysis
- All-weather capability ensuring consistent temporal coverage
- Penetration capabilities for complex urban environments

**Optical Imagery**:
- Building footprint delineation and land cover classification
- Seasonal vegetation dynamics affecting energy demand
- Urban heat island characterization

**Ancillary Data**:
- Population density for demand scaling
- Meteorological data for climate-energy interactions
- Nighttime lights for activity pattern validation

### Applications and Impact

This comprehensive urban morphology database enables:

- **Dynamic Energy Modeling**: High-resolution inputs for spatiotemporal energy consumption models
- **Climate Vulnerability Assessment**: Understanding how urban form affects energy resilience
- **Policy Analysis**: Evidence-based urban planning for energy efficiency
- **Cross-City Comparisons**: Standardized metrics for comparative urban energy analysis

### Validation and Uncertainty

Rigorous validation includes:
- Comparison with airborne LiDAR data in multiple cities
- Field survey validation of building characteristics
- Uncertainty propagation through energy modeling chains
- Sensitivity analysis for different urban typologies

### Future Integration

This city-scale morphology mapping provides the spatial foundation for subsequent research stages, including land use functional analysis and dynamic occupancy modeling for comprehensive urban energy assessment.

---

*This project represents Stage 2 of a unified research framework, building upon ICESat-2 foundations to enable comprehensive urban energy modeling at city scales.*