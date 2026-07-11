# Flipkart-Sales-Performance-Analysis-and-Business-Insights
End-to-end data analytics project analyzing Flipkart sales performance, customer behavior, and business insights using Python, SQL, and Power BI.

📖 Project Overview

This project presents an end-to-end Business Analytics solution built on a Flipkart e-commerce dataset. The objective is to transform raw transactional data into meaningful business insights by combining Python, SQL Server, and Power BI.

The project follows a real-world analytics workflow beginning with data understanding and cleaning, followed by exploratory data analysis, feature engineering, SQL-based business analysis, customer segmentation using RFM analysis, and finally interactive dashboard development in Power BI.

The analysis focuses on answering practical business questions related to sales performance, customer purchasing behavior, product performance, seller performance, logistics, customer reviews, and revenue growth.

## 📌 Business Problem

E-commerce companies generate massive volumes of transactional data every day. However, without proper analysis, it becomes difficult to answer critical business questions such as:

- Which products generate the highest revenue?
- Who are the most valuable customers?
- Which categories contribute the most sales?
- How are customer purchasing patterns changing over time?
- Which sellers consistently perform the best?
- How efficient is the delivery process?
- What factors influence customer satisfaction?
- Which customers are likely to become inactive?

This project addresses these business challenges by applying modern data analytics techniques using Python, SQL Server, and Power BI.

## 🎯 Project Objectives

The primary objectives of this project are:

- Clean and preprocess raw Flipkart transactional data.
- Perform exploratory data analysis to uncover business trends.
- Engineer meaningful features for customer and sales analytics.
- Build a relational SQL Server database for efficient querying.
- Solve real-world business problems using SQL.
- Segment customers using the RFM framework.
- Generate actionable business insights for decision-making.
- Develop an interactive Power BI dashboard *(In Progress)*.
- Build a Sales Forecasting model *(Planned)*.

## 🛠 Tech Stack

| Category | Technologies |
|-----------|--------------|
| Programming Language | Python |
| Database | Microsoft SQL Server |
| Data Manipulation | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Business Intelligence | Power BI *(In Progress)* |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |

## 🎯Skills Demonstrated

### Programming
- Python
- SQL (T-SQL)

### Data Analysis
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Customer Segmentation (RFM)

### Visualization
- Matplotlib
- Seaborn
- Power BI

### Database
- SQL Server
- Joins
- CTEs
- Window Functions
- Views

### Business Analytics
- Customer Behavior Analysis
- Sales Analysis
- Product Performance Analysis
- Business Insights

## 📂 Dataset Information

This project uses a relational Flipkart e-commerce dataset consisting of multiple interconnected tables. The dataset captures customer information, orders, products, sellers, payments, logistics, customer reviews, returns, and engineered features for advanced analytics.

| Dataset | Rows | Columns |
|---------|-----:|--------:|
| Customers | 25,000 | 10 |
| Orders | 120,000 | 10 |
| OrderItems | 350,000 | 9 |
| Products | 8,000 | 13 |
| Categories | 40 | 3 |
| Sellers | 500 | 6 |
| Payments | 120,000 | 7 |
| Shipments | 60,067 | 10 |
| Returns | 18,000 | 6 |
| Reviews | 75,000 | 8 |


## 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Understanding
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Export Clean Data to SQL Server
      │
      ▼
SQL Business Analysis
      │
      ▼
Customer Segmentation (RFM)
      │
      ▼
Power BI Dashboard (In Progress)
      │
      ▼
Sales Forecasting (Planned)
      │
      ▼
Business Recommendations
```

## Repository Structure

# 📁 Repository Structure

```text
Flipkart-Business-Analytics/
│
├── 📂 datasets/
│   ├── Customers.csv
│   ├── Orders.csv
│   ├── OrderItems.csv
│   ├── Products.csv
│   ├── Categories.csv
│   ├── Sellers.csv
│   ├── Payments.csv
│   ├── Shipments.csv
│   ├── Returns.csv
│   ├── Reviews.csv
│
├── 📂 notebooks/
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_Exploratory_Data_Analysis.ipynb
│   ├── 03_Feature_Engineering.ipynb
│   ├── 04_SQL_Data_Export.ipynb
│   ├── 05_RFM_Segmentation.ipynb
│   └── 06_Sales_Forecasting.ipynb (Planned)
│
├── 📂 sql/
│   └── SQL_Questions.sql
│
├── 📂 powerbi/
│   └── Flipkart_Dashboard.pbix (In progress*)
│
├── 📂 images/
│   ├── workflow.png
│   ├── dashboard.png
│   └── eda/
│
├── README.md
├── requirements.txt
└── LICENSE
```



## Business Questions

## 📊 Exploratory Data Analysis

The exploratory data analysis focuses on answering key business questions across different business domains.

### Revenue Analysis

- What is the total revenue generated?
- How does monthly revenue change over time?
- Which states contribute the highest sales?
- Which product categories generate the most revenue?
- Which products contribute the highest revenue?

### Customer Analysis

- Who are the highest-value customers?
- What is the average customer spending?
- Which customer age groups contribute the most revenue?
- Which cities have the highest number of customers?
- How many customers are repeat buyers?

### Product & Category Analysis

- Which products are best-selling?
- Which categories dominate total sales?
- Which products receive the highest customer ratings?
- Which products experience the highest return rates?

### Logistics & Delivery Analysis

- What is the average delivery time?
- Which shipping methods are used most frequently?
- How do delivery delays impact customer ratings?

### Payment Analysis

- Which payment methods are most popular?
- What is the average transaction value by payment type?

### Customer Segmentation

- Who are the Champions?
- Which customers are At Risk?
- Which customers are Lost?
- Which customer segments generate the highest revenue?

## 📌 Key Findings

- A small group of customers contributes a significant portion of overall revenue.
- Product category performance varies considerably across different regions.
- Repeat customers generate higher average order values than first-time buyers.
- Delivery delays have a noticeable impact on customer ratings and satisfaction.
- RFM segmentation successfully identifies high-value, loyal, and at-risk customers.
- Revenue and order volume show clear seasonal and monthly purchasing trends.

## 🚀 Project Highlights

- Cleaned and transformed a multi-table Flipkart e-commerce dataset using Python.
- Performed comprehensive exploratory data analysis (EDA) to uncover sales and customer trends.
- Engineered business-focused features for customer and order analytics.
- Built a relational SQL Server database for efficient querying and analysis.
- Solved 40+ real-world business questions using SQL joins, CTEs, window functions, and aggregations.
- Performed RFM analysis to segment customers based on purchasing behavior.
- Generated actionable business insights to support data-driven decision making.

## 📈 Project Status

| Module | Status |
|---------|:------:|
| Data Understanding | ✅ Completed |
| Data Cleaning & Preprocessing | ✅ Completed |
| Exploratory Data Analysis (EDA) | ✅ Completed |
| Feature Engineering | ✅ Completed |
| SQL Database Creation | ✅ Completed |
| SQL Business Analysis | ✅ Completed |
| Customer Segmentation (RFM) | ✅ Completed |
| Business Insights | ✅ Completed |
| Power BI Dashboard | 🚧 In Progress |
| Sales Forecasting | ⏳ Planned |

## 👨‍💻 Author

**Prateek Khicher**

🎓 B.Tech, Mechanical Engineering  
📊 Aspiring Data Analyst | Business Analyst  
🐍 Python • SQL Server • Power BI • Data Visualization  
📍 India

If you found this project useful, feel free to ⭐ the repository.

  
  
