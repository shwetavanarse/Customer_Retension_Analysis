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
|---|---:|---:|---:|---:|
| Month-to-month | 3,875 | 55.0% | 1,655 | 42.7% |
| One year | 1,473 | 20.9% | 166 | 11.3% |
| Two year | 1,695 | 24.1% | 48 | 2.8% |

**Key Observations:**

- Month-to-month customers represent 55% of the total customer base.
- Approximately 88.6% of all customers who left belonged to the month-to-month contract category.
- Month-to-month customers have a churn rate of 42.7%.
- Two-year contract customers have a significantly lower churn rate of 2.8%.
- The month-to-month churn rate is approximately 15 times the two-year contract churn rate.

**Business Interpretation:**

Contract type is strongly associated with customer churn. Businesses should pay particular attention to month-to-month customers and investigate suitable retention incentives and longer-term contract options.

### 3. Customer Retention Opportunities

Based on the observed patterns, businesses could consider:

- Identifying customers with month-to-month contracts who may be at risk of leaving.
- Offering suitable incentives for longer-term subscriptions.
- Improving customer experience during the early subscription period.
- Evaluating the impact of technical support and service bundles on retention.
- Monitoring churn patterns across different customer segments.

*These are potential business recommendations based on observed associations, not proven causal relationships.*

## 💡 Business Questions Explored

- How many customers does the company currently serve?
- What percentage of customers have discontinued their services?
- Which contract category has the highest churn rate?
- How does contract duration relate to customer retention?
- How does technical support relate to customer churn?
- Does churn vary across customer demographics?
- How do combinations of subscribed services compare with churn rates?

## ⚙️ How to Run This Project

### Option 1: Google Colab

1. Download the Jupyter Notebook.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook.
4. Execute the cells sequentially.
5. Explore the analysis and recorded outputs.

### Option 2: Run Locally

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project directory:

```bash
cd customer-retention-analysis
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib scipy jupyter
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and execute the cells.

## 📁 Repository Structure

```text
Customer-Retention-Analysis/
│
├── customer_retention_analysis.ipynb
│
└── README.md
```

## 🚀 Skills Demonstrated

- Python Programming
- Exploratory Data Analysis (EDA)
- Data Manipulation using Pandas
- Numerical Analysis using NumPy
- Data Visualization
- Customer Segmentation
- Churn Rate Calculation
- Statistical Analysis
- Business Intelligence and Interpretation
- Data-Driven Decision Making

## 📌 Project Scope

This project focuses on exploratory data analysis and identifying relationships between customer characteristics and churn.

It does not include a trained machine learning prediction model. The findings represent patterns observed in the available dataset and should not be interpreted as proof of causation.

## 👩‍💻 About the Author

**Shweta Vanarse**

BCA Graduate | Data Analytics

Passionate about transforming raw data into meaningful insights and solving business problems through data analytics.

- **GitHub:** [shwetavanarse](https://github.com/shwetavanarse)
- **LinkedIn:** [Shweta Vanarse](https://www.linkedin.com/in/shweta-vanarse-aa82313b/)

---

<div align="center">

### Turning Data into Insights. Insights into Action.

**Thank you for exploring this project!**

</div>
