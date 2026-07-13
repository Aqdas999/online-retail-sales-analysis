# online-retail-sales-analysis
End-to-end retail sales analytics project using Python, Pandas, Power BI, and GitHub.

# 🛍️ Online Retail Sales Analysis

### End-to-End Data Analytics Project using Python, Pandas & Power BI

This project demonstrates a complete **Data Analytics workflow**, transforming over **1 million retail transactions** into meaningful business insights through:

- 🧹 Data Cleaning using Pandas
- 📊 Exploratory Data Analysis (EDA)
- 📈 Interactive Power BI Dashboard
- 📉 Business Insight Generation

The project follows industry-standard analytics practices, from raw data preprocessing to executive-level dashboard reporting.

## 📖 Project Overview

Retail businesses generate millions of transaction records, but raw sales data often contains duplicate records, cancelled orders, missing values, and inconsistent information that can affect business reporting.

In this project, the **Online Retail II** dataset from the **UCI Machine Learning Repository** was cleaned, transformed, and analyzed to uncover meaningful business insights.

The project concludes with a fully interactive **Power BI dashboard** designed for executive reporting and sales analysis.

This project simulates a real-world Data Analyst workflow commonly used in retail and e-commerce organizations.

## 🚀 Project Highlights

✔ Cleaned over **1 million** transaction records

✔ Removed duplicate and invalid transactions

✔ Engineered new analytical features

✔ Performed Exploratory Data Analysis (EDA)

✔ Built a 3-page interactive Power BI Dashboard

✔ Generated actionable business insights

✔ Documented the complete analytics workflow

## 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Cleaning (Pandas)
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights
```

## 📂 Dataset Information

| Attribute | Details |
|-----------|---------|
| **Dataset Name** | Online Retail II |
| **Source** | UCI Machine Learning Repository |
| **Domain** | E-Commerce / Retail |
| **Time Period** | December 2009 – December 2011 |
| **Raw Records** | 1,067,371 Transactions |
| **Features** | 8 Columns |
| **File Format** | Excel (.xlsx) |

### Dataset Features

- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

## 🎯 Business Objective

The objective of this project is to transform raw retail transaction data into meaningful business insights by:

- Cleaning inconsistent and incomplete transactional records
- Identifying sales trends across time
- Understanding customer purchasing behavior
- Evaluating product performance
- Building an interactive dashboard for business stakeholders

The final dashboard enables decision-makers to monitor sales performance and identify opportunities for business growth.

## 🛠️ Tech Stack

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Data Visualization

- Matplotlib

### Business Intelligence

- Microsoft Power BI

### Development Environment

- Jupyter Notebook
- Visual Studio Code

### Version Control

- Git
- GitHub

## 📁 Repository Structure

```
online-retail-sales-analysis/

├── dashboard/
│   └── Online_Retail_Sales_Dashboard.pbix
│
├── data/
│   └── raw/
│       └── online_retail_II.xlsx
│
├── notebooks/
│   └── retail_analysis.ipynb
│
├── outputs/
│   ├── monthly_revenue.csv
│   ├── country_revenue.csv
│   └── visualizations
│
├── screenshots/
│   ├── executive_dashboard.png
│   ├── sales_dashboard.png
│   └── customer_dashboard.png
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

## 🧹 Data Cleaning

Several preprocessing techniques were applied to improve the quality of the dataset before analysis.

### Cleaning Steps

- Removed duplicate transactions
- Removed cancelled invoices
- Removed transactions with negative quantities
- Removed records with zero or negative prices
- Removed accounting adjustment entries
- Investigated missing values
- Validated the cleaned dataset

These steps ensured that only valid customer purchases were included in the analysis.

## ⚙️ Feature Engineering

New analytical features were created to support business analysis.

| Feature | Description |
|----------|-------------|
| Revenue | Quantity × Price |
| Year | Purchase Year |
| Month | Purchase Month |
| Month Name | Month Label |
| Weekday | Day of Week |
| Hour | Purchase Hour |
| Weekend | Weekend / Weekday Indicator |

These engineered features enabled trend analysis and dashboard development.

## 📊 Exploratory Data Analysis (EDA)

After cleaning the dataset, exploratory analysis was performed to identify trends, customer behavior, and product performance.

### Analysis Performed

- 📈 Monthly Revenue Trend
- 🌍 Revenue by Country
- 🛒 Top 10 Products by Revenue
- 👥 Top 10 Customers by Revenue
- 🕒 Revenue by Hour
- 📅 Revenue by Weekday
- 💰 Average Order Value
- 📦 Sales Distribution Analysis

The insights obtained from EDA were later used to design an interactive Power BI dashboard.

# 📸 Dashboard Preview

## Executive Dashboard

![Executive Dashboard](screenshots/executive_dashboard.png)

---

## Sales Performance Dashboard

![Sales Dashboard](screenshots/sales_dashboard.png)

---

## Customer Insights Dashboard

![Customer Dashboard](screenshots/customer_dashboard.png)

# 📸 Dashboard Preview

## Executive Dashboard

![Executive Dashboard](screenshots/executive_dashboard.png)

---

## Sales Performance Dashboard

![Sales Dashboard](screenshots/sales_dashboard.png)

---

## Customer Insights Dashboard

![Customer Dashboard](screenshots/customer_dashboard.png)

# 📌 Project Outcomes

Through this project:

- Processed over **1 million retail transactions**
- Improved data quality through preprocessing
- Generated meaningful business insights
- Built an interactive Power BI dashboard
- Demonstrated an end-to-end Data Analytics workflow

# 🚀 How to Run

### Clone the Repository

```bash
git clone https://github.com/Aqdas999/online-retail-sales-analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebooks/retail_analysis.ipynb
```

to reproduce the analysis.

# 🔮 Future Improvements

- Customer Segmentation (RFM Analysis)
- Sales Forecasting using Machine Learning
- Customer Lifetime Value (CLV) Analysis
- Profitability Analysis
- Inventory Demand Forecasting
- Power BI Service Deployment

