# gold-recovery-predictive-model
Predictive modeling of gold recovery using Random Forest and sMAPE evaluation on mineral processing data.
# Gold Recovery Predictive Model

Predictive modeling of gold recovery in mineral processing using **Random Forest** and **sMAPE evaluation**.

---

##  Project Overview

The goal of this project is to **predict the efficiency of gold recovery** in the rougher and final stages of mineral processing. Accurate predictions help optimize operations and maximize gold yield.

---

##  Dataset

- The dataset contains **industrial mineral processing data**, including features like ore properties, process parameters, and time-based measurements.
- Data cleaning included:
  - Removing NaN and infinite values
  - Dropping non-numeric columns (e.g., date)
  - Ensuring all features are numeric for machine learning

> Note: For privacy and size reasons, only a sample of the dataset is included. Instructions for downloading the full dataset can be added here.

---

##  Data Preprocessing

- Checked for missing or infinite values  
- Converted all relevant features to numeric types  
- Split data into training and testing sets  
- Scaled features if necessary

---

##  Methods

1. **Exploratory Data Analysis (EDA)**  
   - Understanding feature distributions  
   - Correlation analysis between features and target variables  

2. **Modeling**  
   - **Linear Regression** (baseline)  
   - **Random Forest Regressor** (optimized)  

3. **Evaluation**  
   - **sMAPE (Symmetric Mean Absolute Percentage Error)** used to measure prediction accuracy for:
     - Rougher gold recovery  
     - Final gold recovery  
   - Weighted sMAPE calculated for overall performance  

---

##  Results

| Metric                  | Value |
|-------------------------|-------|
| Rougher recovery sMAPE  | 2.22% |
| Final recovery sMAPE    | 3.59% |
| Weighted sMAPE          | 2.73% |

> Random Forest with optimized parameters achieved high accuracy with low error rates.

---
