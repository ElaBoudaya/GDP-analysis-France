
# France GDP Analysis with Regression Models

## Project Description
This project explores the evolution of France's GDP using different regression models: **linear, polynomial, exponential, and multiple linear regression**.  
The goal is to understand the differences between these models and demonstrate the complete process of **data preprocessing, correlation analysis, modeling, and performance evaluation**.

---

## Data
The data comes from the **World Bank** and includes several indicators for France:

- **GDP** (Value)  
- **Population**  
- **Inflation**  
- **Annual GDP Growth**  

All Excel files are included in the `data/` folder of the repository:


**Original source:** [World Bank Open Data] 

> **Note:** Files have been cleaned and merged for analysis. All preprocessing steps are detailed in the project notebook.

---

## Project Steps
1. **Data Extraction and Cleaning**  
   - Handle missing values  
   - Merge multiple datasets  
   - Create new features (e.g., `GDP_lag1`)  

2. **Exploratory Data Analysis (EDA)**  
   - Study correlations between variables  
   - Visualize relationships using scatter plots and heatmaps  

3. **Regression Modeling**  
   - Linear Regression  
   - Polynomial Regression (degree 2)  
   - Exponential Regression  
   - Multiple Linear Regression with additional features  

4. **Model Evaluation**  
   - Calculate R² and RMSE metrics  
   - Compare model performance  
   - Visualize predicted vs actual values  

---

## Key Results
- Simple models (linear, polynomial, exponential) show limitations in capturing the rapidly increasing GDP.  
- Multiple Linear Regression with additional features (population, inflation, GDP growth, GDP_lag1) provides the best performance according to **R²** and **RMSE**.  

---

## Project Objective
- Understand and compare different regression models  
- Preprocess and enrich real-world datasets  
- Evaluate and interpret model performance effectively  

---
