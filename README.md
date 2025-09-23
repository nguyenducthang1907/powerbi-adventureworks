**🌟 Project Highlights**
🔹 Built an interactive Power BI dashboard using the Adventure Works dataset from Kaggle.
🔹 Applied Power Query, DAX, and data modeling to transform raw data into actionable insights.
🔹 Delivered executive-level reports on sales, customer behavior, and inventory management.
🔹 Showcased business intelligence and data visualization skills for portfolio and career growth.

**Adventure Works Sales & Operations Dashboard (Power BI Project)**
📌 Project Overview
This project analyzes the Adventure Works dataset (from Kaggle) using Power BI.
The dashboard provides insights into sales performance, customer behavior, revenue trends, and inventory management, demonstrating skills in data cleaning, modeling, and visualization.

🛠 Tools & Technologies

Power BI (Dashboard & Data Modeling)
Power Query (ETL: extract, transform, load)
DAX (Data Analysis Expressions)
Dataset: Adventure Works on Kaggle

📊 Dashboard Features

Executive Summary
Total Sales, Profit, Orders, Customers
YoY Growth trends
Sales Analysis
Sales by Region, Product Category, and Subcategory

Top-performing products

Customer Insights

Top Customers by revenue
New vs. Returning Customers
Inventory & Operations
Stock levels vs. Reorder levels
Forecasted demand

⚙️ Data Model

Fact Tables: Sales, Orders, Inventory
Dimension Tables: Customers, Products, Employees, Date
Relationships established to support star schema modeling.

📈 DAX Measures (Examples)
Total Sales = SUMX(Sales, Sales[Quantity] * Sales[UnitPrice] * (1 - Sales[Discount]))

Total Orders = COUNTROWS(Sales)
Avg Order Value = [Total Sales] / [Total Orders]

🚀 How to Use

Open the .pbix file in Power BI Desktop.

Interact with dashboards using filters and slicers.

🔍 Insights Gained

Identified top revenue-generating products and regions with highest sales.

Found customer segments contributing to recurring revenue.

Monitored inventory risks (low stock vs. reorder level).

📂 Project Structure
📁 powerbi-adventureworks
 ┣ 📄 AdventureWorks.pbix
 ┣ 📄 README.md
 ┗ 📁 data (raw dataset from Kaggle)
