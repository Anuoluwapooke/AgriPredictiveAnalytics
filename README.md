# Agricultural Predictive Analytics Project

**Author:** Aspiring Predictive Data Analyst (AgriTech focus)

---

## Project Overview

This project demonstrates end-to-end predictive analytics on agricultural data, focusing on crop yield prediction based on rainfall and engineered risk features. It includes:

- Data cleaning and handling missing values
- Feature engineering (Low Rainfall and Low Yield risk flags)
- Exploratory data analysis (EDA) and correlation visualization
- Predictive modeling using Linear Regression
- Evaluation and visualization of model predictions

The goal is to show how predictive analytics can support farmers and AgriTech stakeholders in making informed decisions.

---

## Folder Structure

AgriPredictiveAnalytics/

├─ notebooks
│ ├─ exploratory_analysis.ipynb
│ └─ cleaning_and_prediction.ipynb
├─ datasets
│ └─ agri_predictive_dataset_final.csv
└─ README.md

## Data

- Seasonal rainfall (`Rainfall_mm`) and crop yield (`Yield_tons`) data over multiple years.
- Missing values handled using forward-fill (for yield) and mean imputation (for rainfall).
- Risk flags (`Low_Rainfall_Risk`, `Low_Yield_Risk`) engineered to identify high-risk seasons.



