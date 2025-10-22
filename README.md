# 📊 Tableau End-to-End BI Project
## Customer and Sales Performance Dashboards (2013)

---

## 🧩 Overview
This project demonstrates a complete **end-to-end Tableau analytics workflow**, analyzing **sales and customer performance** for the year **2013**.

The dataset originates from an **internal data warehouse**, which was **cleaned, modeled, and visualized** using Tableau Desktop.

This project replicates a **real-world BI solution**, combining **data engineering**, **visualization design**, and **business storytelling** in a single package.

---

## 🎯 Objectives
- Connect and prepare data from a data warehouse.
- Create interactive dashboards to monitor customer behavior and sales performance.
- Compare **year-over-year performance (2013 vs 2012)**.
- Identify **top customers**, **profit trends**, and **product category insights**.
- Apply design principles that support **clarity and decision-making**.

---

## 🗂️ Project Structure

| Component | Description |
|-----------|-------------|
| `Dashboard.twbx` | Tableau packaged workbook containing both dashboards and data model |
| `Sales Dashboard.png` | Snapshot of the Sales Performance Dashboard |
| `Customer Dashboard.png` | Snapshot of the Customer Insights Dashboard |
| **Data Source** | Extracted from internal data warehouse tables (`Sales`, `Orders`, `Customers`, `Products`) |

---

## ⚙️ Process Overview

### 1. Data Preparation
- Data pulled from **internal data warehouse** (fact and dimension tables).
- Joined and cleaned in **Tableau’s Data Source tab**.
- Created calculated fields:

```text
Profit Margin = SUM([Profit]) / SUM([Sales])
Sales per Customer = SUM([Sales]) / COUNTD([Customer ID])
Year-over-Year Growth = ([Current Year] - [Previous Year]) / [Previous Year]

