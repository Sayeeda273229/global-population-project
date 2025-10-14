# global-population-project
# 🌍 Global Population Prediction Project

This project focuses on predicting the 2022 population of different countries using features like GDP, continent, capital city, and more. The goal was to build a regression model capable of learning from historical and categorical data, and to interpret which features have the greatest influence on population estimates.

## 🔍 Overview

- **Data Source:** Dataset with various demographic and economic indicators
- **Target Variable:** 2022 Population
- **Tools Used:** Python, Jupyter Notebook, pandas, scikit-learn, XGBoost, SHAP

## ⚙️ Process

1. **Data Preprocessing**
   - Dropped unnecessary or duplicate columns
   - One-hot encoded categorical variables
   - Scaled numerical features using 'StandardScaler'

2. **Model Training**
   - Used XGBoost Regressor to predict population
   - Evaluated using MAE and RMSE
   - Handled errors related to data types, missing values, and encoding

3. **Model Explainability**
   - Used SHAP values to understand feature impact
   - Visualised top contributing features in predictions

## 📁 Files

- 'world_population.ipynb' — Full notebook with all code, outputs, and visualisations
- 'world_population.py' - Project coverted to .py
- 'world_population.csv' — Dataset used in the analysis
- 'README.md'

## 📊 Results

The model produced reasonable predictions and showed how features like GDP, region, and capital can influence a country's population. EDA helped understant correlations and SHAP helped visualise these relationships and added transparency to the model’s decisions.

## 🚀 How to Run

1. Clone the repo or download the files  
2. Open 'world_population.ipynb' in Jupyter Notebook  
3. Run all cells (Restart & Run All recommended)  
4. Outputs and SHAP plots will appear in-line

## What this project showcases

This was a hands-on challenge in managing messy real-world data, debugging classic machine learning workflow issues, and building a model that actually explains its predictions. It reflects real development struggles — and wins.

---

*Built with Python, frustration, debugging, and coffee.*
