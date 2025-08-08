# 🌧️ Rainfall Prediction in India (Regression)

This project uses historical rainfall data across Indian states and districts to **predict annual rainfall** using a Random Forest Regression model. The goal is to analyze rainfall trends and predict annual totals based on monthly rainfall inputs.

---

## 📌 Overview

- ✅ **Model Used:** Random Forest Regressor  
- ✅ **R² Score Achieved:** 0.969  
- ✅ **Low Prediction Error:** MAE = 92.16 mm, RMSE = 163.80 mm  
- ✅ **Dataset Coverage:** 115 years (1901–2015)  
- ✅ **Tools:** Python, Pandas, Seaborn, Matplotlib, Scikit-learn  
- ✅ **Visualizations:** Trend analysis, correlation heatmaps, and regional comparisons

---

## ⚙️ Technologies Used

- **Programming Language:** Python  
- **Data Manipulation:** Pandas, NumPy  
- **Data Visualization:** Matplotlib, Seaborn  
- **Machine Learning:** Scikit-learn (RandomForestRegressor)  
- **Notebook & Scripts:** Jupyter Notebook

---

## 📂 Dataset

1. **`district wise rainfall normal.csv`**  
   Average monthly rainfall for each Indian district and state.

2. **`rainfall in india 1901-2015.csv`**  
   Historical monthly rainfall data from 1901 to 2015.

📌 *Source: Indian Meteorological Department (via Kaggle)*

---

## 📊 Features

- **Data Analysis:**
  - Correlation heatmaps between months
  - Monthly and annual rainfall distributions
  - Rainfall trends over the years
  - State-wise and district-wise comparisons

- **ML Model:**
  - **Features:** Monthly rainfall (JAN–DEC)
  - **Target Variable:** Annual rainfall (mm)
  - **Model:** Random Forest Regressor
  - **Evaluation Metrics:** MAE, RMSE, R² Score

- **Visual Insights:**
  - Top 10 rainiest districts in India
  - State-wise Rainfall Distribution Boxplots
  - Actual vs Predicted Rainfall Plot

