# US Flood Claims Analysis (2015–2025)

This repository contains an exploratory data analysis of FEMA’s Redacted Flood Claims dataset from 2015 to 2025. The project aims to identify trends in flood insurance claims, assess regional risk patterns, and prepare data for visualization in Tableau to support storytelling and public policy analysis.

---

## Data Source

**FEMA NFIP Redacted Claims V2**  
[OpenFEMA Dataset Link](https://www.fema.gov/openfema-data-page/fima-nfip-redacted-claims-v2)

This dataset contains anonymized claim-level information for National Flood Insurance Program (NFIP) policies.

---

## Key Questions

- What are the trends in the number and value of flood claims over time?
- Which states and counties have the highest concentration of flood-related losses?
- How do building and content damage compare across regions?
- Are there patterns in cause of loss or increased activity following major events?

---

## Methods Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Data cleaning and normalization
- Handling missing values and inconsistent latitudes and longitudes
- Aggregation by year, state, and type of loss
- Visualizations in Tableau

---

## Tableau Dashboard

An interactive Tableau dashboard was created to explore:
- Total claim amounts by state and year
- Trends in building vs. content losses
- Geographic hotspots of repeated loss
- Distributions by cause of loss

**Link to dashboard coming soon**

---

## Notable Findings

- Coastal states account for the highest total claims over the 10-year period.
- Content damage claims are consistently lower in value than building damage claims.
- Several high-frequency flood zones appear in the same ZIP codes repeatedly.
- Claims spike noticeably following major storm events such as Hurricanes Harvey and Ida.

---

## Data Cleaning Summary

Key steps taken during the data preparation process include:
- Removing rows with missing or placeholder values
- Standardizing zipcode and state formats
- Cleaning and converting dollar amount fields
- Renaming columns for readability and consistency

Details are available in the `flood_data.ipynb` notebook.

---

## Future Work

- Integrate FEMA’s Multiple Loss Properties (MLP) dataset
- Merge with NOAA or FEMA flood zone shapefiles for spatial analysis
- Develop predictive models for high-risk flood-prone areas
