# 🏦 Bank Customer Churn Dashboard Using Power BI

## Interactive Customer Churn Analysis Dashboard

This project showcases an end-to-end Power BI dashboard designed to analyze customer churn behavior in the banking sector. The dashboard transforms raw customer banking data into meaningful business insights using Power BI, DAX, and data visualization techniques.

The dashboard helps identify customer retention trends, churn patterns, account balance behavior, and customer segmentation insights for better business decision-making.

---

# 🎯 Project Objective

To create an interactive analytics dashboard that:

- Tracks customer churn KPIs
- Identifies high-risk churn customer groups
- Analyzes churn based on tenure, salary, products, and credit score
- Provides dynamic filtering and business insights
- Supports customer retention strategy analysis

---

# 🛠️ Technical Overview

## Tools & Technologies Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query (ETL)
- Data Visualization
- Simulated Banking Customer Dataset

---

## Core DAX Measures Implemented

## 🧮 Core DAX Measures Implemented

- Total Customers = COUNT(Customer ID)

- Churned Customers = CALCULATE(COUNT(Customer ID), Churn Status = "Churned")

- Churn Rate % = DIVIDE([Churned Customers], [Total Customers]) * 100

- Stayed Customers = CALCULATE(COUNT(Customer ID), Churn Status = "Not Churned")

- Average Account Balance = AVERAGE(Account Balance)

- Average Credit Score = AVERAGE(Credit Score)

- ### Customer Segmentation using calculated groups:
  - Age Groups
  - Credit Score Groups
  - Account Balance Groups
  - Tenure Groups

- ### Conditional churn analysis using:
  - Product-wise customer analysis
  - Salary and balance segmentation
  - Credit score retention analysis
  - Active vs inactive customer comparison

- ### Dynamic filtering and interactivity using slicers:
  - Country
  - Gender
  - Activity Status
  - Account Balance

---

# 🧱 Data Model

The dashboard uses a structured data model with:

## Fact Table
- Customer Data

## Key Attributes
- Customer ID
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Products
- Salary
- Churn Status

---

# 📊 Dashboard Features

## KPI Cards
- Total Customers
- Churned Customers
- Churn Rate %

## Visualizations
- Product Analysis
- Credit Score Analysis
- Tenure Analysis
- Account Balance Analysis

## Interactive Features
- Dynamic slicers
- Cross filtering
- Interactive visuals
- Responsive dashboard layout

---

# 📷 Dashboard Preview

## Main Dashboard

![Dashboard Preview](Dashboard%201.png)
![Dashboard Preview](Dashboard%202.png)
---

# 🔍 Business Insights Generated

- Customers with 3+ products show higher churn probability
- Customers with lower credit scores are more likely to churn
- High account balance customers contribute significantly to churn
- Mid-tenure customers show relatively stable retention
- Salary and balance segmentation helps identify churn-prone groups

---

# 💼 Business Value

This dashboard helps businesses:

- Understand customer retention trends
- Identify churn-prone customer segments
- Improve retention strategy planning
- Make data-driven business decisions

---

# 🌐 Use Case

This project is suitable for:

- Banking analytics
- Customer retention analysis
- Business intelligence portfolios
- Data analyst portfolio projects

---

# 📌 License & Disclaimer

This is a self-built portfolio project developed for educational and learning purposes using a simulated banking customer dataset.

---

# 🙌 Author

### Roshini R

Aspiring Data Analyst | Power BI | SQL | Python
