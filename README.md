<img width="2911" height="1468" alt="image" src="https://github.com/user-attachments/assets/e71eb2e5-7707-4bb3-b4d2-9b8d5bbcdc7a" /> Olist Store Analysis – E-commerce Data Analytics

Excel | MySQL | SQL | Power BI | Tableau

📌 Project Overview

This project focuses on end-to-end e-commerce data analysis using the Olist Brazilian E-commerce dataset. It explores sales performance, customer behavior, product categories, payment methods, and delivery operations.

The project uses Excel, MySQL, SQL, Power BI, and Tableau to transform raw data into meaningful business insights and interactive dashboards.

The analysis covers approximately 99K+ orders and evaluates key business performance indicators to support data-driven decision-making.

🎯 Project Objectives

Analyze overall sales and revenue performance.

Understand customer purchasing behavior and geographical distribution.

Identify top-performing and low-performing product categories.

Analyze payment methods and customer reviews.

Evaluate delivery performance and logistics efficiency.

Build interactive dashboards to monitor important business KPIs.

Generate actionable business recommendations.

🛠️ Tools & Technologies

Tool

Purpose

Microsoft Excel

Data cleaning, preparation and dashboard creation

MySQL

Database management and data storage

SQL

Data extraction, querying and business analysis

Power BI

Interactive dashboard and data visualization

Tableau

Business intelligence and visual analytics

📊 Key Performance Indicators (KPIs)

The following KPIs are based on the current project dashboard:

KPI

Value

Total Orders

89.24K

Total Revenue

14M

Total Customers

86K

Average Order Value

155.11

On-Time Delivery Rate

78.98%

Average Delivery Time

11.69 Days

Note: Revenue and order metrics should be interpreted using the currency, date filters, and calculation definitions applied in the dashboard. The original Olist dataset uses Brazilian Real (BRL), not USD.

📁 Dataset Overview

The project uses the Olist Brazilian E-commerce public dataset, which contains information about orders, customers, products, sellers, payments, reviews, and geographical locations.

Core Tables

Dataset

Description

olist_orders_dataset

Order status, purchase date, approval date and delivery dates

olist_customers_dataset

Customer IDs, city, state and geographical information

olist_order_items_dataset

Order items, product IDs, seller IDs, prices and freight

olist_products_dataset

Product categories and product attributes

olist_sellers_dataset

Seller IDs and seller locations

Supporting Tables

Dataset

Description

olist_order_payments_dataset

Payment types, installments and payment values

olist_order_reviews_dataset

Customer review scores and comments

olist_geolocation_dataset

Zip codes, cities, states and geographical coordinates

product_category_name_translation

Portuguese-to-English product category translations

🔗 Data Relationships

The project uses a relational data model:

Orders connect customers, order items, payments and reviews.

Order items connect products and sellers.

Products connect with product category information.

Geolocation data supports geographical analysis.

Category translation data provides readable English category names.

🔍 Analysis Performed

1. Sales and Revenue Analysis

Total revenue and total orders.

Monthly and yearly sales trends.

Average order value.

Weekday versus weekend sales.

Revenue by product category.

2. Customer Analysis

Total unique customers.

Customer geographical distribution.

Repeat customer analysis.

Customer purchasing patterns.

State-wise customer performance.

3. Product Analysis

Top-performing product categories.

Revenue by product category.

Product sales distribution.

Product performance comparison.

4. Payment Analysis

Payment method distribution.

Revenue by payment type.

Installment analysis.

Average payment value.

5. Delivery Analysis

Average delivery time.

On-time delivery rate.

Estimated versus actual delivery dates.

Delivery performance by geographical region.

6. Customer Review Analysis

Average review score.

Review score distribution.

Delivery time versus review score.

Customer satisfaction trends.

💡 Key Business Insights

Weekday sales contribute more revenue than weekend sales.

Beleza Saúde is among the leading product categories by revenue in the current analysis.

São Paulo (SP) contributes the highest sales among Brazilian states.

Average delivery time is approximately 12 days.

Faster deliveries generally show a positive relationship with customer review scores.

📈 Business Recommendations

Improve delivery speed and logistics efficiency to enhance customer satisfaction.

Focus on high-performing product categories to identify revenue growth opportunities.

Develop weekend marketing campaigns to improve weekend sales.

Optimize logistics operations in regions with weaker delivery performance.

Use historical sales data to support demand forecasting and inventory planning.

📸 Dashboard Previews

Power BI Dashboard

Excel Dashboard

Tableau Dashboard

📂 Repository Structure

Olist-Store-Analysis-E-commerce/
│
├── README.md
│
├── data/
│   ├── olist_orders_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_customers_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   └── product_category_name_translation.csv
│
├── SQL/
│   ├── 01_data_exploration.sql
│   ├── 02_data_cleaning.sql
│   ├── 03_sales_analysis.sql
│   ├── 04_customer_analysis.sql
│   ├── 05_product_analysis.sql
│   └── 06_delivery_analysis.sql
│
├── Excel/
│   ├── Olist_Excel_Analysis.xlsx
│   └── Excel_Dashboard.png
│
├── PowerBI/
│   ├── Olist_PowerBI_Dashboard.pbix
│   └── PowerBI_Dashboard.png
│
└── Tableau/
    ├── Olist_Tableau_Dashboard.twbx
    └── Tableau_Dashboard.png

🚀 How to Use This Project

Clone or download this GitHub repository.

Download or access the datasets from the data/ folder.

Import the datasets into MySQL.

Execute the SQL scripts available in the SQL/ folder.

Open the Excel workbook to explore data analysis and dashboards.

Open the Power BI .pbix file to explore interactive reports.

Open the Tableau workbook to explore visualizations.

🧠 Skills Demonstrated

Data Cleaning and Data Preparation

Exploratory Data Analysis (EDA)

SQL Queries and Database Management

MySQL Data Analysis

Excel Data Analysis and Dashboards

Power BI Dashboard Development

Tableau Data Visualization

Business Intelligence

KPI Development

Business Insights and Recommendations

🏁 Conclusion

The Olist E-commerce Data Analysis project demonstrates how multiple data analytics tools can be used to solve real-world business problems.

By analyzing sales, customers, products, payments, reviews, and logistics, this project provides insights into business performance and operational efficiency.

The combination of Excel, SQL, MySQL, Power BI, and Tableau showcases an end-to-end Data Analyst workflow, from raw data preparation to interactive dashboards and actionable business recommendations.

Project Domain: E-commerce Analytics
Project Type: End-to-End Data Analytics
Tools: Excel, SQL, MySQL, Power BI and Tableau
