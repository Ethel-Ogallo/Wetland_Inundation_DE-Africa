# Wetland Dynamics Analysis in the Zambezi Delta

This repository contains workflows (`STAC- wetland_inundation.ipynb`) used to analyze wetland dynamics in the Zambezi Delta region of Mozambique using satellite data and products accessed through the Digital Earth Africa (DE-Africa) STAC Catalog. The notebook processes Landsat data to derive key indicators providing insights into the spatial and temporal changes in wetland characteristics.  

### Overview

Wetlands play a vital role in ecosystem services and biodiversity. This project aims to:

- Monitor spatiotemporal wetland dynamics (2017–2024)
- Analyze patterns of surface water and vegetation by applying Tasseled Cap Wetness (TCW), Water Observations from Space (WOfS), and Fractional Cover (FC) indices
- Visualize changes through plots and animations  

### Workflow  

- **Data access:**  
  - odc-stac – Load STAC-based EO datasets from Digital Earth Africa  
  - deafrica-tools – Utility functions from DE Africa
 
- **Analysis methods:**
  - Tasseled Cap Wetness (TCW) – Indicator of wetland moisture  
  - Water Observations from Space (WOfS) – Surface water detection   
  - Fractional Cover (FC) – Vegetation cover decomposition (green, non-green, bare)  

### Sample Output
Wetland Changes over time  
<img src="output/wetland_dnamics_monthly.gif" alt="Wetland Dynamics" width="300"/>  

### Acknowledgements
[Digital Earth Africa](https://github.com/digitalearthafrica)



