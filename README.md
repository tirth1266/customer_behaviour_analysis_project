# Customer Behavior Analysis – End-to-End Data Analytics Project
📌 Overview

This project provides a complete end-to-end data analytics workflow to understand customer shopping behaviour.
It covers Python-based EDA, data cleaning, SQL analysis using PostgreSQL/MySQL/SQL Server, and an interactive Power BI dashboard, followed by a structured analytics report and a presentation created using Gamma.

The goal is to uncover insights on purchase patterns, customer segments, product categories, and revenue drivers to support data-driven decision-making.

📂 Dataset

Total Records: ~3,900
Columns: 18
Data Includes:

Customer demographics (Age, Gender, Subscription Status, Location)

Shopping behaviour (Previous purchases, frequency, shipping type)

Purchase details (Category, Amount, Discount, Season, Size, Colour)

Review ratings & promo usage

Key Issues Identified:

Missing values (mainly in review ratings)

Inconsistent column naming

Redundant fields requiring cleaning and standardisation

🛠 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) – EDA & data cleaning

PostgreSQL / MySQL / SQL Server – SQL queries & analytics

Power BI – Interactive visualisation & dashboard

Gamma – Automated presentation slides

Jupyter Notebook – Data exploration

GitHub – Version control & documentation

📘 Project Steps
1. Data Loading (Python)

Imported dataset using Pandas

Performed initial inspection using .info(), .head(), .describe()

Converted column names to readable snake_case format

2. Data Cleaning

Imputed missing ratings using category-wise median

Removed duplicates & standardised data types

Feature engineering:

age_group buckets

purchase_frequency_days

Loaded cleaned data into SQL database

3. Exploratory Data Analysis (EDA)

Gender distribution, subscription behaviour, category trends

Revenue contribution by age group

Correlation analysis of numerical features

Frequency and distribution plots

4. SQL Analysis

Executed business-focused SQL queries, such as:

Revenue by gender, category, and age group

Top-rated and most frequently purchased products

Subscriber vs non-subscriber spending behaviour

Discount impact on purchasing patterns

Repeat buyers and loyalty segment analysis

5. Power BI Dashboard

An interactive dashboard was created featuring:

KPIs (Customer count, Avg Purchase, Avg Ratings)

Category-wise sales & revenue

Age group revenue contributions

Subscription distribution

Shipping preference analysis

6. Final Report

A structured PDF report summarising:

Insights

Visualizations

Business recommendations

7. Gamma Presentation

A concise PPT created automatically using Gamma, summarising:

Objectives

Key findings

Dashboard walkthrough

Recommendations

📊 Key Insights & Results

Clothing contributes the highest revenue across categories

Subscribers spend more on average than non-subscribers

Young adults and middle-aged groups form the biggest revenue segments

Discounts significantly influence product sales, especially in specific categories

Shipping type impacts purchase behaviour (Express users spend more)

🚀 How to Run the Project

✅ 1. Clone the Repository
git clone: https://github.com/tirth1266/Customer-Behavior-Analysis-End-to-End-Data-Analytics-Project
   customer-behavior-analysis

✅ 2. Install Python Packages
pip install -r requirements.txt

✅ 3. Run the Python Notebook

Open Jupyter Notebook:

jupyter notebook


Run EDA_and_Cleaning.ipynb to:

Explore the dataset

Clean data

Export cleaned CSV

✅ 4. Load Data into SQL

Use the SQL scripts provided:

Customer_SQL.sql


Execute in:

PostgreSQL

MySQL

SQL Server

✅ 5. Open the Power BI Dashboard

Open:

Customer_Behavior_Dashboard.pbix

✅ 6. View the Report & Presentation

Customer_Behaviour_Report.pdf

Presentation_Gamma.pptx (Generated using Gamma)

📁 Project Structure
├── data/
│   └── customer_behavior.csv
├── notebooks/
│   └── EDA_and_Cleaning.ipynb
├── sql/
│   └── Customer_SQL.sql
├── dashboard/
│   └── Customer_Behavior_Dashboard.pbix
├── reports/
│   ├── Customer_Behaviour Report.pdf
│   └── Presentation_Gamma.pptx
└── README.md

✅ Final Note

This project demonstrates end-to-end analytics skills:
✅ Python
✅ SQL
✅ Power BI
✅ Reporting
✅ Presentation structuring

Perfect for showcasing data analyst, business analyst, or BI analyst capabilities.
