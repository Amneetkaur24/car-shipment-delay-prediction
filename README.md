# 🚗 Predicting Car Shipment Delays – Full Data Science Project

## 📌 Overview

This project aims to help supply chain teams reduce car shipment delays, anticipate costs, and make proactive logistics decisions using machine learning and data visualization. We handle not only whether a shipment will be delayed, but also **how many days** and the **financial impact** of such delays.

It includes:
- Classification Model – Predicts if a shipment will be delayed.
- Regression Model 1 – Predicts the number of delay days.
- Regression Model 2 – Predicts the financial cost of the delay.
- Streamlit App – For easy prediction using trained models.
- Power BI Dashboard – Summarizes insights and business recommendations.

---

## 🧠 Machine Learning Models

Each model was developed and tested with baseline and tuned versions using algorithms like:
- **Random Forest**
- **CatBoost**
- **XGBoost**
- **Linear Regression** (for benchmarking)

### 🔍 Key Steps:
- **Data Cleaning & Preprocessing**
- **EDA (Exploratory Data Analysis)**
- **Feature Engineering** (including outlier removal, log transforms, label encoding, etc.)
- **Model Training & Evaluation** (using MAE, RMSE, R², Accuracy, etc.)
- **Feature Importance** visualization

---

## 📊 Power BI Dashboard

Includes a 6-page interactive dashboard with:
- Executive Summary
- Delay Insights by Part, Region, and Supplier
- Cost Implications
- Shipment Trends
- Model Results
- Business Insights & Recommendations

Tools Used:
- Power Query (Data cleaning and transformation)
- DAX (Custom metrics and logic)
- Relationship building and custom table creation

---

## 🌐 Streamlit App

A simple app to use all three models:
- Input shipment details
- Get delay classification
- Get predicted delay days
- Get estimated cost of delay

[Click on the link to use the app](https://car-shipment-delay-prediction-8gxekgz52yqxspeqtu8svv.streamlit.app/)

---

## 📁 Repository Structure

car-shipment-delay-prediction/
│
├── data/
│   ├── raw_shipment_data.csv
│   └── clean_shipment_data.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_feature_eng_classification.ipynb
│   ├── 04_feature_eng_regression_days.ipynb
│   ├── 05_feature_eng_regression_cost.ipynb
│   ├── 06_model_classification.ipynb
│   ├── 07_model_regression_days.ipynb
│   ├── 08_model_regression_cost.ipynb
│
├── app/
│   ├── streamlit_app.py
│   └── models/
│       ├── delay_classifier.pkl
│       ├── delay_days_model.pkl
│       └── cost_prediction_model.pkl
│
├── powerbi_dashboard/
│   ├── car_delay_dashboard.pbix
│   └── powerbi_assets/
│
├── reports/
│   └── final_project_report.pdf
│
├── presentation/
│   └── car_delay_presentation.pptx
│
├── requirements.txt
├── README.md
└── .gitignore
---

## 📦 Tools & Technologies

- Python (Pandas, Scikit-learn, CatBoost, XGBoost, Matplotlib, Seaborn)
- Power BI
- Streamlit
- Jupyter Notebook

---

## ✍️ Author

**Amneet Kaur**  
_Data Scientist & Analyst | Focused on Real-World Impact_  
📧 [amneet1224@gmail.com]  
📂 [linkedin.com/in/amneetkaur24]

---
