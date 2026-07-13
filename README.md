# online-retail-sales-analysis
End-to-end retail sales analytics project using Python, Pandas, Power BI, and GitHub.
# 🛍️ Online Retail Sales Analysis

End-to-End Data Cleaning, Exploratory Data Analysis (EDA), and Interactive Power BI Dashboard using Python and Power BI.

---




## 📌 Project Overview

This project analyzes over **1 million retail transactions** from a UK-based online retailer between **December 2009 and December 2011**.

The objective was to transform raw transactional data into meaningful business insights through:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Interactive Power BI Dashboard Development

The project demonstrates an end-to-end data analytics workflow commonly used by Data Analysts and Business Intelligence professionals.

## 🎯 Business Problem

Retail businesses generate massive amounts of transactional data every day.

However, raw sales data often contains:

- Duplicate records
- Cancelled transactions
- Missing customer information
- Invalid prices
- Inconsistent data

Without proper cleaning, business reports and dashboards can produce misleading insights.

This project focuses on preparing reliable retail data for analysis and developing an interactive dashboard to support business decision-making.

## 📂 Dataset Information

**Dataset:** Online Retail II

**Source:** UCI Machine Learning Repository

**Time Period:**
- December 2009 – December 2011

**Rows:**
- 1,067,371 (Raw)

**Rows after Cleaning:**
- ~1,007,913

**Features Include:**

- Invoice
- StockCode
- Description
- Quantity
- Price
- Customer ID
- Country
- InvoiceDate

## 🔄 Project Workflow

Raw Dataset

↓

Data Cleaning (Pandas)

↓

Feature Engineering

↓

Exploratory Data Analysis

↓

Business Insights

↓

Power BI Dashboard

↓

Business Decision Support

## 🛠️ Technologies Used

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib

### Business Intelligence

- Power BI Desktop

### Development Tools

- Jupyter Notebook
- VS Code
- Git
- GitHub

## 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Removed cancelled invoices
- Removed invalid prices
- Removed negative quantities
- Removed accounting adjustment records
- Handled missing values
- Verified final dataset quality

## ⚙️ Feature Engineering

New columns were created to simplify analysis:

- Revenue
- Year
- Month
- Month Name
- Weekday
- Hour
- Weekend

## 📊 Exploratory Data Analysis

Key analyses performed include:

- Monthly Revenue Trend
- Top 10 Products
- Top 10 Customers
- Revenue by Country
- Revenue by Hour
- Revenue by Weekday
- Average Order Value

## 📈 Power BI Dashboard

The interactive dashboard consists of three report pages:

### Executive Dashboard

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Monthly Revenue Trend
- Top Countries by Revenue

### Sales Performance

- Top Products
- Revenue by Weekday
- Revenue by Hour

### Customer Insights

- Top Customers
- Customer Order Analysis
- Revenue Distribution

## 💡 Key Business Insights

- The United Kingdom contributes the majority of total revenue.
- Revenue peaks during the holiday shopping season.
- A small number of products account for a significant portion of total sales.
- Sales activity is highest during midday business hours.
- Weekday sales consistently outperform weekend sales.

## 📁 Repository Structure

online-retail-sales-analysis/

├── dashboard/

├── data/

│ ├── raw/

│ └── cleaned/

├── notebooks/

├── outputs/

├── screenshots/

├── README.md

├── requirements.txt

└── LICENSE

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Aqdas999/online-retail-sales-analysis.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```
## 🔮 Future Improvements

- Customer Segmentation (RFM Analysis)
- Sales Forecasting
- Profitability Analysis
- Customer Lifetime Value (CLV)
- Interactive Power BI Service Deployment
