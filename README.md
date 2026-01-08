# FUTURE_ML_01


## Machine Learning Internship Assignments

This repository contains multiple hands-on machine learning projects completed as part of my internship.
Each project focuses on solving a real-world business problem using data analysis, machine learning models, and business insights.

---
## 📊 Project 01: Sales Forecasting & Predictive Analytics Dashboard 
### 📌 Project Overview

This project focuses on building a sales forecasting system that helps retail businesses predict future sales using historical transaction data. The goal is to uncover sales trends, seasonality patterns, and provide actionable insights through an interactive Power BI dashboard.

The project combines time series forecasting, data analysis, and business storytelling, which are essential skills for analytics, consulting, and retail SaaS roles.

### 🎯 Business Problem

Retail businesses need accurate sales forecasts to:

Plan inventory effectively

Optimize marketing campaigns

Prepare for seasonal demand fluctuations

Improve revenue forecasting and decision-making

This project answers the question:

“Based on historical sales data, how will sales perform in the coming months?”

### 📁 Dataset

Dataset Used: Superstore Sales Dataset (or Kaggle Retail Sales / Rossmann – based on final choice)

Data Type: Historical retail transaction data

Key Fields:

Order Date

Sales

Category

Sub-Category

Region / Store

### 🧹 Data Cleaning & Preparation

The following preprocessing steps were performed using Python:

Converted order dates into datetime format

Aggregated sales data by month

Handled missing and inconsistent values

Structured the data for time series forecasting

### 🧠 Feature Engineering

Key features engineered include:

Monthly sales aggregates

Year and month indicators

Seasonal trends and patterns

(Optional) Holiday and peak-season effects

These features help the forecasting model capture seasonality and long-term trends.

### 📈 Forecasting Models

The following time series forecasting techniques were used:

Facebook Prophet – primary forecasting model

(Optional) ARIMA / Machine Learning-based approaches

Prophet was chosen for its ability to:

Handle seasonality automatically

Work well with business time series data

Produce interpretable forecasts

### 📊 Model Output

The model generates:

Future sales forecasts (e.g., next 3–6 months)

Confidence intervals

Trend and seasonality components

### 📉 Power BI Dashboard

An interactive Power BI dashboard was built to visualize insights, including:

✔ Actual vs forecasted sales trend
✔ Monthly and yearly sales comparison
✔ Filters by category, region, and segment
✔ KPI cards (Total Sales, Avg Monthly Sales, Forecasted Growth)
✔ Identification of peak and low-demand seasons

The dashboard is designed for business users and decision-makers.

### 💡 Key Business Insights

Clear seasonal patterns in retail sales

Strong sales performance during specific months

Identifiable low-sales periods requiring strategic intervention

Forecasts enable proactive inventory and marketing planning

### 📌 Business Recommendations

Based on the analysis:

Increase inventory and promotions during peak seasons

Optimize marketing spend in high-growth months

Plan cost-saving strategies during low-demand periods

Use forecasts to support data-driven sales planning

### 🛠 Tools & Technologies

Python

Pandas, NumPy

Facebook Prophet

Power BI Desktop

Jupyter Notebook
## 📌 Project 02: Customer Churn Prediction

### Objective
Build a churn prediction system to identify customers likely to stop using a service and provide actionable insights to improve customer retention.

### Dataset
- Telco Customer Churn Dataset (Kaggle)

### Models Used
- Logistic Regression (Final Model)
- Random Forest
- XGBoost

### Key Insights
- Month-to-month contracts show the highest churn risk
- High monthly charges and low tenure increase churn probability
- Long-term contracts and automatic payments reduce churn

### Project Files
- 📂 Folder: `Project_01_Churn_Prediction`
- 📘 Notebook: `Churn_Prediction_Project.ipynb`
- 📄 Report: `Churn_Prediction_Report_G_Anish_Extended.pdf`

---

## 👤 Author
**G.Anish**
