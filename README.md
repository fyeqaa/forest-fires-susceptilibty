# Assessing Forest Fire Susceptibility and Its Impact on Biodiversity in Brandenburg Using Machine Learning and Climate Projections

This Project is part of my **Master’s Thesis** at **Technische Universität Berlin**. The study investigates **forest fire susceptibility** in Brandenburg, Germany, using **machine learning**, **explainable AI (XAI)**, and **climate projections**, while also evaluating the **ecological risks to biodiversity within protected areas**.

---

## Thesis Overview

Forest fires are increasing worldwide due to climate change, threatening ecosystems, biodiversity, and human livelihoods. Brandenburg is one of the most fire-prone regions in Germany, characterized by flammable pine forests and rising temperatures.

This project addresses:

-  What are the primary drivers of forest fire susceptibility in Brandenburg?  
-  Which biodiversity-rich protected areas are most at risk now and in the future?  
-  How can Explainable AI (XAI) improve the interpretability of fire prediction models?

---

## Methodology

### Data Sources

- Forest fire occurrences (2016–2021)  
- Topographic, vegetation, anthropogenic, and climatic predictors  
- Climate projections for 2030 & 2050 under **SSP5–8.5**  
- Protected areas datasets: **Natura 2000**, **WDPA**

### Modeling Approach

- **Random Forest (RF)**: Classification model for forest fire susceptibility  
- **LOYO (Leave-One-Year-Out)**: Cross-validation strategy to assess temporal generalization  
- **Future Projections**: Fire prediction for summer seasons of 2030 & 2050  
- **Explainable AI**:  
  - Feature importance using Gini  
  - Local and global interpretation with SHAP values

### Biodiversity Risk Assessment

- Spatial overlay of high-risk fire zones and protected areas  
- Buffer zone analysis to account for fire spread potential  
- Exposure trend comparison across **2021 → 2030 → 2050**

---

## Key Results

### Model Performance

- Historical (LOYO): **~66% accuracy**, ROC-AUC: **0.717**  
- Future scenarios: **~69% accuracy**, ROC-AUC: **0.755**

### Main Drivers

- Proximity to **railways** and **built-up areas**  
- Forest type – especially **Scots pine (coniferous)**  
- Temperature and precipitation had a secondary but relevant effect

### Spatial Insights

- **Southern Brandenburg** identified as a persistent fire hotspot  
- **24% of protected areas** overlap with high-susceptibility zones  
- **Special Protection Areas (SPAs)** under the Birds Directive show growing vulnerability

---

## Implications

This work highlights the importance of integrated, adaptive fire management strategies that combine:

- **Nature-Based Solutions (NbS)**  
  - Mixed-species forests  
  - Vegetated buffer zones  
- **Preventive Measures**  
  - Firebreaks  
  - Wetland restoration  
  - Fuel load management  
- **Policy Recommendations**  
  - Align fire risk planning with the **EU Biodiversity Strategy 2030**  
  - Target conservation efforts in high-risk zones

The framework developed here can be **replicated in other fire-prone regions** to assess ecological risks under future climate scenarios.

---

## Thesis Document

📥 *Thesis PDF coming soon*  
*Code and data will be added later (pending permissions)*

---

## Author

**Fyeqa Akram**  
MSc Geodesy and Geoinformation Sciences
Technische Universität Berlin  
2025

---


