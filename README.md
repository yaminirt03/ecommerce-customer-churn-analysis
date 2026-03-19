# E-Commerce Customer Churn Analysis Dashboard

## 📌 Problem Statement

Customer churn is a major challenge for e-commerce businesses, directly
impacting revenue and growth.\
Many organizations lack clear visibility into *why customers leave*,
making it difficult to take proactive action.

This project aims to analyze customer churn patterns and provide
actionable insights to improve retention strategies.

------------------------------------------------------------------------

## 📊 Overview

The **E-Commerce Customer Churn Analysis Dashboard** is built using
Power BI to visualize churn trends, customer behavior, and risk factors.

### Key Metrics

-   Total Customers: 6,000\
-   Churned Customers: 948\
-   Churn Rate: 16.84%\
-   Customer Satisfaction Score Analysis

------------------------------------------------------------------------

## 📂 Dataset Description

-   Records: 6,000 customers\
-   Features:
    -   Customer ID
    -   Gender
    -   City Tier
    -   Tenure
    -   Preferred Payment Mode
    -   Order Category
    -   Satisfaction Score
    -   Churn Status

*(Dataset can be from Kaggle / sample dataset)*

------------------------------------------------------------------------

## 📈 Dashboard Features

### KPI Cards

-   Total Customers\
-   Churn Customers\
-   Churn Rate\
-   Satisfaction Score

### Visualizations

-   Churn by Tenure\
-   Churn by Gender\
-   Churn by City Tier\
-   Churn by Payment Mode\
-   Churn by Product Category

------------------------------------------------------------------------

## 🧮 Key DAX Measures

-   Churn Rate = Churn Customers / Total Customers\
-   Total Customers = COUNT(Customer ID)\
-   Churn Customers = CALCULATE(COUNT(Customer ID), Churn = "Yes")

------------------------------------------------------------------------

## 💡 Key Insights

-   High churn observed in early tenure (month 0)\
-   Male customers show higher churn\
-   Debit card users have the highest churn\
-   Tier 1 cities contribute most to churn

------------------------------------------------------------------------

## 🎯 Business Recommendations

-   Improve onboarding experience\
-   Optimize payment systems\
-   Target high-risk customer segments\
-   Create personalized retention campaigns

------------------------------------------------------------------------

## 🚀 Future Enhancements

-   Machine Learning churn prediction model\
-   Real-time dashboard updates\
-   Customer segmentation using clustering

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   Power BI\
-   SQL\
-   DAX

------------------------------------------------------------------------

## 📷 Dashboard Preview

[View Dashboard](E-Commerce Customer Churn Dashboard Image.jpeg)

------------------------------------------------------------------------

## ▶️ How to Use

1.  Open the Power BI (.pbix) file\
2.  Load dataset\
3.  Refresh data\
4.  Interact with filters and visuals

------------------------------------------------------------------------

## 📄 License

For educational and portfolio use.

------------------------------------------------------------------------

## 👩‍💻 Author

Yamini T
