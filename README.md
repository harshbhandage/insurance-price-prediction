# 🏥 Health Insurance Price Prediction

This project uses machine learning to predict health insurance charges based on personal attributes like age, BMI, and smoking status. It includes a Power BI dashboard for data visualization and model performance insights.

---

## 📊 Dashboard Overview

![Dashboard Screenshot](visuals/Dashboard_screenshot.png)

**Highlights:**
- **R² Score**: 0.93
- **RMSE**: $3.29K
- **Total Users**: 1338
- Predictive insights across **age**, **BMI groups**, and **smoking status**

---

## 📁 Project Structure

insurance-price-prediction/
├── data/
│ ├── insurance.csv # Raw dataset
│ └── insurance_predictions_all.xlsx# Model predictions
├── visuals/
│ └── Dashboard_screenshot.png # Power BI screenshot
├── dashboard/
│ └── insurance_dashboard.pbix # Power BI file
├── insurance.ipynb # Jupyter Notebook (ML model)
├── README.md # This file
└── .gitignore

---

## 🔍 Dataset

The dataset `insurance.csv` includes:
- `age`: Age of the individual
- `sex`: Gender
- `bmi`: Body Mass Index
- `children`: Number of children
- `smoker`: Smoking status
- `region`: Residential region
- `charges`: Medical costs billed by health insurance

---

## 🤖 Machine Learning

Model built using **scikit-learn** with the following steps:

- Data Cleaning and Exploration
- Feature Engineering
- Train-test Split
- Model Training (Linear Regression / Random Forest / etc.)
- Evaluation Metrics: `R²`, `RMSE`, residual analysis

📌 Best model achieved:
- **R² Score**: 0.93
- **RMSE**: \$3.29K

---

## 📈 Power BI Dashboard

Power BI visualizes:
- Actual vs. Predicted charges by BMI, Age, Smoking status
- Distribution and trends
- Performance summary

🗂 File: `dashboard/insurance_dashboard.pbix`

---
