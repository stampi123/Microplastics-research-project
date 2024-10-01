# Microplastics Concentrations and Policy Effectivness Research Study
This was my senior year research paper for an experiential learning data science course at UCSD (COGS 108). 

## Overview: 

### Research Question
**How do global policies passed each year impact subsequent rates of oceanic microplastic concentration?**

### Background
**In this research project, we analyzed the effectiveness of plastic policies on the actual rates of microplastic increase in the ocean. The accumulation of these invisible plastics is a growing concern and may have long term effects.**

### Data
This research analyzes two primary datasets to explore the correlation between plastic policies and microplastic concentration:

1. **Marine Microplastic Concentration Dataset** (NOAA)
   - **Coverage**: Microplastic concentrations in various oceans and subregions from 1989-2022.
   - **Observations**: 22,266
   - **Details**: Collected daily, this dataset includes varied measurements but requires standardization for analysis.
   - **Link**: [Dataset](https://experience.arcgis.com/experience/b296879cc1984fda833a8acc93e31476/page/Page/?views=Data-Table#data_s=id%3AdataSource_1-18cf9a85fdd-layer-4%3A269)

2. **Plastics Policy Inventory Dataset** (Nicholas Institute)
   - **Coverage**: Plastic-related policies from 1990-2023.
   - **Observations**: 10,715
   - **Details**: This dataset catalogs significant policies targeting various plastic products, including their enactment dates and geographic locations.
   - **Link**: [Dataset](https://duke.app.box.com/s/9uy2qi2lzy6nz4l68l6ujmrc0zd4s22p)

### Data Analysis Methodology
We cleaned and formatted the datasets to identify potential correlations between annual policy enactments and subsequent microplastic concentration increases. The analysis includes:

- **Average Microplastic Concentration Ranking**: Calculate yearly rankings for comparison.
- **Non-Parametric Model Fitting**: Since the data is non-parametric, we will apply appropriate statistical models.
- **Rate of Increase Calculation**: Determine annual slopes to track concentration changes.
- **Mann-Whitney U Testing**: Compare concentrations in the 5- and 10-year periods following policy enactments against randomly selected control windows.

This structured approach will help assess whether the number of policies enacted correlates with microplastic concentration changes in the ocean.

### Access the full research paper
Please reference: https://github.com/stampi123/Microplastics-research-project/blob/main/Final_Report.ipynb to read the full research paper and code


