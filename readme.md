# Project Proposal: Istanbul Reservoir Levels, Rainfall, and Water Consumption (2011–2024)

## 1. Project Description
This project focuses on analyzing the relationship between **rainfall**, **water consumption**, **population growth** and **reservoir levels** in Istanbul between 2011 and 2024.  
The aim is to understand how rainfall and increasing water demand influence the city’s water storage and sustainability.  
Water scarcity is an important issue for Istanbul, and examining these patterns can help highlight the balance between natural supply and human demand.


## 2. Data Sources

| Data | Source | Period | Description |
|------|---------|---------|-------------|
| **Reservoir Levels, Rainfall, and Water Consumption** | [Kaggle: Istanbul 2011–2024 Dam, Precipitation and Consumption Dataset] (https://www.kaggle.com/datasets/noepinefrin/istanbul-2011-2024-dam-precipitation-and-consumption?resource=download) | 2011–2024 | Contains daily data of Istanbul’s 10 reservoirs storage data, total rainfall, and water consumption (m³/day). |
| **Population Data** | [nufusu.com - Istanbul Population] (https://www.nufusu.com/il/istanbul-nufusu) | 2009–2024 | Annual population data of Istanbul, sourced from TÜİK (Turkish Statistical Institute). |


## 3. Methodology

**3.1 Data Collection**
- Download rainfall, reservoir level, and water consumption data from Kaggle.
- Collect annual population data from TÜİK (via nufusu.com).

**3.2 Data Cleaning & Preparation**
- Convert daily rainfall, reservoir levels, and consumption data into monthly averages.
- Assign each month the corresponding yearly population value.
- Merge all variables — rainfall, reservoir levels, water consumption, and population — into a single time-aligned dataframe.
- Handle missing values and ensure consistent date formatting.

**3.3 Exploratory Data Analysis**
- Visualize trends in rainfall, reservoir storage, water consumption, and population over time.
- Identify seasonal patterns (dry/wet periods) and long-term trends.
- Examine how population growth aligns with changes in water consumption.
- Calculate correlations between key variables (rainfall, reservoir levels, consumption, population).

**3.4 Hypothesis Testing**
The project will test the following hypotheses:

H₀₁: Rainfall has no significant effect on Istanbul’s reservoir water storage.
Hₐ₁: Rainfall has a significant positive effect on Istanbul’s reservoir water storage.

H₀₂: Water consumption does not significantly reduce reservoir water storage.
Hₐ₂: Water consumption significantly reduces reservoir water storage.

H₀₃: Population growth does not significantly increase water consumption in Istanbul.
Hₐ₃: Population growth significantly increases water consumption in Istanbul.

H₀₄: Rainfall and water consumption together do not significantly explain changes in Istanbul’s long-term water sustainability.
Hₐ₄: Rainfall and water consumption together significantly explain changes in Istanbul’s long-term water sustainability.

## 4. Expected Outcomes

- Quantitative insight into how much rainfall affects reservoir levels.
- Understanding of whether consumption or population growth significantly reduces water storage.
- Visual trends showing long-term changes in water supply and demand.
- Evidence-based conclusions supported by hypothesis testing.

