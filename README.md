# customer_behavior_analysis
📊 Data Analytics Project – End-to-End Business Insights

🔍 Overview
This project demonstrates an end-to-end data analytics workflow, starting from raw data ingestion to delivering business insights through SQL analysis and an interactive Power BI dashboard.
The objective is to analyze customer purchasing behavior, product performance, and revenue trends to support data-driven decision-making.

📂 Dataset
The dataset contains customer purchase and product-related information, including:
Customer ID
Product category and item purchased
Purchase amount
Discount applied (Yes/No)
Review rating
Subscription status
Previous purchase count
The dataset was loaded and explored using Python, then stored and queried using relational databases.


🛠️ Tools & Technologies
Python – Data loading, EDA, and data cleaning
Pandas, NumPy, Matplotlib, Seaborn
SQL – Data analysis and querying
PostgreSQL / MySQL / SQL Server
CTEs, Joins, Window Functions
Power BI – Data modeling, DAX measures, dashboard creation
Power Query – Data transformation
GitHub – Version control and project documentation

🔄 Project Workflow / Steps
Data Loading (Python)
Loaded raw dataset using Pandas
Verified schema, data types, and basic statistics
Exploratory Data Analysis (EDA)
Identified patterns, outliers, and trends
Analyzed distributions, correlations, and missing values
Data Cleaning
Handled missing and inconsistent values
Converted data types (ratings, numeric fields)
Removed duplicates and standardized fields
Database Integration
Loaded cleaned data into relational databases

Executed analytical SQL queries using:
Aggregations
CASE statements
CTEs
Window functions (ROW_NUMBER, RANK)

Power BI Dashboard
Created DAX measures for KPIs
Built interactive visuals and slicers
Enabled category-wise and product-wise analysis
Reporting & Presentation
Created a structured analytics report
Designed a business-focused presentation using Gamma

📊 Power BI Dashboard Highlights
KPI Cards:
Total Revenue
Total Orders
Average Spend
Discount Rate (%)

Top products by category
Revenue comparison by subscription status
Customer segmentation (New, Returning, Loyal)
Interactive slicers for dynamic analysis


📈 Key Results & Insights
Identified top-performing products within each category
Analyzed discount dependency across products
Compared revenue contribution by subscription status
Segmented customers based on purchase behavior
Highlighted opportunities for targeted marketing and pricing strategies
