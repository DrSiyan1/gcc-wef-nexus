# GCC Water-Energy-Food Nexus Vulnerability Analysis
**Author:** Dr. Adedamola Akeem Siyanbola (Ph.D) | May 2026
**Tools:** Python · Pandas · Matplotlib · Seaborn · World Bank Data
**Data:** World Bank WDI (2000-2023) · 6 Countries · 6 Indicators

---

## Overview
This project constructs an original **Water-Energy-Food (WEF) Nexus Vulnerability Index** for all six Gulf Cooperation Council (GCC) member states using World Bank data (2000-2023).

---

## Key Findings
| Rank | Country | WEF Index | Primary Vulnerability |
|------|---------|-----------|----------------------|
| 1 | Saudi Arabia | 6.38 | Energy transition gap |
| 2 | Bahrain | 6.02 | Extreme water scarcity |
| 3 | Kuwait | 5.34 | Balanced across all three |
| 4 | Oman | 4.13 | Food import dependency |
| 5 | Qatar | 4.08 | Moderate across all |
| 6 | UAE | 2.39 | Least vulnerable |

---

## Methodology
1. **Data collection:** World Bank WDI via web portal (2024)
2. **Normalisation:** Min-Max scaling to 0-10 vulnerability scale
3. **Weighting:** Water 35% · Energy 35% · Food 30%
4. **Period:** 2018-2023 average for index stability

---

## Project Structure
- data/ — raw and cleaned datasets
- charts/ — 5 publication-quality figures
- 01_data_exploration.ipynb — data loading and cleaning
- 02_wef_index.ipynb — index construction
- 03_visualisations.ipynb — all 5 charts
- 04_policy_memo.ipynb — findings and recommendations

---

## Headline Insights
- Saudi Arabia's biggest vulnerability is energy transition failure, not water
- Bahrain faces the GCC's most acute water crisis (score 9.96/10)
- Kuwait has effectively zero renewable electricity output
- UAE's early clean energy investment is measurably reducing systemic risk

---

## How to Run
1. Clone this repository
2. Open Jupyter Notebook
3. Run notebooks in order: 01 then 02 then 03 then 04

---

## Related Projects
gulf-renewable-energy-analysis


## Author
**Dr. Adedamola Akeem Siyanbola (Ph.D)**
Senior Lecturer, Department of Economics
Olabisi Onabanjo University, Nigeria
Email: siyanbolaadedamola@gmail.com
GitHub: github.com/DrSiyan1
