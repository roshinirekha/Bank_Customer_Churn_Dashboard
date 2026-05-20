# 🏦 Power BI Bank Customer Churn Dashboard

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

```DAX
Total Customers = COUNT(Customer Data[Customer ID])

Churned Customers = 
CALCULATE(
    COUNT(Customer Data[Customer ID]),
    Customer Data[Customer Status] = "Churned"
)

Churn Rate % =
DIVIDE([Churned Customers], [Total Customers]) * 100
```

Additional calculations include:

- Customer segmentation measures
- Percentage contribution analysis
- Churn distribution analysis
- Dynamic KPI calculations

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

---

# 🔍 Business Insights Generated

- Customers with lower tenure show higher churn behavior
- Certain salary/account balance groups have increased churn rate
- Customers with fewer products tend to churn more
- Credit score influences customer retention patterns

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
