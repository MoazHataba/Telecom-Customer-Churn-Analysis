# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview

- Customer churn is a major challenge for subscription-based businesses, as losing existing customers directly impacts recurring revenue and long-term customer value.
- This project analyzes demographic, economic, contract, tenure, payment, and service-related factors to understand customer churn patterns, identify high-risk customer segments, and uncover opportunities for customer retention.
- The analysis follows a data storytelling approach, moving from understanding the overall churn problem to exploring customer behavior and segment-level risk, and finally translating analytical findings into business insights, revenue impact, and actionable retention recommendations.

---

## 🎯 Project Objectives

- Measure the overall customer churn rate and understand its business impact.
- Identify customer segments with the highest churn risk.
- Analyze the relationship between churn, contract type, tenure, and customer lifecycle.
- Understand how customer demographics and service usage relate to churn.
- Evaluate billing, monthly charges, total charges, and payment behavior.
- Assess the role of customer support and subscribed services in customer retention.
- Quantify the financial impact and revenue at risk caused by customer churn.
- Translate analytical findings into actionable customer retention strategies.

---

## 📂 Dataset

The dataset contains customer-level information covering:

- 👤 Customer Demographics
- 📅 Customer Tenure
- 📄 Contract Type
- 🌐 Internet & Phone Services
- 💳 Billing & Payment Methods
- 💰 Monthly & Total Charges
- 🎫 Technical & Administrative Support Tickets
- ❌ Customer Churn Status

### Main Dataset Features

| Feature | Description |
|---|---|
| `customerid` | Unique customer identifier |
| `gender` | Customer gender |
| `seniorcitizen` | Senior citizen indicator |
| `partner` | Whether the customer has a partner |
| `dependents` | Whether the customer has dependents |
| `tenure` | Number of months with the company |
| `phoneservice` | Phone service subscription |
| `multiplelines` | Multiple lines subscription |
| `internetservice` | Internet service type |
| `onlinesecurity` | Online security subscription |
| `onlinebackup` | Online backup subscription |
| `deviceprotection` | Device protection subscription |
| `techsupport` | Technical support subscription |
| `streamingtv` | Streaming TV subscription |
| `streamingmovies` | Streaming movies subscription |
| `contract` | Contract type |
| `paperlessbilling` | Paperless billing status |
| `paymentmethod` | Payment method |
| `monthlycharges` | Monthly customer charge |
| `totalcharges` | Total charges |
| `churn` | Customer churn status |

### Derived Features

Additional analytical features were created during the cleaning and preparation stage:

- `senior_citizen_label`
- `churn_flag`
- `tenure_group`
- `monthly_charge_band`
- `high_monthly_charge`

---

## 🛠️ Tools & Technologies

### Programming & Analysis

- Python
- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn
- Plotly

### Business Intelligence

- Microsoft Excel
- Pivot Tables
- Excel Dashboard

---

# 🖥️ Dashboard Preview

## 🏠 Landing Page

![Landing Page](Images/01_Landing_Page.jpg)

---

## 💡 Recommendations

- Prioritize Month-to-Month Customers
- Strengthen Early-Lifecycle Retention
- Reduce Electronic Check Churn
- Address Fiber Optic Churn
- Promote Security & Technical Support Services
- Target High-Value, High-Risk Customers

---

## 🙏 Thank You

---

# 📌 Key KPIs

| KPI                    |        Value |
| ---------------------- | -----------: |
| Total Customers        |        7,043 |
| Churned Customers      |        1,869 |
| Churn Rate             |       26.54% |
| Monthly Charges        |        $456K |
| Monthly Revenue Loss   |        $139K |
| Revenue Loss           |        30.5% |

---

# 🔄 Project Workflow

The project follows a business-focused analytical workflow:

The project follows a structured analytics lifecycle:

```text
Business Understanding
        ↓
Data Acquisition & Documentation
        ↓
Data Understanding
        ↓
Data Quality Assessment
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis (EDA)
        ↓
Required Business Questions
        ↓
Our Own Analytical Questions
        ↓
Diagnostic & Segmentation Analysis
        ↓
Business Impact & Prioritization
        ↓
Insight Validation
        ↓
Recommendations
        ↓
Dashboard


```


# 📁 Repository Structure

```text
Telecom-Customer-Churn-Analysis/
│
├── Dataset/
│   ├── Raw/
│   │   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│   │
│   └── Cleaned/
│       └── telco_churn_cleaned.csv
│
├── Notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_quality_assessment.ipynb
│   ├── 03_data_cleaning_preparation.ipynb
│   ├── 04_data_preprocessing.ipynb
│   └── 05_Business_Questions_Diagnostics_Insight_Validation.ipynb
│
│
├── Dashboard/
│   └── telco_churn_cleaned.xlsx
│
│
└── README.md
```
# 📌 Key Analytical Principles

- Raw data is preserved and never modified.
- Data cleaning is separated from analysis.
- EDA is descriptive and does not establish causality.
- Customer-volume thresholds are considered when ranking segments.
- Revenue exposure is analyzed alongside churn rate.
- Dashboard KPIs are selected according to the business goal.
- The dashboard is separate from the data-cleaning sheet.
- Python/Pandas is the primary analysis environment.
- SQL provides an additional validation layer.
- High-risk segments are prioritized using both **risk and business impact**.

# 🎯 Expected Business Value

The analysis can help a telecom company:

- Identify customer groups with elevated churn.
- Focus retention efforts on high-priority segments.
- Understand early-lifecycle churn.
- Investigate contract-related churn patterns.
- Identify revenue exposure caused by churn.
- Develop targeted retention strategies.
- Monitor churn KPIs through an executive dashboard.


# 🚀 Future Improvements

- Churn Prediction using Machine Learning
- Customer Lifetime Value (CLV) Modeling
- Customer Segmentation
- Automated Churn Alerts
- What-if Analysis
- Churn Risk Scoring
- Predictive Retention Modeling

# 🚀 Conclusion

This project transforms raw telecom customer data into actionable business insights through a complete data analytics workflow.

The final outcome is not simply a churn report. It provides a structured approach to:

```text
Understand
    ↓
Measure
    ↓
Diagnose
    ↓
Segment
    ↓
Prioritize
    ↓
Recommend
    ↓
Monitor
```

## 👤 Author

**Moaz Osama Esmail**
**Ziad Mohamed Mokhtar**
**Mayar Hesham Helmy**
**Seif Eldeen Tarek Abdelfatah**

Telecom Customer Churn Analysis  
Data Analytics Project


## ⭐ Project

If you found this project useful or interesting, feel free to ⭐ the repository.
