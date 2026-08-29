# 📊 Telco Customer Churn Analysis

> An end-to-end **Business Intelligence and Data Analytics project** built with **Power BI** to analyze customer churn, identify high-risk customer segments, understand revenue impact, and translate data-driven insights into actionable retention strategies.

---

## 📌 Project Overview

Customer churn is a major challenge for subscription-based businesses, as losing existing customers directly affects recurring revenue and long-term customer value.

This project analyzes customer demographics, contracts, tenure, charges, payment methods, services, and support interactions to understand customer churn patterns and identify opportunities for customer retention.

The dashboard was designed around a **storytelling approach**, moving from understanding the overall churn problem to exploring customer characteristics, service and payment behavior, and finally translating the findings into business recommendations.

---

## 🎯 Business Objectives

- Measure the overall customer churn rate.
- Identify customer segments with higher churn rates.
- Analyze the relationship between churn, contract type, and customer tenure.
- Understand customer characteristics and service usage patterns.
- Analyze billing, charges, and payment behavior.
- Examine customer support interactions.
- Measure the financial impact of customer churn.
- Translate analytical findings into actionable retention recommendations.

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

---

## 🛠️ Tools & Technologies

- 📊 Power BI
- ⚡ DAX
- 🔄 Power Query
- 🗄️ Data Modeling
- 📈 Data Visualization
- 💼 Business Intelligence
- 📖 Dashboard Storytelling

---

# 🖥️ Dashboard Preview

## 🏠 Landing Page

![Landing Page](Images/01_Landing_Page.jpg)

The landing page introduces the project and provides navigation into the analytical report.

---

## 📊 Executive Overview

![Executive Overview](Images/02_Executive_Overview.jpg)

The Executive Overview provides a high-level view of the churn problem through key business KPIs and the most important churn patterns.

### Key findings

- **27% overall churn rate**
- **43% churn rate among month-to-month customers**
- Churned customers have a substantially shorter average tenure than retained customers.
- Monthly revenue loss reaches approximately **$139K**.

---

## 👥 Customer Profile

![Customer Profile](Images/03_Customer_Profile.jpg)

This page explores the characteristics of the customer base, including:

- Gender
- Age group
- Partner status
- Dependents
- Churn vs. Retained customer segments

The page also allows users to interactively explore customer characteristics by churn status.

---

## 🎫 Customer Support Analysis

![Tickets](Images/04_Tickets.jpg)

This page examines customer support interactions through:

- Technical support tickets
- Administrative tickets
- Churn status

The analysis helps identify customer service patterns that may require further investigation from a retention perspective.

---

## 💰 Charges Analysis

![Charges](Images/05_Charges.jpg)

This page analyzes:

- Monthly Charges
- Total Charges
- Revenue contribution
- Revenue loss
- Churn status

The objective is to understand the financial dimension of customer churn.

---

## 💳 Payment Analysis

![Payments](Images/06_Payments.jpg)

This page explores customer payment behavior through:

- Payment methods
- Paperless billing
- Customer churn
- Customer distribution

---

## 🌐 Services Analysis

![Services](Images/07_Services.jpg)

This page analyzes customer service subscriptions, including:

- Internet Service
- Phone Service
- Multiple Lines
- Online Security
- Online Backup
- Device Protection
- Tech Support

The analysis helps identify service patterns associated with different customer segments.

---

## 💡 Recommendations

![Recommendations](Images/08_Recommendations.jpg)

The final page translates the analytical findings into actionable business strategies.

### 01 | Contract Strategy

**43% churn among month-to-month customers.**

Encourage customers to move to longer-term contracts through targeted upgrade offers and loyalty incentives.

**Expected Impact:**
Reduce churn and improve customer retention.

### 02 | Early-Tenure Retention

**Churned customers have an average tenure of 17.98 months vs. 37.57 months for retained customers.**

Strengthen onboarding and introduce proactive retention programs during the early stages of the customer relationship.

**Expected Impact:**
Increase early-stage retention and reduce avoidable churn.

### 03 | Revenue Protection

**$139K monthly revenue loss, representing 30.5% of monthly revenue.**

Prioritize high-value customers for targeted retention campaigns based on their revenue contribution and churn risk.

**Expected Impact:**
Protect recurring revenue and minimize revenue loss.

### 04 | Service Experience

**Repeated administrative or technical tickets can indicate potential customer friction.**

Monitor customers with repeated tickets and proactively resolve recurring service issues before they escalate.

**Expected Impact:**
Improve customer satisfaction and reduce potential churn risk.

### 05 | Payment Experience

**Payment and billing behavior should be monitored across churn-risk segments.**

Identify payment and billing patterns associated with higher churn and simplify the payment experience for high-risk customer segments.

**Expected Impact:**
Reduce payment-related friction and support customer retention.

---

## 🙏 Thank You

![Thank You](Images/09_Thanks_Page.jpg)

---

# 📌 Key KPIs

| KPI                    |        Value |
| ---------------------- | -----------: |
| Total Customers        |        7,043 |
| Churned Customers      |        1,869 |
| Churn Rate             |          27% |
| Monthly Charges        |        $456K |
| Monthly Revenue Loss   |        $139K |
| Revenue Loss           |        30.5% |
| Avg. Tenure – Retained | 37.57 months |
| Avg. Tenure – Churned  | 17.98 months |

---

# 💡 Key Insights

### 1. Contract Type

Month-to-month customers show the highest churn rate at **43%**, compared with **11%** for one-year contracts and **3%** for two-year contracts.

### 2. Customer Tenure

Churned customers have a considerably lower average tenure than retained customers, indicating that early customer lifecycle stages deserve greater retention attention.

### 3. Revenue Impact

Customer churn has a significant financial impact, with approximately **$139K in monthly revenue loss** represented in the analysis.

### 4. Customer Experience

Support interactions and service-related behavior provide additional dimensions for understanding customer churn and identifying customers who may require proactive attention.

---

# 📈 Business Recommendations

Based on the analysis, the main recommended actions are:

- Encourage migration from month-to-month to longer-term contracts.
- Strengthen onboarding and early-tenure retention programs.
- Prioritize high-value customers for targeted retention campaigns.
- Monitor repeated support interactions as potential early-warning signals.
- Review payment and billing patterns among high-risk customer segments.
- Use customer-level segmentation to support targeted retention strategies.

---

# 🧠 Analytical Approach

The project follows a business-focused analytical workflow:

**Business Problem**
↓
**Data Preparation**
↓
**Data Modeling**
↓
**KPI Development**
↓
**Exploratory Analysis**
↓
**Dashboard Storytelling**
↓
**Key Insights**
↓
**Business Recommendations**

The dashboard was designed to answer:

> **What is happening? → Who is affected? → Where is churn concentrated? → What is the business impact? → What should we do next?**

---

# 📚 Skills Demonstrated

- Business Analysis
- Data Cleaning
- Power Query
- Data Modeling
- DAX Development
- KPI Development
- Customer Segmentation
- Data Visualization
- Dashboard Design
- Dashboard Storytelling
- Business Intelligence
- Insight Generation
- Business Recommendations

---

# 📁 Repository Structure

```text
Telco-Customer-Churn/
│
├── Dataset/
│   └── Telco_Customer_Churn.xlsx
│
├── Power BI Report/
│   └── Telco_Customer_Churn.pbix
│
├── Images/
│   ├── 01_Landing_Page.jpg
│   ├── 02_Executive_Overview.jpg
│   ├── 03_Customer_Profile.jpg
│   ├── 04_Tickets.jpg
│   ├── 05_Charges.jpg
│   ├── 06_Payments.jpg
│   ├── 07_Services.jpg
│   ├── 08_Recommendations.jpg
│   └── 09_Thanks_Page.jpg
│
└── README.md
```

---

# 🚀 Future Improvements

- Churn Prediction using Machine Learning
- Customer Lifetime Value (CLV) Modeling
- Customer Segmentation
- Automated Churn Alerts
- What-if Analysis
- Churn Risk Scoring
- Predictive Retention Modeling

---

# 👩‍💻 About Me

Hi! I'm **Eman Mahmoud**, a **Data Analyst** with a background in Computer Engineering and a strong interest in Data Analytics and Business Intelligence.

I am currently pursuing a **Professional Master's in Data Analysis at Cairo University – fgssr**.

My analytical toolkit includes:

**Power BI | SQL | Python | R | SPSS | EViews | Excel**

I am passionate about transforming data into meaningful insights and building analytical solutions that support better business decisions.

---

## ⭐ Project

If you found this project useful or interesting, feel free to ⭐ the repository.
