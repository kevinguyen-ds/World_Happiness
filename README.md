# 🌎 World Happiness Report (2015–2019): Data Analysis & Predictive Modeling

## 🧭 Overview
This project explores and models the **World Happiness Report (2015–2019)** to understand global well-being trends and identify key socioeconomic factors influencing happiness scores. Using machine learning techniques, the analysis aims to predict a country’s happiness score and evaluate which variables contribute most to overall life satisfaction.

The work reflects a complete **end-to-end data science workflow** — from raw data acquisition and cleaning to feature engineering, modeling, and evaluation — designed to simulate a real-world analytical project.

---

## 🎯 Objectives
- Consolidate and clean multi-year datasets from 2015–2019 into a unified analytical table.  
- Perform **exploratory data analysis (EDA)** to detect patterns, outliers, and correlations among variables such as GDP per capita, social support, health, and freedom.  
- Build and evaluate **multiple regression models** to predict happiness scores.  
- Compare model performance and select the best based on key metrics (MAE, RMSE, R²).  
- Visualize insights through plots and dashboards for effective communication.

---

## 🧰 Tools & Technologies
**Languages:** Python, Excel  
**Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
**Techniques:** Data Cleaning, Feature Engineering, Model Training & Evaluation, Pipeline Automation, Regression Analysis  
**Environment:** Jupyter Notebook, VS Code  

---

## ⚙️ Methodology

1. **Data Preparation**
   - Imported datasets from 2015–2019, standardized variable names, and merged them into a single DataFrame.  
   - Addressed missing values, handled outliers, and created engineered features (e.g., GDP-to-Family ratio).  

2. **Exploratory Data Analysis**
   - Produced correlation matrices, histograms, and scatter plots to visualize relationships between predictors and happiness scores.  
   - Identified strong positive relationships between happiness and GDP, social support, and life expectancy.

3. **Model Development**
   - Implemented and tuned multiple regression models:
     - Linear Regression  
     - Ridge Regression  
     - Polynomial Regression (degree = 2)  
     - Decision Tree  
     - Random Forest  
   - Used scaling, encoding, and pipeline workflows for consistency and reproducibility.

4. **Model Evaluation**
   - Compared models using **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, and **R²** metrics.  
   - Selected the **Linear Regression** model as the best performer based on high accuracy and generalization.

---

## 📊 Results Summary

| Model | MAE | RMSE | R² |
|-------|------|------|----|
| **Linear Regression** | 0.1673 | 0.2341 | **0.9561** |
| Ridge Regression | 0.1773 | 0.2550 | 0.9465 |
| Polynomial (d=2) | 0.1991 | 0.3121 | 0.9199 |
| Decision Tree | 0.3829 | 0.5282 | 0.7706 |
| Random Forest | 0.2724 | 0.3687 | 0.8883 |

✅ **Best Model:** Linear Regression (RMSE = 0.2341, R² = 0.9561)  
📈 The results indicate that linear relationships dominate in predicting happiness scores, suggesting that socioeconomic indicators have a consistent influence across years.

---

## 📁 Repository Contents
- `Final_dataset.xlsx` — Cleaned and merged dataset (2015–2019)  
- `Model_Comparison.xlsx` — Model performance summary table  
- `World_Happiness.ipynb` — Full notebook with code, plots, and commentary  
- `best_model.pkl` — Serialized Linear Regression model for reuse  

---

## 🧠 Key Takeaways
- Gained practical experience applying regression techniques to real-world socioeconomic data.  
- Strengthened proficiency in data cleaning, feature engineering, and hyperparameter tuning using Scikit-learn pipelines.  
- Demonstrated ability to extract insights and communicate findings effectively through both visualization and quantitative evaluation.

---

*Created by **Tuan Kiet Nguyen** — Bachelor of Data Science & Analytics, Seneca Polytechnic*  
📍 Toronto, Canada  

