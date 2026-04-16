# Geospatial-Socioeconomic-Interactive-Dashboard-for-Massachusetts


## Data Metrics: Interactive Socio-Economic Suitability Dashboard for Suffolk County, MA

![Tableau](https://img.shields.io/badge/Tableau-Public-blue?logo=tableau)
![Data](https://img.shields.io/badge/Data-US%20Census%20%7C%20Zillow-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📊 Live Dashboard

🔗 [View on Tableau Public](https://public.tableau.com/app/profile/prithvi.prasad/viz/Project2_17338776393160/Dashboard1)

---

## 📌 Project Overview

**Data Metrics** is an interactive data visualization dashboard that analyzes multiple socio-economic variables at the **zip code level** across **Suffolk County, Massachusetts**. The dashboard enables users to explore and compare neighborhood desirability through a customizable composite suitability score — helping individuals, researchers, and policymakers make informed, data-driven decisions about regional livability.

---

## 🎯 Objectives

- Visualize key socio-economic indicators across Suffolk County zip codes
- Calculate a **composite suitability score** for each zip code based on user-defined priorities
- Provide an interactive, intuitive interface for exploring neighborhood-level data
- Support data-driven decision-making for individuals evaluating where to live or invest

---

## 📂 Key Variables

The dashboard is built around **five critical socio-economic variables**:

| Variable | Source | Relationship to Desirability |
|---|---|---|
| **Median Income** | U.S. Census Bureau (ACS 5-Year, 2022) | ↑ Higher = More Desirable |
| **Educational Attainment** | U.S. Census Bureau (ACS 5-Year, 2022) | ↑ Higher = More Desirable |
| **Population Density** | U.S. Census Bureau (ACS 5-Year, 2022) | ↑ Higher = More Desirable |
| **Housing Prices** | Zillow Home Value Index (ZHVI) | ↓ Lower = More Desirable |
| **Poverty Percentage** | U.S. Census Bureau (ACS 5-Year, 2022) | ↓ Lower = More Desirable |

---

## ⚙️ Score Calculation Methodology

A **composite suitability score** is generated for each zip code using the following approach:

### 1. Normalization
Each variable is normalized to ensure equal contribution to the composite score, accounting for different scales and units across variables.

### 2. Directional Weighting
- **Directly proportional** variables (Median Income, Education, Population Density): Higher values indicate better living conditions.
- **Inversely proportional** variables (Housing Prices, Poverty %): Lower values are more desirable, so scores are inverted accordingly.

### 3. User-Defined Weights
Users can assign custom weights (ranging from **0 to 100**) to each variable based on their personal priorities:
- Prioritize **Median Income** → emphasizes economic prosperity
- Prioritize **Housing Prices** → emphasizes affordability
- Adjust all weights simultaneously for a fully personalized suitability ranking

---

## 🗺️ Geographic Scope

- **Region:** Suffolk County, Massachusetts
- **Granularity:** Zip Code level
- **Zip Codes Covered:** 02108, 02109, 02110, 02111, 02113–02116, 02118–02136, 02150–02152, 02163, 02199, 02203, 02205, 02210, 02215 (and more)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Tableau Public** | Dashboard creation and interactive visualization |
| **U.S. Census Bureau (ACS)** | Demographic and socio-economic data |
| **Zillow Research (ZHVI)** | Housing price data |

---

## 📁 Data Sources

1. U.S. Census Bureau. (2022). *Educational Attainment* — ACS 5-Year Estimates, Table S1501.
2. U.S. Census Bureau. (2022). *Poverty Status in the Past 12 Months* — ACS 5-Year Estimates, Table S1701.
3. U.S. Census Bureau. (2022). *Population 60 Years and Over* — ACS 5-Year Estimates, Table S0102.
4. U.S. Census Bureau. (2022). *Median Income in the Past 12 Months* — ACS 5-Year Estimates, Table S1903.
5. Zillow. (n.d.). *Zillow Home Value Index (ZHVI)*. Zillow Research. [zillow.com/research/data](https://www.zillow.com/research/data/)

---

## 👤 Author

**Prithvi Prasad**
[prasad.pri@northeastern.edu](mailto:prasad.pri@northeastern.edu)  

Northeastern University — College of Engineering  

IE6600: Computation and Visualization | Fall 2024  

Supervised by: Prof. Sri Radhakrishnan

---

## 📄 License

This project was created for academic purposes as part of coursework at Northeastern University.
