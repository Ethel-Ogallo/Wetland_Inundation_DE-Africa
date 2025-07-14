# Wetland Dynamics Analysis in the Zambezi Delta

This repository contains workflows (`STAC- wetland_inundation.ipynb`) used to analyze wetland dynamics in the Zambezi Delta region of Mozambique using satellite data and products accessed through the Digital Earth Africa (DE-Africa) STAC Catalog. The notebook processes Landsat data to derive key indicators providing insights into the spatial and temporal changes in wetland characteristics.

## Overview

Wetlands play a vital role in ecosystem services and biodiversity. This project aims to:

- Monitor spatiotemporal wetland dynamics (2017–2024)
- Analyze patterns of surface water and vegetation using:
  - Tasseled Cap Wetness (TCW)
  - Water Observations from Space (WOfS)
  - Fractional Cover (FC)
- Visualize the changes 

## Code

- The main analysis is implemented in [`STAC- wetland_inundation.ipynb`](STAC-%20wetland_inundation.ipynb)
- It uses the following tools and libraries:
  - `odc-stac` for loading STAC-based EO datasets
  - `deafrica-tools` for utility functions

## Seminar Paper

For the full context, methodology, results, and discussion, please read the seminar paper [here](Paper_Ogallo.pdf)

## Sample Output

Visualizations and animations of wetland changes over time are included in the notebook.  

<img src="output/wetland_dnamics_monthly.gif" alt="Wetland Dynamics" width="300"/>

### Acknowledgements
Author: Ethel Ogallo  
Supervisor: Hannah Augustine  
[Digital Earth Africa](https://github.com/digitalearthafrica)




