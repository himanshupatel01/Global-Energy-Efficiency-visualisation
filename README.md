# Global Energy Efficiency Trends & Regional EPC Analysis

## 📌 Project Overview
This project presents an end-to-end data analytics and econometric investigation into global energy efficiency patterns (1980–2019) across 28 countries, alongside a regional case study of domestic Energy Performance Certificate (EPC) distributions in England and Wales (2020–2022). 

The study calculates a custom **Energy Efficiency Index (EEI)** and deploys multivariate panel regressions and advanced geographical visualisations to establish how economic development shapes carbon mitigation paths.

---

## 🛠️ Technical Toolkit & Skills
* **Languages & Core Libraries:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Geospatial Analysis & Mapping:** GeoPandas / Choropleth mapping by Local Authority Districts (LADs)
* **Econometric Modelling:** Fixed-Effects Ordinary Least Squares (OLS) Panel Regression, Heteroscedasticity-Robust Standard Errors (HC3)
* **Statistical Insights:** Summary statistics by decade, distribution box plots, and significance testing (p-values)

---

## 📈 Key Visualisation & Analytical Highlights

### 1. Global Decadal Efficiency Trends (Python Viz)
* Engineered and plotted the macro global EEI trend line showing a **44% reduction in energy intensity** from the 1980s to the 2010s. 
* Contextualised structural anomalies by mapping macro-economic event shocks like the 1991 recession and the 2008 Global Financial Crisis.
* Benchmarked 28 countries for 2019 using ranked horizontal bar charts, identifying the UK as the 6th most energy-efficient economy sample-wide.

### 2. Macro-Economic Drivers (Panel Regression)
* Built a fixed-effects model (R² > 0.90) mapping Log EEI against World Bank development metrics.
* **Developed Subsample Findings:** Shifting away from heavy industry (\(-0.013^{**}\)) and expanding renewable energy shares (\(-0.022^{***}\)) act as the strongest empirical drivers for efficiency gains.
* **Developing Subsample Findings:** Trade openness (\(0.003^{***}\)) stands out as the single significant determinant, indicating that clean technology transfers happen through global market integration.

### 3. Domestic EPC Analysis (Geospatial Mapping)
* Processed and cross-compared regional EPC and Environmental Impact distributions across 314 local authorities.
* Generated regional box plots proving London holds the highest median score (**68.0**) while Wales records the lowest (**65.5**).
* Developed dual choropleth maps highlighting strong spatial clustering: urban centres display superior insulation metrics, while rural districts struggle with older, hard-to-insulate housing stocks.

---
