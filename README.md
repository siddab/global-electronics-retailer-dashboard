Global Electronics Retailer — Interactive Revenue Dashboard (Excel BI Project)
Project Overview

This project analyzes transactional data from a global electronics retailer to uncover insights about sales performance, customer demographics, product trends, and delivery efficiency.
Built entirely in Microsoft Excel, the project demonstrates skills in data modeling, data transformation, calculated measures, and interactive dashboard design.

The final deliverable is an interactive revenue report that enables business leaders to explore key metrics such as total orders, revenue, average order value (AOV), and delivery performance across multiple dimensions including time, product category, and store location.

Objectives
1. Data Profiling and Preparation

Connected and profiled multiple CSV datasets: Sales, Products, Stores, Customers, and Exchange_Rates.

Added a unique TransactionKey to identify each record.

Cleaned and transformed data by:

Standardizing city names.

Removing unnecessary fields (e.g., Zip Code).

Calculating Customer Age and categorizing into Age Ranges:

Young Adult (18–30)

Adult (31–60)

Senior (60+)

Built a Calendar Table containing contiguous dates and time intelligence columns (Day, Month, Quarter, Year).

2. Relational Data Model

Established 1-to-many relationships between:

Sales ↔ Customers

Sales ↔ Products

Sales ↔ Stores

Sales ↔ Calendar

Created a new ExchangeKey field to connect Sales with Exchange Rates.

Implemented a star schema design and hid redundant foreign key fields.

(Bonus) Normalized the Products table into separate Category and Subcategory dimension tables.

3. Data Enrichment and Measures

Added a dedicated Measures Table and created key calculated metrics:

Total Orders = Count of unique Order Numbers

Total Revenue (USD) = Sum of (Quantity × Unit Price)

Average Order Value (AOV) = Total Revenue ÷ Total Orders

Average Delivery Time (Days) = Date difference between Order Date and Delivery Date

Insights:

Revenue trends showed seasonal fluctuations across quarters.

Certain product categories had significantly higher AOV.

Delivery times improved over time, indicating operational efficiency.

Store performance varied by region and customer demographics.

4. Interactive Dashboard Design

Developed an interactive Excel dashboard featuring:

KPI cards for Orders, Revenue, AOV, and Delivery Time.

Line chart showing monthly revenue trends.

Bar chart displaying revenue by product category.

Slicers for Store and Year to filter all visuals.

Consistent color palette, clear formatting, and readable number formats.

Key Insights

Adults aged 30–60 represented the highest-value customer segment.

Home Appliances and Computers generated the most consistent revenue.

Delivery times improved by approximately 15% year over year.

Some stores showed lower AOV despite high order volumes, indicating opportunities for upselling.
