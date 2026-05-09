# 📊 Telecom Customer Churn Analysis using Power BI

## 🚀 Project Overview

This project analyzes telecom customer churn using Power BI to identify why customers leave and what factors influence customer retention.

The dashboard provides insights into customer demographics, service usage, billing behavior, and churn prediction using interactive visualizations and DAX measures.

---

## 🎯 Objectives

* Analyze customer churn patterns
* Identify major churn drivers
* Understand customer behavior
* Provide business recommendations to improve retention

---

## Project Overview

This project focuses on analyzing customer churn in the telecom industry using Power BI. The goal of the project is to identify the major factors causing customers to leave the company and provide business insights that can help improve customer retention.

The dashboard was built using the Telco Customer Churn dataset and includes interactive visualizations related to customer demographics, service subscriptions, billing patterns, and churn prediction.

---

# Problem Statement

Customer churn is a major challenge for telecom companies because losing customers directly impacts revenue and increases customer acquisition costs.

This project aims to answer the following questions:

* Which customers are more likely to churn?
* What factors are driving churn?
* How can the company reduce churn and improve retention?

---

# Tools & Technologies Used

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling

---

# Dataset Information

Dataset Used: Telco Customer Churn Dataset

The dataset contains information about telecom customers, including:

* Customer demographics
* Internet and phone services
* Contract type
* Payment methods
* Monthly and total charges
* Customer tenure
* Churn status

Total Records: 7,000+ customers

---

# Dashboard Pages

## Page 1 – Customer Demographics Analysis

This page focuses on understanding customer profiles and churn patterns.

### Key Insights

* Senior citizens have a higher churn rate.
* Customers in their first year show the highest churn.
* Long-term customers are more loyal.
* Gender has little impact on churn behavior.

### Visuals Used

* KPI Cards
* Pie Chart
* Stacked Column Chart
* Clustered Column Chart
* Line Chart

---

## Page 2 – Service Subscription Analysis

This page analyzes churn based on telecom services used by customers.

### Key Insights

* Fiber Optic customers have the highest churn rate.
* Customers with high monthly charges and low tenure are more likely to churn.
* Phone service alone has little impact on churn.

### Visuals Used

* Donut Chart
* Scatter Plot
* Bar Chart
* Clustered Column Chart
* Stacked Bar Chart

---

## Page 3 – Contract & Billing Insight

This page focuses on contract type, payment methods, and billing behavior.

### Key Insights

* Month-to-month customers churn significantly more.
* Long-term contracts reduce churn.
* Electronic check users show higher churn.
* Customers with longer contracts generate more revenue.

### Visuals Used

* Column Chart
* Donut Chart
* Bar Chart
* Clustered Column Chart

---

## Page 4 – Churn Prediction & Key Drivers

This page combines AI visuals and risk analysis to identify high-risk customers.

### Key Insights

* Contract type is the strongest churn driver.
* Fiber Optic users with low tenure are high-risk customers.
* Revenue loss due to churn is significant.
* High-risk customers can be targeted with retention strategies.

### Visuals Used

* Key Influencers Visual
* Decomposition Tree
* Pivot Table
* Risk Score Analysis

---

# DAX Measures Used

Some important DAX measures created in this project:

DAX
Total Customers = COUNT(Customer[customerID])

Churned Customers =
CALCULATE(COUNT(Customer[customerID]), Customer[Churn] = "Yes")

Churn Rate =
DIVIDE([Churned Customers], [Total Customers], 0)

Average Monthly Charges = AVERAGE(Customer[MonthlyCharges])


---

# Business Recommendations

Based on the analysis, the following recommendations were identified:

1. Encourage customers to move from month-to-month contracts to long-term contracts.
2. Improve Fiber Optic service quality and pricing.
3. Focus on retaining customers during their first year.
4. Provide special offers for high-risk customers.
5. Improve customer engagement and onboarding.

---

# Conclusion

This project demonstrates how Power BI can be used to transform raw telecom data into meaningful business insights.

The analysis identified contract type, internet service type, tenure, and payment method as major factors influencing customer churn.

By using interactive dashboards, DAX measures, and AI visuals, businesses can better understand customer behavior and take proactive steps to improve customer retention.

---

# Author

Rapolu.Vaishnavi

## Project Title

Telecom Customer Churn Analysis using Power BI
