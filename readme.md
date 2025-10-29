# Project Proposal: Istanbul Reservoir Levels, Rainfall, and Water Consumption (2011–2024)

## 1. Project Description
This project focuses on analyzing the relationship between **rainfall**, **water consumption**, and **reservoir levels** in Istanbul between 2011 and 2024.  
The aim is to understand how rainfall and increasing water demand influence the city’s water storage and sustainability.  
Water scarcity is an important issue for Istanbul, and examining these patterns can help highlight the balance between natural supply and human demand.


## 2. Data Sources

| Data | Source | Period | Description |
|------|---------|---------|-------------|
| **Reservoir Levels, Rainfall, and Water Consumption** | [Kaggle: Istanbul 2011–2024 Dam, Precipitation and Consumption Dataset] (https://www.kaggle.com/datasets/noepinefrin/istanbul-2011-2024-dam-precipitation-and-consumption?resource=download) | 2011–2024 | Contains daily data of Istanbul’s 10 reservoirs storage data, total rainfall, and water consumption (m³/day). |
| **Population Data** | [nufusu.com - Istanbul Population] (https://www.nufusu.com/il/istanbul-nufusu) | 2009–2024 | Annual population data of Istanbul, sourced from TÜİK (Turkish Statistical Institute). |


## 3. Plan for Data Collection and Preparation
- Download the Kaggle dataset containing rainfall, reservoir, and water consumption data.  
- Collect Istanbul’s annual population data from TÜİK (via nufusu.com).  
- Convert daily data to monthly averages or totals.  
- Assign each month the corresponding yearly population value.  
- Merge rainfall, water consumption, reservoir level, and population data into a single dataframe.  
- Ensure all datasets use the same date format for temporal alignment.

