# Codeathon-Assessment
Absolutely. For GitHub, I would make it **more portfolio-level and professional**, rather than making it look like an assignment submission.

Copy-paste this directly into `README.md`:

````markdown
# 📊 Nexa Mart Sales Analytics Dashboard

> An interactive Power BI dashboard designed to analyze sales performance, product trends, customer behavior, and profitability using a cleaned retail sales dataset.

---

## 📌 Project Overview

**Nexa Mart Sales Analytics** is an end-to-end **Power BI Data Analytics project** developed as part of a Power BI Module End Evaluation.

The project transforms a raw sales dataset into an interactive business intelligence dashboard through:

- Data cleaning and transformation
- Data quality handling
- DAX calculations
- KPI development
- Interactive visualizations
- Business performance analysis
- Insight generation
- Data-driven recommendations

The final dashboard is organized into four analytical views:

**Sales Overview · Product Analysis · Customer Analysis · Profitability**

---

## 🎯 Business Objective

The primary objective of this project is to transform transactional sales data into meaningful business insights that can help answer questions such as:

- How are overall sales and profits performing?
- Which regions and categories contribute the most to sales?
- Which products generate the highest order volume and sales?
- Which customers contribute the most to business performance?
- How does profitability change over time?
- Where are opportunities for improving sales and profitability?

---

# 🗂️ Dashboard Structure

## 01 · Sales Overview

Provides a high-level summary of the company's overall sales performance.

### Key Metrics

- **Total Sales:** 94.34M
- **Total Orders:** 1K
- **Total Profit:** 5.15M
- **Profit Margin:** 5.46%

### Visual Analysis

- Sales by Region
- Sales by Category
- Monthly Sales Trend

### Interactive Filters

- Region
- Year
- Category

### Key Focus

The page provides an executive-level overview of sales performance and highlights the strongest regions, categories, and sales periods.

---

## 02 · Product Analysis

Analyzes product-level performance and order activity.

### Key Metrics

- **Total Orders:** 1K
- **Total Products:** 9
- **Total Quantity Sold:** 3K

### Visual Analysis

- Order Distribution by Region
- Total Sales by Product
- Top 5 Trending Products by Order Count

### Key Findings

- **East** leads regional order volume with **263 orders (26.3%)**.
- **South** follows with **255 orders (25.5%)**.
- **Monitor** leads the Top 5 products by order count with **132 orders**.
- Monitor also records approximately **12.9M** in sales.

### Business Focus

The analysis helps identify high-demand products and supports inventory planning, product prioritization, and promotional decisions.

---

## 03 · Customer Analysis

Focuses on customer contribution and purchasing behavior.

### Key Metrics

- **Unique Customers:** 101
- **Total Orders:** 1K
- **Total Sales:** 94.34M
- **Total Profit:** 5.15M

### Visual Analysis

- Top 10 Customers by Sales
- Top Customers by Order Count
- Customer Sales Trend

### Key Findings

- The dataset contains **101 unique customers**.
- **Jordan Henderson** is the highest identified customer by sales, contributing approximately **2.2M**.
- **Tracy House** records the highest order count among identified customers with **22 orders**.

### Business Focus

Customer analysis helps identify high-value and frequent customers, supporting customer retention, targeted promotions, and relationship management.

---

## 04 · Profitability

Provides a detailed view of profit performance and cost impact.

### Key Metrics

- **Total Profit:** 5.15M
- **Total Cost:** 89.21M
- **Profit Margin:** 5.46%

### Visual Analysis

- Profit Cost Difference by Category
- Profit by Sales Category
- Monthly Profit Trend
- Profit by Product

### Key Findings

- Overall profit is approximately **5.15M**.
- Overall profit margin stands at **5.46%**.
- The High Sales Category contributes approximately **4.8M** in profit.
- **Laptop** is the highest-profit product at approximately **0.71M**.
- **Bookshelf** follows with approximately **0.69M**.
- **Monitor** contributes approximately **0.65M**.
- August records the highest monthly profit at approximately **0.49M**.

### Business Focus

The page identifies profitable products and categories while highlighting opportunities for cost optimization and margin improvement.

---

# 🧹 Data Preparation

The raw dataset was prepared using **Power Query** before analysis.

### Data Cleaning Activities

- Identified and handled missing values
- Removed duplicate records
- Standardized date fields
- Corrected data types
- Cleaned numerical fields
- Prepared categorical fields for analysis
- Validated the cleaned dataset before loading it into the Power BI model

### Data Transformation

Additional analytical fields were created to support business analysis, including:

- Sales Category
- Profit Type
- Quantity Type
- Profit
- Profit Cost Difference
- Order Year

---

# 🧮 DAX Analysis

The project includes calculated tables, calculated columns, and measures.

## Calculated Table

### East Region Orders

Creates a separate table containing orders belonging to the East region.

---

## Calculated Column

### Profit Cost Difference

Used to analyze the difference between profit and cost across categories and other business dimensions.

---

## Measure

### Total Profit

Used throughout the dashboard for profit analysis and KPI reporting.

---

## Profit Margin

The profitability analysis also uses a measure-based profit margin calculation:

The measure is formatted as a percentage in Power BI.

---

# 📊 Key Business Insights

The completed dashboard highlights several important patterns:

### Sales Performance

* Total sales reached approximately **94.34M**.
* Total profit reached approximately **5.15M**.
* Overall profit margin stands at **5.46%**.
* East is the leading region in order and sales contribution.
* Furniture is the leading category by sales.

### Product Performance

* Monitor is one of the strongest-performing products.
* High-order products represent important opportunities for inventory planning.
* Product-level sales analysis helps identify products requiring greater focus.

### Customer Performance

* The dataset contains **101 unique customers**.
* High-value customers make a significant contribution to overall sales.
* Frequent customers provide opportunities for retention and loyalty strategies.

### Profitability

* High Sales Category contributes the majority of total profit.
* Laptop, Bookshelf, and Monitor are among the strongest profit-generating products.
* Monthly profitability varies across the year, creating opportunities for targeted planning.

---

# 💡 Business Recommendations

Based on the analysis, the following actions are recommended:

### 01 — Strengthen High-Performing Products

Maintain sufficient inventory and promotional support for products generating high sales and order volumes.

### 02 — Focus on High-Value Customers

Develop targeted offers and retention strategies for customers contributing significant sales and order frequency.

### 03 — Strengthen Regional Performance

Continue supporting high-performing regions while developing targeted strategies for lower-performing regions.

### 04 — Improve Profitability

Review cost structures and pricing strategies for products and categories with weaker profitability.

### 05 — Optimize Sales During Low-Performance Periods

Use targeted campaigns and promotional strategies during weaker sales and profit periods.

---

# 🔄 Project Workflow

```text
Raw Dataset
     │
     ▼
Power Query
     │
     ▼
Data Cleaning & Transformation
     │
     ▼
Data Validation
     │
     ▼
Power BI Data Model
     │
     ▼
DAX Calculations
     │
     ▼
KPI Development
     │
     ▼
Interactive Visualizations
     │
     ▼
Dashboard Development
     │
     ▼
Business Insights
     │
     ▼
Recommendations
```

---

# 🛠️ Tools & Technologies

| Technology                | Purpose                                            |
| ------------------------- | -------------------------------------------------- |
| **Microsoft Power BI**    | Dashboard development and visualization            |
| **Power Query**           | Data cleaning and transformation                   |
| **DAX**                   | Measures, calculated columns and calculated tables |
| **Microsoft Excel / CSV** | Source data                                        |
| **GitHub**                | Project documentation and version control          |

---

# 📈 Skills Demonstrated

* Data Cleaning
* Data Transformation
* Power Query
* Data Modeling
* DAX
* Calculated Columns
* Calculated Tables
* Measures
* KPI Development
* Data Visualization
* Dashboard Design
* Interactive Slicers
* Business Intelligence
* Business Analysis
* Insight Generation
* Data Storytelling

---

# 📁 Project Structure

```text
Nexa-Mart-Sales-Analysis/
│
├── Dataset/
│   └── SalesData_1000Rows_WithIssues_copy.csv
│
├── PowerBI/
│   └── Codeathon Answers.pbix
│
├── Documentation/
│   └── Questions.docx
│
└── README.md
```

---

# 🎓 Assessment Coverage

This project addresses the core requirements of the Power BI assessment:

### Data Cleaning & Loading

✔ Missing-value handling
✔ Duplicate handling
✔ Date standardization
✔ Data preparation

### Visualizations & Insights

✔ Order distribution by region
✔ Top 5 trending products by order count
✔ Profit trend over time
✔ Interactive dashboard analysis

### DAX Calculations

✔ East Region Orders calculated table
✔ Profit Cost Difference calculated column
✔ Total Profit measure
✔ Additional analytical calculations

---

# 🚀 Project Outcome

The project demonstrates how raw transactional data can be transformed into an **interactive Business Intelligence solution**.

The final dashboard enables users to move from:

**Raw Data → Clean Data → Analysis → Visualization → Insights → Business Decisions**

through a structured and interactive Power BI reporting experience.

---

## 👩‍💻 Project

### Nexa Mart Sales Analytics

**Codeathon Assessment**

*Data → Insights → Decisions*

```

This version is more suitable for a **professional GitHub portfolio** because it reads as a real analytics project rather than simply an assignment answer sheet.
```
