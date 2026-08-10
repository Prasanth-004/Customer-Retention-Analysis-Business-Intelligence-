Customer Retention Analysis Using Power BI



📌 Project Overview

Customer Retention Analysis Using Power BI is a Business Intelligence project focused on understanding customer behavior, retention patterns, and customer churn.

The project uses the Telco Customer Churn dataset and applies Power Query for data cleaning and transformation, DAX for calculated measures and KPIs, and Microsoft Power BI for interactive dashboard development.

The objective is to transform raw customer information into meaningful business insights that can help organizations identify high-risk customers, understand customer loyalty patterns, improve customer satisfaction, and support data-driven decision-making.

🎯 Objectives

Analyze customer retention and churn trends.

Identify factors influencing customer loyalty and churn.

Study customer demographics and service usage patterns.

Analyze the impact of contract types, tenure, payment methods, and internet services.

Monitor business performance using interactive KPI indicators.

Identify customer segments with higher churn risk.

Provide business insights that can support customer retention strategies.

📊 Dataset

The project uses the Telco Customer Churn dataset.

Dataset Summary

Records: Approximately 7,043 customer records

Attributes: 21

Target: Churn

Format: CSV

Main data categories:

Customer demographics

Tenure

Contract type

Payment method

Internet service

Service usage

Monthly charges

Total charges

Churn status

Important Columns

Column

Description

customerID

Unique customer identifier

gender

Customer gender

SeniorCitizen

Senior citizen indicator

Partner

Whether the customer has a partner

Dependents

Whether the customer has dependents

tenure

Number of months with the company

PhoneService

Phone service subscription

InternetService

Internet service type

OnlineSecurity

Online security subscription

OnlineBackup

Online backup subscription

DeviceProtection

Device protection subscription

TechSupport

Technical support subscription

StreamingTV

Streaming TV subscription

StreamingMovies

Streaming movies subscription

Contract

Contract duration/type

PaperlessBilling

Paperless billing status

PaymentMethod

Customer payment method

MonthlyCharges

Monthly customer charges

TotalCharges

Total customer charges

Churn

Whether the customer discontinued the service

🛠️ Technology Stack

Microsoft Power BI – Dashboard development and visualization

Power Query – Data cleaning and transformation

DAX (Data Analysis Expressions) – Measures, calculated columns, and KPIs

CSV / Excel – Customer dataset source

Power BI Desktop – Report development

🔄 Project Workflow

Customer Dataset
       ↓
Data Collection
       ↓
Data Cleaning & Transformation
       ↓
Power Query
       ↓
Data Modeling
       ↓
DAX Measures & KPI Creation
       ↓
Power BI Dashboard Development
       ↓
Customer Retention & Churn Analysis
       ↓
Business Insights & Decision Making

🧹 Data Preparation

Power Query is used to prepare the customer data before analysis.

The preprocessing workflow includes:

Removing duplicate records

Handling missing or null values

Correcting data types

Renaming fields where required

Removing unnecessary fields

Filtering and transforming records

Preparing a structured dataset for analysis

📐 DAX & KPI Analysis

The dashboard uses DAX to create dynamic business metrics.

Key KPIs

Total Customers

Active Customers

Churned Customers

Customer Churn Rate

Customer Retention Rate

Average Monthly Charges

Customer Lifetime Value, where applicable

These measures dynamically respond to dashboard filters and slicers.

📊 Dashboard Features

The Power BI dashboard uses multiple visualization types to make customer analysis easier.

Visualizations

KPI Cards

Bar Charts

Pie Charts

Donut Charts

Line Charts

Tables

Matrix Visuals

Interactive Slicers

Filters

Interactive Capabilities

Customer segmentation

Cross-filtering

Drill-down analysis

Dynamic KPI indicators

Filtering by demographics

Filtering by contract type

Filtering by payment method

Filtering by tenure

Filtering by service category

🔎 Analysis Areas

1. Customer Profile Analysis

Analyzes customer demographics and characteristics to understand the customer base.

2. Customer Behavior Analysis

Examines tenure, services, contracts, payment methods, and other customer attributes.

3. Customer Retention Analysis

Compares active and churned customers and evaluates retention behavior across different customer segments.

4. Customer Churn Analysis

Analyzes churn percentage and churn patterns across:

Contract types

Payment methods

Customer tenure

Internet services

Customer segments

5. Business Insights

The dashboard helps identify:

High-risk customers

Customer loyalty patterns

Important customer segments

Payment preferences

Customer behavior patterns

Areas requiring retention-focused action

💡 Business Value

The project demonstrates how Business Intelligence can convert raw customer information into actionable business insights.

The dashboard can help organizations:

Identify customers at risk of churn

Improve customer retention strategies

Understand customer behavior

Improve customer relationship management

Enhance customer satisfaction

Reduce manual reporting effort

Monitor KPIs efficiently

Support data-driven business decisions

📁 Suggested Repository Structure

customer-retention-analysis-powerbi/
│
├── data/
│   └── Customer-Churn-data.csv
│
├── dashboard/
│   └── Customer Retention Analysis1.pbix
│
├── screenshots/
│   ├── executive-dashboard.png
│   ├── customer-profile.png
│   ├── customer-behavior.png
│   └── retention-analysis.png
│
├── documentation/
│   ├── project-report.pdf
│   └── presentation.pdf
│
└── README.md

Note: Rename the dashboard screenshot files according to the actual screenshots you upload to GitHub.

▶️ How to Run the Project

Prerequisites

Install:

Microsoft Power BI Desktop

Git (optional, for repository management)

Steps

Clone or download this repository.

Open Microsoft Power BI Desktop.

Open:

dashboard/Customer Retention Analysis1.pbix

If required, update the CSV file path in Power Query.

Refresh the dataset.

Navigate through the dashboard pages.

Use slicers and filters to explore customer retention and churn patterns.

📈 Project Outcomes

The project successfully demonstrates:

Customer data preparation using Power Query.

KPI creation using DAX.

Interactive dashboard development using Power BI.

Analysis of churn across contract, tenure, internet service, and payment method.

Customer segmentation and high-risk customer identification.

Dynamic reporting for business decision-making.

🚀 Future Enhancements

The project can be extended with:

Real-time data integration using SQL or cloud databases.

Machine Learning models for predictive churn analysis.

Customer segmentation using advanced analytics.

Sentiment analysis using customer feedback and reviews.

Automated Power BI data refresh.

Mobile dashboard support.

Row-Level Security (RLS).

Additional KPIs such as Customer Lifetime Value (CLV), Customer Acquisition Cost (CAC), Net Promoter Score (NPS), and Repeat Purchase Rate.

AI-powered Power BI visuals and advanced drill-through reports.

👥 Team

This project was developed as part of the Data Analytics Using Power BI internship/project work at GIET Engineering College A.P.

Team Member

Roll Number

Vandana Durga Prasanth

23T91A05D8

Chintam Srivyshnavi

23T91A0519

Thalam Chandhanasarika

23T91A05D0

Undi Navya Keerthi

23T91A05D3

🎓 Project Context

The project was prepared as part of the Summer Internship Program on Data Analytics Using Power BI, with guidance from Anji Reddy Bapathu, M.Tech. (Ph.D.), and was submitted in July 2026.

📚 References

Microsoft Power BI Documentation

Microsoft Power Query Documentation

Microsoft DAX Documentation

Telco Customer Churn Dataset

IBM Customer Retention resources

⭐ Conclusion

Customer Retention Analysis Using Power BI provides an interactive Business Intelligence approach to understanding customer churn and retention. By combining data preprocessing, data modeling, DAX-based KPI analysis, and interactive visualization, the project transforms customer data into business-focused insights that can support better retention strategies and long-term organizational growth.
