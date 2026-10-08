# USA Regional Sales Analysis

## Project Overview

This project presents an end-to-end analysis of regional sales data, starting from data ingestion and profiling to data cleaning, feature engineering, exploratory data analysis, business insights, and interactive Power BI reporting.

The objective is to analyse sales performance across products, channels, customers, states, and regions, identify important trends and patterns, and transform the analysis into an interactive business dashboard.

---

## Project Objective

The main objective of this project is to understand historical sales performance and identify patterns related to:

* Sales trends and seasonality
* Product performance
* Channel performance
* Regional and state-level performance
* Customer revenue and profitability
* Order value distribution
* Relationships between financial variables

The analysis is designed to move from raw data to actionable business insights through Python-based analysis and Power BI visualization.

---

## Project Workflow

```text
Data Ingestion
      ↓
Data Profiling
      ↓
Data Cleaning & Wrangling
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis
      ↓
Business Insights
      ↓
Power BI Dashboard
```

---

## Data Analysis

The project follows a structured data analytics workflow.

### 1. Data Ingestion

The sales data was loaded from multiple related tables containing information about:

* Sales Orders
* Customers
* Products
* Regions
* State-Region mapping
* Budgets

### 2. Data Profiling

Initial profiling was performed to understand:

* Dataset dimensions
* Column structure
* Data types
* Available variables
* Data quality
* Relationships between different tables

### 3. Data Cleaning & Wrangling

The data preparation process included:

* Setting appropriate headers
* Merging related tables
* Removing redundant columns
* Standardizing column names
* Selecting relevant analytical fields
* Renaming columns for clarity
* Preparing the dataset for analysis

### 4. Feature Engineering

Additional analytical features were created, including:

* Profit
* Profit Margin %
* Month-related fields
* Geographic attributes
* Other analysis-ready variables

### 5. Exploratory Data Analysis

The EDA focused on understanding:

* Monthly sales trends
* Seasonality
* Product revenue
* Product profitability
* Sales by channel
* State and regional performance
* Customer performance
* Average Order Value distribution
* Revenue and profit relationships
* Outliers and important patterns

---

## Key Insights

The analysis identified several important patterns.

### Sales Trends

Sales showed recurring seasonal patterns, with stronger performance during parts of the year and lower performance during certain months.

### Product Performance

A small group of products contributes a significant share of overall revenue, while lower-performing products form a separate group requiring further evaluation.

### Channel Performance

Wholesale represents the largest share of sales, followed by Distributor and Export channels.

### Geographic Performance

Sales performance varies considerably across U.S. states and regions, with some states contributing substantially more revenue than others.

### Customer Performance

Revenue is concentrated among a group of high-value customers, while the bottom customer segment contributes considerably less revenue.

### Financial Relationships

The analysis also examined relationships between quantity, unit price, revenue, cost, and profit using correlation analysis.

---

## Power BI Dashboard

The Python analysis was transformed into an interactive Power BI sales report containing three dashboard pages.

### 1. Executive Overview & Trends

This dashboard provides an overall view of sales performance through:

* Revenue
* Profit
* Profit Margin
* Orders
* Revenue per Order
* Monthly Revenue Trends
* Monthly Profit Trends
* Unit Price vs Profit Margin
* Order Value Distribution

### 2. Product & Channel Performance

This dashboard focuses on:

* Product Revenue
* Product Profitability
* Product Profit Margin
* Revenue by Channel
* Profit by Channel
* Channel Profit Margin

### 3. Geographic & Customer Insights

This dashboard focuses on:

* Top States by Revenue
* Top Customers
* Revenue by Region
* Profit Margin by Region
* Bottom Customers
* Bottom States
* Geographic Profit Analysis

Interactive filters are provided for dimensions such as channel, region, month, and year.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Power BI

---

## Repository Structure

```text
USA_REGIONAL_ANALYSIS/
│
├── README.md
├── requirements.txt
│
├── EDA_Regional_Sales_Analysis.ipynb
├── USA_Regional_Sales_Report.pbix
└── Sales_data_EDA_Exported.csv
```

---

## Files Description

### `EDA_Regional_Sales_Analysis.ipynb`

Complete Python-based analysis containing data ingestion, profiling, cleaning and wrangling, feature engineering, exploratory data analysis, visualizations, insights, and recommendations.

### `Sales_data_EDA_Exported.csv`

Processed dataset generated during the analysis and used as an analysis-ready data file.

### `USA_Regional_Sales_Report.pbix`

Interactive Power BI report containing three dashboard pages for executive, product/channel, geographic, and customer-level analysis.

### `requirements.txt`

Contains the Python libraries required for the analysis.

---

## Project Outcome

The project demonstrates an end-to-end data analytics workflow:

**Raw Data → Data Preparation → Exploratory Analysis → Business Insights → Interactive Power BI Dashboard**

The final outcome combines Python-based data analysis with Power BI reporting to transform sales data into an interactive business intelligence solution.
