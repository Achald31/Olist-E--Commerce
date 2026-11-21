# 🛒 Olist Store Analysis – E-commerce

**Power BI | Tableau | SQL | MySQL | Excel**

## 📌 Project Overview
An end-to-end E-commerce Data Analysis project using Excel, MySQL, SQL, Power BI, and Tableau. This project analyzes 99K+ orders to identify sales trends, customer behavior, product performance, and delivery efficiency through interactive dashboards.

## 🎯 Objectives
- Analyze sales and revenue trends.
- Understand customer behavior and distribution.
- Evaluate product category performance.
- Monitor delivery performance.
- Track key business KPIs.

## 🛠️ Tools & Technologies
- **Excel:** Data cleaning and preparation.
- **MySQL:** Database management.
- **SQL:** Data querying and analysis.
- **Power BI:** Interactive dashboards.
- **Tableau:** Data visualization.

## 📊 Key KPIs

| KPI | Value |
|---|---:|
| Total Orders | 89.24K |
| Total Revenue | 14M |
| Total Customers | 86K |
| Average Order Value | 155.11 |
| On-Time Delivery Rate | 78.98% |
| Average Delivery Time | 11.69 Days |

*Note: Revenue currency and KPI calculations should be verified against the dashboard. Original Olist data uses Brazilian Real (BRL).*

## 📁 Dataset Overview

The project uses the Olist Brazilian E-commerce dataset, containing information about orders, customers, products, sellers, payments, reviews, and logistics.

### Core Tables
- **olist_orders_dataset:** Order details, status and timestamps.
- **olist_customers_dataset:** Customer IDs and locations.
- **olist_order_items_dataset:** Products, sellers, prices and freight.
- **olist_products_dataset:** Product details and categories.
- **olist_sellers_dataset:** Seller information and locations.

### Supporting Tables
- **olist_order_payments_dataset:** Payment types and values.
- **olist_order_reviews_dataset:** Customer ratings and feedback.
- **olist_geolocation_dataset:** Geographical information.
- **product_category_name_translation:** Category name translations.

## 🔗 Data Relationships
- Orders connect customers, payments, reviews and order items.
- Order items connect products and sellers.
- Geolocation supports regional analysis.
- Category translations provide English product names.

## 💡 Key Insights
- Weekday sales are higher than weekend sales.
- Beleza Saúde is a leading revenue-generating category.
- São Paulo contributes the highest sales.
- Average delivery time is approximately 12 days.
- Faster deliveries generally correlate with higher review scores.

## 📈 Business Recommendations
- Improve delivery speed and logistics efficiency.
- Focus on high-performing product categories.
- Introduce weekend marketing campaigns.
- Optimize logistics in low-performing regions.
- Implement demand forecasting for inventory planning.

## 📊 Business Impact
- Improved sales and customer performance visibility.
- Identified revenue growth opportunities.
- Highlighted operational improvement areas.
- Supported data-driven business decisions.

## 🧠 Skills Demonstrated
- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- SQL & MySQL
- Excel Data Analysis
- Power BI Dashboard Development
- Tableau Visualization
- KPI Analysis
- Business Intelligence

## 📸 Dashboard Previews

### Power BI Dashboard


### Excel Dashboard


### Tableau Dashboard

## 🚀 How to Use
1. Clone or download this repository.
2. Access datasets from the `data/` folder.
3. Import datasets into MySQL.
4. Execute SQL queries.
5. Open the Excel workbook.
6. Open Power BI and Tableau dashboards.
7. Explore insights using interactive filters.

## 🏁 Conclusion
This project demonstrates an end-to-end data analytics workflow using Excel, SQL, MySQL, Power BI, and Tableau. It transforms raw e-commerce data into meaningful business insights, helping identify sales opportunities, understand customer behavior, and improve delivery performance.

**Project Domain:** E-commerce Analytics  
**Project Type:** End-to-End Data Analytics  
**Tools:** Excel, SQL, MySQL, Power BI & Tableau
