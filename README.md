# ☀️ Predicting Solar Energy Production

This project focuses on developing a robust machine learning model to predict **annual solar energy production** using various features like system size, location, utility, and energy storage. The solution aims to support a renewable energy provider in enhancing project planning and improving grid integration through accurate forecasting.

---

## 📌 Objectives

- Predict estimated annual photovoltaic (PV) energy output (in kWh)
- Support better decision-making with data-driven insights
- Identify key features influencing energy production

---

## 📊 Dataset Overview

- **Rows:** 218,115  
- **Columns:** 17  
- **Target Variable:** Estimated Annual PV Energy Production (kWh)  
- **Key Features:** Developer, Region, Utility, PV System Size (kWac, kWdc), Interconnection Date, Energy Storage

---

## 🔍 Workflow

1. **Data Collection & Exploration**
   - Summary statistics, correlation analysis, and outlier detection
2. **Data Preprocessing**
   - Missing value handling (median for numeric, 'Unknown' for categorical)
   - Label encoding and standard scaling
3. **Feature Engineering**
   - New features: Efficiency Ratio, Years Since Interconnection
   - Irrelevant features removed for cleaner modeling
4. **Model Development**
   - Models: Linear Regression, Random Forest Regressor
   - Evaluation: MAE, RMSE, R² Score
5. **Feature Importance**
   - Analyzed top contributing factors like system size and developer

---

## 🚀 Results

- **Linear Regression:** R² = 1.00 *(likely overfitting)*
- **Random Forest Regressor:** R² = 0.99
- Key Features:
  - PV System Size (kWac)
  - Developer
  - Energy Storage
  - Region

---

## 🔮 Future Work

- Validate model using real-world unseen data
- Deploy via Streamlit or Flask for user interaction
- Build a Power BI dashboard for dynamic reporting

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- Streamlit / Flask (for deployment)
- Power BI (for visualization dashboard)

---


