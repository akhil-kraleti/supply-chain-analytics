# Supply Chain Analytics Dashboard

## Project Overview

This project is an end-to-end Supply Chain Analytics solution built using **Python, MySQL, and Power BI**. The objective was to transform raw supply chain transaction data into a structured data warehouse and develop interactive dashboards that provide actionable business insights.

The project covers the complete analytics workflow, including:

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Data Warehouse Design
- ETL Process
- SQL Data Loading
- Power BI Dashboard Development
- Business Performance Analysis

---

## Objectives

The project aims to answer key business questions such as:

- How is revenue performing over time?
- Which product categories generate the highest revenue and profit?
- Who are the most valuable customers?
- Which customer segments contribute the most sales?
- How effective are shipping and delivery operations?
- What factors impact overall profitability?

---

## Technology Stack

| Tool | Purpose |
|--------|---------|
| Python | Data Cleaning & Feature Engineering |
| Pandas | Data Manipulation |
| MySQL | Data Warehouse |
| SQL | Data Modeling & Data Loading |
| Power BI | Dashboard Development |
| DAX | Business Calculations & KPIs |

---

## Dataset

**Dataset:** DataCo Supply Chain Dataset

The dataset contains information related to:

- Orders
- Customers
- Products
- Categories
- Departments
- Shipping Information
- Sales Transactions

---

## Project Architecture

```text
Raw Dataset
     │
     ▼
Exploratory Data Analysis
     │
     ▼
Data Cleaning
     │
     ▼
Feature Engineering
     │
     ▼
MySQL Data Warehouse
     │
     ▼
Power BI Dashboard
```

---

## Data Warehouse Design

The project uses a dimensional data model with:

### Fact Table

**FactOrders**

Contains:

- Revenue
- Profit
- Quantity
- Order Information
- Foreign Keys

### Dimension Tables

**DimCustomer**

- Customer Name
- Customer Segment
- City
- State
- Country

**DimProduct**

- Product Name
- Department
- Category

**DimCategory**

- Category Details

**DimShipping**

- Shipping Mode
- Delivery Status

**DimDate**

- Date Attributes
- Month
- Quarter
- Year

---

## Data Processing Workflow

### 1. Exploratory Data Analysis

- Dataset Understanding
- Missing Value Analysis
- Duplicate Detection
- Statistical Summary
- Data Distribution Analysis

### 2. Data Cleaning

- Handled Missing Values
- Removed Duplicates
- Standardized Column Names
- Corrected Data Types
- Removed Redundant Fields

### 3. Feature Engineering

Created business metrics such as:

- Net Sales
- Profit
- Shipping Delay
- Profit Margin %
- Discount Amount

### 4. SQL Data Loading

- Created Dimension Tables
- Created Fact Table
- Established Relationships
- Loaded Data into MySQL

---

## Power BI Dashboards

### Executive Dashboard

Provides a high-level overview of business performance.

#### KPIs

- Total Revenue
- Total Profit
- Total Orders
- Total Customers
- Profit Margin %
- Average Order Value

#### Visuals

- Monthly Revenue Trend
- Revenue by Category
- Revenue by Department
- Revenue by Shipping Mode

---

### Product Performance Dashboard

Analyzes product-level performance.

#### Visuals

- Top 10 Products by Revenue
- Profit by Category
- Quantity Sold by Category
- Revenue by Department

---

### Customer Analysis Dashboard

Analyzes customer behavior and segmentation.

#### Visuals

- Top Customers by Revenue
- Revenue by Customer Segment
- Revenue by State
- Customers by City

---

### Supply Chain Analysis Dashboard

Evaluates shipping and delivery performance.

#### KPIs

- Average Shipping Delay
- Late Delivery %
- Total Orders
- Total Revenue

#### Visuals

- Orders by Shipping Mode
- Revenue by Shipping Mode
- Delivery Status Analysis
- Average Delay by Shipping Mode

---

## DAX Measures

Key measures created in Power BI:

```DAX
Total Revenue
Total Profit
Total Orders
Total Customers
Total Quantity
Average Order Value
Profit Margin %
Revenue per Customer
Average Shipping Delay
Late Delivery %
```

---

## Project Structure

```text
SupplyChainAnalytics/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   └── 04_SQL_Data_Load.ipynb
│
├── sql/
│   ├── 01_Create_Database.sql
│   └── 02_Create_Tables.sql
│
├── powerbi/
│   └── SupplyChainAnalytics.pbix
│
├── screenshots/
│
└── requirements.txt
```

---

## Key Business Insights

- Identified the highest revenue-generating product categories.
- Determined top-performing products and departments.
- Analyzed customer segments contributing the highest sales.
- Evaluated shipping performance and delivery delays.
- Measured profitability across products and customer groups.

---

## Skills Demonstrated

### Data Analytics

- Exploratory Data Analysis
- Business Intelligence
- KPI Development
- Data Visualization

### Python

- Pandas
- Data Cleaning
- Feature Engineering

### SQL

- Data Warehouse Design
- Fact & Dimension Modeling
- ETL Processes

### Power BI

- Data Modeling
- DAX Measures
- Interactive Dashboards
- Dashboard Design

---

## Future Enhancements

- Forecasting and Time-Series Analysis
- Advanced DAX Calculations
- Drill-through Reports
- Dynamic KPI Indicators
- Power BI Service Deployment

---

## Author

**Akhil Kraleti**

Aspiring Data Analyst skilled in Python, SQL, Power BI, and Data Analytics.

---
