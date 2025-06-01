# Climate Modeling Analysis of India using CMIP6
![](monsoon.webp)

## About
This study leverages data from the Coupled Model Intercomparison Project Phase 6 (CMIP6) to analyze projected changes in precipitation and wind patterns across India. Given the country’s strong reliance on monsoon-driven rainfall, this analysis focuses on comparing historical climate conditions with a future high-emissions scenario (SSP5-8.5), which assumes continued fossil fuel development and minimal climate mitigation efforts. The goal is to assess how intensification or disruption of monsoonal systems could impact regional climate dynamics under extreme climate.

## Repository Structure
```bash

```

## Data
The data utilized for this analysis is publicly available on an API catalog. To read in the data, ensure the package `intake` is imported to your Python environment.

```{python}
# load packages
import intake

# CMIP6 catalog
catalog = intake.open_esm_datastore('https://cmip6-pds.s3.amazonaws.com/pangeo-cmip6.json')
```

## References
Government of India. (2025, January). Agriculture and Food Management: Sector of the Future https://www.indiabudget.gov.in/economicsurvey/doc/eschapter/echap09.pdf

Sahastrabuddhe, R., Ghausi, S. A., Joseph, J., & Ghosh, S. (2023). Indian summer monsoon rainfall in a changing climate: A Review. Journal of Water and Climate Change, 14(4), 1061–1088. https://doi.org/10.2166/wcc.2023.127

Douglas, I. (2009). Climate change, flooding and Food Security in South Asia. Food Security, 1(2), 127–136. https://doi.org/10.1007/s12571-009-0015-1

Chen, Y. J., Hwang, Y. T., & Lu, J. (2024). Robust increase in South Asian monsoon rainfall under warming driven by extratropical clouds and Ocean. Npj Climate and Atmospheric Science, 7(1). https://doi.org/10.1038/s41612-024-00843-7

Li, X., Ting, M., Li, C., & Henderson, N. (2015). Mechanisms of asian summer monsoon changes in response to anthropogenic forcing in CMIP5 models. Journal of Climate, 28(10), 4107–4125. https://doi.org/10.1175/jcli-d-14-00559.1

## Acknowledgements
This repository was created for a final project related to the course EDS 296: A Climate Modeling Perspective on Big Data Techniques.

This course is an academic requirement for the Master of Environmental Data Science (MEDS) program at the Bren School of Environmental Science & Management, University of California, Santa Barbara
