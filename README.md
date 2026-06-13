# 📊 Financial-Analysis-Dashboard
# Overview

This project is an interactive Finance Analytics Dashboard built in Power BI to analyze transaction data and provide business insights related to revenue, fees, taxes, customer segments, and transaction performance.

The dashboard enables stakeholders to monitor financial KPIs, identify trends, and drill down into transaction-level details for deeper analysis.

Dashboard Preview
Overview Analysis

<img width="1181" height="642" alt="image" src="https://github.com/user-attachments/assets/8da03675-f7a2-4329-94c7-ed937e52833f" />


Transaction Details

<img width="1640" height="841" alt="image" src="https://github.com/user-attachments/assets/399af26c-d82c-4562-a9fe-b7fdae39c70a" />


# Business Problem

Financial institutions process thousands of transactions daily. Decision-makers need a centralized dashboard to:

Monitor transaction performance
Track fee and tax collections
Analyze customer behavior
Identify transaction trends
Review detailed transaction records

This dashboard addresses these requirements through interactive visualizations and dynamic filtering.

Key KPIs
Total Amount
Total Transactions
Average Transaction Value
Total Fee
Total Tax
Features
Executive Overview Dashboard
KPI Cards
Monthly Fee Trend Analysis
Transaction Status Analysis
Customer Segment Analysis
State-wise Fee Analysis
Transaction Type Analysis
Gender-based Transaction Analysis
Transaction Detail Dashboard
Transaction-Level Reporting
Searchable Data Table
Interactive Filtering
Drill-through Navigation
Filters

Users can dynamically filter the report using:

Year
Dynamic Metric Selection
Occupation
Category
Power BI Skills Demonstrated
Data Preparation
Power Query
Data Cleaning
Data Transformation
Data Modeling
Star Schema Concepts
Relationships
Data Types Optimization
DAX

Examples of measures used:

Total Amount =
SUM(Transactions[Amount])

Total Fee =
SUM(Transactions[Fee])

Total Tax =
SUM(Transactions[Tax])

Total Transactions =
COUNTROWS(Transactions)

Average Transaction Value =
DIVIDE([Total Amount],[Total Transactions])
Visualizations Used
KPI Cards
Line Chart
Donut Chart
Bar Chart
Matrix/Table
Slicers
Navigation Buttons
Tools Used
Power BI Desktop
Power Query
DAX
Excel/CSV Dataset
Project Learnings

Through this project I improved my understanding of:

Data Modeling
DAX Calculations
Dashboard Design
Business Intelligence Reporting
Data Storytelling
Interactive User Experience Design
Future Improvements
Row Level Security (RLS)
Dynamic Date Intelligence
Advanced DAX Measures
Mobile Layout Optimization
Drill-through Enhancements
Author

Namrata Choudhary

API Developer transitioning into Data Analytics

LinkedIn:https://www.linkedin.com/in/namrata1choudhary/

