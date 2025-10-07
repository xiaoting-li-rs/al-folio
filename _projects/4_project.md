---
layout: page
title: Dynamic Residential Vacancy Modeling
description: Dynamic Energy Demand Modeling Using Urban Residential Vacancy Indicators
img: assets/img/vacancy_modeling.jpg
importance: 4
category: energy_modeling
related_publications: li2022mapping_vacancies
---

## Stage 3: Dynamic Energy Demand Indicators

This project introduces temporal dynamics into urban energy modeling by developing methods to infer residential occupancy patterns and vacancy rates, enabling more accurate and responsive energy demand estimates.

### Project Overview

Traditional energy models often assume static occupancy patterns, leading to significant errors in demand forecasting. This project develops innovative methods to detect and quantify residential vacancy dynamics using multi-source temporal data, providing a crucial missing piece for accurate urban energy modeling.

### Key Innovations

- **Multi-Source Temporal Analysis**: Novel integration of Nighttime Lights (NTL), building activity indicators, and mobile phone data to infer occupancy dynamics.

- **Vacancy Detection Algorithm**: Development of robust algorithms to identify vacant residential units and quantify occupancy rates at high spatial and temporal resolution.

- **Dynamic Energy Refinement**: Integration of vacancy metrics into energy models to capture infrastructure underutilization and seasonal fluctuations.

- **Temporal Scalability**: Methods capable of detecting both short-term (daily/weekly) and seasonal (monthly/yearly) vacancy patterns.

### Technical Methodology

**Data Sources and Processing**:
- **Nighttime Lights (NTL)**: VIIRS-DNB and Luojia-1 satellite data for activity detection
- **Building Activity**: Thermal signatures and electricity consumption patterns
- **Mobile Phone Data**: Anonymized location data for occupancy validation
- **Administrative Records**: Census and utility connection data for ground truth

**Vacancy Detection Algorithm**:
1. **Baseline Establishment**: Historical occupancy patterns for different building types
2. **Anomaly Detection**: Statistical methods to identify deviations from expected patterns
3. **Temporal Filtering**: Smoothing algorithms to distinguish vacancy from temporary absence
4. **Spatial Validation**: Cross-validation using neighboring building patterns

**Energy Model Integration**:
- **Occupancy Scaling**: Dynamic adjustment of energy demand based on actual occupancy
- **Infrastructure Efficiency**: Modeling of shared system efficiency under varying occupancy
- **Seasonal Adjustments**: Incorporation of vacation and migration patterns
- **Uncertainty Quantification**: Probabilistic modeling of occupancy uncertainty

### Validation and Accuracy Assessment

**Ground Truth Validation**:
- Field surveys in Beijing covering 500+ residential buildings
- Utility company data for electricity connection status
- Property management records for occupancy verification
- Cross-validation with census data and administrative records

**Accuracy Metrics**:
- Overall vacancy detection accuracy: 78-85%
- Temporal correlation with known seasonal patterns: R² > 0.7
- Spatial consistency with neighborhood characteristics
- False positive/negative analysis for different building types

### Applications and Impact

**Energy System Planning**:
- More accurate demand forecasting for grid planning
- Infrastructure sizing based on actual rather than theoretical demand
- Peak demand prediction incorporating occupancy dynamics

**Urban Policy**:
- Housing policy evaluation through vacancy monitoring
- Urban sprawl assessment and compact development planning
- Affordable housing program effectiveness measurement

**Climate Resilience**:
- Heat wave vulnerability assessment based on actual occupancy
- Emergency response planning using real-time occupancy data
- Energy poverty identification through consumption-occupancy analysis

### Case Study: Beijing Residential Vacancy

**Spatial Patterns**:
- Higher vacancy rates in peripheral developments (15-25%)
- Lower vacancy in central urban areas (5-10%)
- Correlation with housing prices and transportation accessibility

**Temporal Dynamics**:
- Seasonal variations related to Spring Festival migration
- Weekly patterns reflecting work-related temporary absence
- Long-term trends related to urban development cycles

**Energy Implications**:
- 12-18% reduction in actual vs. theoretical energy demand
- Significant implications for infrastructure planning
- Improved accuracy in peak demand forecasting

### Model Robustness and Sensitivity

**Threshold Sensitivity**:
- Analysis of vacancy detection thresholds across building types
- Seasonal adjustment factors for different climate zones
- Urban density effects on detection accuracy

**Temporal Aggregation**:
- Optimal temporal windows for different applications
- Trade-offs between temporal resolution and accuracy
- Integration with weather and economic data for enhanced prediction

### Future Developments

This dynamic vacancy modeling enables:
- Real-time energy demand adjustment systems
- Integration with smart grid technologies
- Enhanced climate vulnerability assessments
- Policy scenario modeling for housing and energy systems

---

*This project represents Stage 3 of the research framework, introducing critical temporal dynamics that significantly improve the accuracy and applicability of urban energy demand models.*