📊 Tableau End-to-End BI Project

Customer and Sales Performance Dashboards (2013)

🧩 Overview

This project demonstrates a complete end-to-end Tableau analytics workflow, designed to analyze sales and customer performance for the year 2013.
The dataset originates from my internal data warehouse, which was cleaned, modeled, and visualized using Tableau Desktop.

The project replicates a real-world BI solution, combining data engineering, visualization design, and business storytelling in a single package.

🎯 Objectives

Connect and prepare data from a data warehouse.

Create interactive dashboards to monitor customer behavior and sales performance.

Compare year-over-year performance (2013 vs 2012).

Identify top customers, profit trends, and product category insights.

Apply design principles that support clarity and decision-making.

🗂️ Project Structure
Component	Description
Dashboard.twbx	Tableau packaged workbook containing both dashboards and data model
Sales Dashboard.png	Snapshot of the Sales Performance Dashboard
Customer Dashboard.png	Snapshot of the Customer Insights Dashboard
Data Source	Extracted from internal data warehouse tables (Sales, Orders, Customers, Products)
⚙️ Process Overview
1. Data Preparation

Data pulled from internal data warehouse (fact and dimension tables).

Joined and cleaned in Tableau’s Data Source tab.

Calculated fields created for:

Profit Margin = SUM([Profit]) / SUM([Sales])

Sales per Customer = SUM([Sales]) / COUNTD([Customer ID])

Year-over-Year Growth = ([Current Year] - [Previous Year]) / [Previous Year]

2. Dashboard Design
a. Sales Dashboard

Focuses on organizational KPIs and high-level trends.
Key Metrics:

Total Sales: $16.3M

Total Quantity: 53K

Total Profit: $6.76M
Key Visuals:

KPI line charts (2013 vs 2012)

Bar chart for Sales & Profit by Subcategory

Dual-line chart for Sales & Profit Trends over Time

Color indicators for Above / Below average performance

b. Customer Dashboard

Designed to track customer-level performance and engagement.
Key Metrics:

Total Customers: 17K

Total Orders: 21K

Sales per Customer: $1K
Key Visuals:

Customer distribution by purchase frequency

Top 10 customers ranked by profit

Year-over-year trend comparison (2013 vs 2012)

🎨 Design Highlights

Dark theme for professional presentation and contrast.

Accent colors:

Pink → 2013 performance

Teal → 2012 baseline

Blue → Highest points

Red → Lowest points

Consistent layout across both dashboards for intuitive navigation.

Interactive filters and navigation buttons at the top of dashboards.

🧠 Key Insights

Sales grew by 180% compared to 2012, with profits up 229%.

Mountain Bikes contributed the highest sales and profit margins.

The Top 10 customers accounted for a significant portion of total revenue.

Customer retention improved — more repeat customers were recorded.

💡 Learnings

Efficient dashboard layout enhances readability and executive usability.

Consistent use of colors improves comparative analysis (2012 vs 2013).

Integrating data directly from a data warehouse ensures scalability and data integrity.

🧰 Tools Used

Tableau Desktop / Tableau Public

Internal Data Warehouse (SQL-based)

Excel (for initial data validation)

🚀 Outcome

This project demonstrates:

Full BI lifecycle from data extraction to visualization.

Advanced Tableau features including parameter controls, calculated fields, and layout containers.

End-to-end dashboard development aligned with real business scenarios.