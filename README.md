📊 Online Retail Sales – Data Analysis Project
This project performs an end-to-end data analysis on an Online Retail Sales dataset.
It includes data cleaning, feature engineering, exploratory analysis, and customer analytics such as RFM and Churn analysis.

🚀 Project Workflow
1. Data Loading

Import raw dataset into a pandas DataFrame.

Handle file formats (CSV/Excel).

2. Data Cleaning

Remove missing or invalid values

Fix data types (InvoiceDate → datetime, Quantity → int, etc.)

Remove negative/duplicate records

Filter out cancellations

3. Feature Engineering

Create new features such as:

Total_Sales = Quantity × UnitPrice

Extract date parts (Year, Month, Day)

Calculate customer-level metrics

📈 4. Visualization & EDA
📌 Monthly Sales Trend

Line plot showing how sales change month-by-month.

📌 Top 5 Countries by Sales

Bar chart showing highest revenue-generating countries (excluding UK if needed).

📌 Percentage Contribution (Country-wise)

Bar plot visualizing contribution of each country to total revenue.

📌 Percentage Contribution (Product-wise)

Bar plot showing top products and their revenue contribution.

🧮 5. RFM Analysis

RFM = Recency, Frequency, Monetary

Recency: Days since last purchase

Frequency: Number of orders

Monetary: Total spending

Steps:

Group data by CustomerID

Calculate RFM metrics

Apply qcut() to assign R/F/M scores

Create overall RFM segment

Purpose:
✔ Identify loyal customers
✔ Detect dormant customers
✔ Target marketing campaigns

🔍 6. Churn Analysis

Churn analysis identifies customers who may have stopped buying.

Steps:

Calculate recency for all customers

Define churn_threshold (e.g., 90 days)

Analyze churn patterns & customer behavior

📊 7. Churned Customer Distribution Visualization

Plot histogram of customer recency

Mark churn threshold using axvline

Visualize the distribution of churned vs active customers

Purpose:
✔ Identify at-risk customers
✔ Understand retention patterns

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

📌 Conclusion

This project provides a complete pipeline of analyzing online retail data — from cleaning to advanced customer analytics such as RFM and Churn.
The insights help businesses understand:

Who are the top customers?

Which products and countries contribute the most?

How customer behavior shifts over time?

Which customers are likely to churn?
