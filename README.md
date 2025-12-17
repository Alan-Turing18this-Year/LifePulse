LIFEPULSE
# Social and Economic Determinants of Birth Rates in 2023: A Cross-Country Analysis
### Linear Regression Analysis of Social and Economic Determinants

## Overview
This repository contains the data, code, and supporting materials for the study **“Social and Economic Determinants of Birth Rates in 2023: A Cross-Country Analysis.”**  
The project investigates whether social (demographic and health-related) or economic factors better explain cross-country differences in birth rates during the post-pandemic year 2023.

Using cross-sectional data from 65 countries and a log-linear Ordinary Least Squares (OLS) regression with heteroskedasticity-robust standard errors, the study finds that **demographic structure and mortality conditions dominate economic indicators** in explaining fertility variation.

---

## Authors

| Name | Role |
|------|------|
| **Josh T. Ganhinhin** | Team Lead and Project Coordinator |
| **Jomar B. Ligas** | Data Analysis and Interpretation |
| **Lex Leander V. Lumantas** | Technical Implementation and Validation |
| **Mark Oraño** | Team Coordination and Workflow Management |
| **Philip Andree C. Tupas** | Statistical Analysis and Results Synthesis |

**Affiliation:**  
Department of Data Science  
College of Information Technology and Computing  
University of Science and Technology of Southern Philippines – Cagayan de Oro  
Cagayan de Oro City, 9000, Philippines

---

## Research Objectives
The main objectives of this study are to:
- Quantify the relative importance of **social determinants** (maternal age, age dependency ratio, child mortality, crude death rate) versus **economic determinants** (GDP per capita, government revenue, government expenditure).
- Examine whether short-term economic conditions in 2023 exert independent effects on fertility after controlling for demographic structures.
- Provide empirical evidence relevant to the post-COVID-19 adjustment period.

---

## Key Findings
- Fertility differences in 2023 are primarily driven by **demographic and mortality-related factors**.
- Higher age dependency ratios are associated with higher birth rates.
- Delayed maternal age and higher mortality rates are linked to lower fertility.
- Economic indicators such as GDP per capita and fiscal variables show **no independent effect** once social factors are controlled.
- Policy responses to fertility decline should prioritise **long-term demographic and health interventions** rather than short-term fiscal expansion.
<img width="1328" height="800" alt="598682615_25385361374406338_1181553391938848595_n" src="https://github.com/user-attachments/assets/747b9669-e060-42d3-807f-a2ee6ee75271" />

---

## Methodology
- **Data Type:** Cross-sectional (65 countries, year 2023)
- **Model:** Log-linear OLS regression  
- **Inference:** Heteroskedasticity-robust standard errors
- **Dependent Variable:**  
  - Birth Rate (log-transformed)
- **Independent Variables:**  
  - Average age of mothers  
  - Age dependency ratio  
  - Child mortality rate (log-transformed)  
  - Crude death rate  
  - GDP per capita (log-transformed)  
  - Fiscal variables (government revenue and expenditure)

---

<img width="1920" height="1080" alt="workflow" src="https://github.com/user-attachments/assets/7d1ea07b-0b91-4fa1-8dff-57ae32b016c1" />

---

<img width="7017" height="9933" alt="image" src="https://github.com/user-attachments/assets/bece9857-7f3e-4d50-8dda-bd7a17788c31" />

---

## Data Sources
- Birth rates and demographic indicators: *Our World in Data*
- Economic indicators: World Bank / national accounts data

(Exact sources and variable definitions are documented in the data or notebook files.)
