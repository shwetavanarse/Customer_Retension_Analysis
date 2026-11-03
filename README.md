# Customer_Retension_Analysis

 <div align="center">

# 📊 Customer Retention & Churn Analysis

### Understanding Customer Behavior | Identifying Churn Patterns | Driving Retention Strategies

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)

**An Exploratory Data Analysis (EDA) project focused on understanding customer churn in the telecommunications industry using Python.**

</div>

---

## 📌 Project Overview

Customer retention is one of the most important challenges faced by subscription-based businesses. Losing existing customers can impact recurring revenue, profitability, and long-term business growth.

This project analyzes customer churn patterns using the IBM Telco Customer Churn dataset. The objective is to understand customer behavior, identify factors associated with customer attrition, and uncover meaningful business insights that can support better customer retention strategies.

Using Python and statistical analysis, the project explores customer demographics, subscribed services, contract types, technical support, and billing information to understand how different customer characteristics relate to churn.

## 🎯 Business Objectives

- Calculate the total customer base and overall churn rate.
- Identify the number and percentage of customers who left.
- Analyze customer distribution across different contract types.
- Compare churn rates across month-to-month, one-year, and two-year contracts.
- Investigate the relationship between technical support and customer churn.
- Explore churn patterns across customer demographics.
- Analyze service combinations and their relationship with customer attrition.
- Convert analytical findings into actionable business recommendations.

## 📂 Dataset Information

| Attribute | Description |
|---|---|
| Dataset | IBM Telco Customer Churn |
| Total Records | 7,043 |
| Total Columns | 21 |
| Target Variable | Churn |
| Industry | Telecommunications |

**Dataset Source:** [IBM Telco Customer Churn Dataset](https://github.com/IBM/telco-customer-churn-on-icp4d/blob/master/data/Telco-Customer-Churn.csv)

### Key Dataset Features

| Category | Features |
|---|---|
| Customer Demographics | Gender, SeniorCitizen, Partner, Dependents |
| Account Information | Tenure, Contract, PaperlessBilling |
| Core Services | PhoneService, InternetService, MultipleLines |
| Support Services | OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport |
| Entertainment | StreamingTV, StreamingMovies |
| Billing Information | MonthlyCharges, TotalCharges, PaymentMethod |
| Target | Churn |

## 🛠️ Tools & Technologies

- **Python:** Primary programming language.
- **Pandas:** Data manipulation, grouping, and analysis.
- **NumPy:** Numerical calculations.
- **Matplotlib:** Data visualization.
- **SciPy:** Statistical analysis.
- **Google Colab:** Development environment.

## 🔍 Project Workflow

1. **Data Collection:** Imported the IBM Telco Customer Churn dataset using Pandas.
2. **Data Understanding:** Examined dataset dimensions, columns, and sample records.
3. **Customer Segmentation:** Grouped services into core services, entertainment, and support categories.
4. **Exploratory Data Analysis:** Investigated customer characteristics and churn distribution.
5. **Churn Analysis:** Calculated customer churn counts, percentages, and overall churn rate.
6. **Contract Analysis:** Compared customer distribution and churn rates across contract categories.
7. **Service Analysis:** Explored how technical support and subscribed services relate to churn.
8. **Demographic Analysis:** Investigated customer churn across demographic groups.
9. **Business Insights:** Interpreted findings and identified potential customer retention opportunities.

## 📈 Key Business Insights

### 1. Overall Customer Churn

| Metric | Value |
|---|---:|
| Total Customers | 7,043 |
| Customers Who Left | 1,869 |
| Customers Who Stayed | 5,174 |
| Overall Churn Rate | 26.5% |

**Insight:** Approximately 26.5% of customers discontinued their services, highlighting the importance of customer retention strategies.

### 2. Contract Type vs Customer Churn

| Contract Type | Customers | Customer Share | Customers Lost | Churn Rate |
|---|---:|---:|---
