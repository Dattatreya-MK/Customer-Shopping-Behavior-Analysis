# Customer-Shopping-Behavior-Analysis
Data analysis project exploring customer shopping behavior using Python, PostgreSQL, SQL, and Power BI to identify purchasing patterns, customer segments, revenue trends, and business insights.
# Customer Shopping Behavior Analysis

## 📊 Project Overview

This project analyzes customer shopping behavior to identify purchasing patterns, customer segments, product trends, and revenue insights.

The project uses Python for data cleaning and transformation, PostgreSQL for data storage and SQL analysis, and Power BI for interactive data visualization and dashboard creation.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- PostgreSQL
- pgAdmin
- SQL
- SQLAlchemy
- Power BI

## 📁 Project Files

- `customer_shopping_behavior.csv` – Original customer shopping dataset
- `customer_behavior.ipynb` – Python data cleaning and analysis
- `csv sql.sql` – SQL queries used for analysis
- `csv powerbi.pbix` – Power BI dashboard
- `Business Problem Document.pdf` – Business problem and requirements
- `Customer Shopping Behavior Analysis.pdf` – Project analysis/report
- `Customer-Shopping-Behavior-Analysis.pptx` – Project presentation

## 🔄 Project Workflow

CSV Dataset
      ↓
Python / Pandas
      ↓
Data Cleaning & Transformation
      ↓
PostgreSQL Database
      ↓
SQL Analysis
      ↓
Power BI Dashboard
      ↓
Business Insights

## 🧹 Data Preparation

The dataset was cleaned and transformed using Pandas.

Key transformations include:

- Handling missing values
- Standardizing column names
- Creating `age_group`
- Creating `purchase_frequency_days`
- Removing redundant columns
- Preparing the dataset for PostgreSQL analysis

## 🗄️ PostgreSQL

The cleaned dataset was loaded into a PostgreSQL database named:

`customer_behavior`

The main table is:

`customer`

SQL queries were used to analyze:

- Revenue by gender
- Customer purchasing behavior
- Product/category performance
- Customer segments
- Purchase frequency
- Other business-related metrics

## 📈 Power BI Dashboard

Power BI was used to create an interactive dashboard from the PostgreSQL database.

The dashboard helps analyze:

- Revenue trends
- Customer demographics
- Product performance
- Purchase patterns
- Customer behavior

## 🎯 Business Objective

The objective of this project is to transform raw customer shopping data into meaningful business insights that can support better decisions related to customers, products, sales, and marketing.

## 👨‍💻 Author

Dattatreya
