# Housing Energy Performance & Retrofit Simulation

This project explores housing energy performance using publicly available EPC data for King’s Lynn and West Norfolk, and simulates how targeted retrofit investment could improve energy efficiency across properties.

Rather than stopping at descriptive analysis, the project introduces a simple decision-making layer by modelling potential improvements and a fixed budget scenario.

## Project Overview

The workflow includes:

- Analysing current EPC ratings across properties  
- Identifying areas with lower energy efficiency  
- Simulating potential EPC improvements  
- Modelling a £5M retrofit budget to prioritise upgrades  

## Key Insight

The analysis shows how a targeted investment approach can upgrade a significant number of lower-rated homes, improving overall energy performance and highlighting where interventions would have the greatest impact.

## Tools Used

- Python (Pandas, NumPy)  
- Power BI (for visualisation)  
- Public EPC dataset  

## Repository Structure

- `epc_analysis.ipynb` → Data cleaning, transformation, and simulation  
- `epc_enriched.csv` → Full dataset with predicted EPC improvements  
- `funded_homes.csv` → Properties selected within the simulated budget  

## Why This Matters

This project demonstrates how data can move beyond reporting into decision support, helping to prioritise housing improvements in a practical and scalable way.
