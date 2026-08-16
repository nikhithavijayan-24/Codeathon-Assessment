# 📊 Nexa Mart Sales Analysis | Power BI

## 📌 About the Project

This project is a Power BI sales analysis dashboard created as part of my Data Analytics learning journey.

I worked with a retail sales dataset containing information about orders, customers, products, categories, regions, sales, profit, cost and quantity. The main objective was to clean and prepare the data, perform the required calculations, and turn the raw data into an interactive dashboard that can be used to understand business performance.

While working on the project, I focused not only on creating visuals, but also on understanding what the data was actually showing and using those findings to create meaningful insights and recommendations.

---

## 🎯 Project Objectives

The main objectives of this project were to:

- Clean and prepare the given dataset
- Handle missing values and duplicate records
- Standardize and validate the data
- Create DAX calculations required for the analysis
- Build an interactive Power BI dashboard
- Analyse sales, products, customers and profitability
- Identify important business insights
- Provide recommendations based on the analysis

---

# 🧹 Data Cleaning & Preparation

I started the project by working with the dataset in **Power Query Editor**.

The main data preparation activities included:

- Identifying missing values
- Handling missing categorical and numerical values
- Removing duplicate records
- Correcting data types
- Cleaning numerical fields
- Standardizing the Order Date column
- Checking the quality and validity of the cleaned data

After completing the cleaning process, the prepared dataset was loaded into Power BI for further analysis.

---

# 🧮 DAX Calculations

I created different measures, calculated columns and a calculated table to support the analysis.

### Measures Created

- Total Sales
- Total Profit
- Total Orders
- Total Quantity Sold
- Total Customers
- Total Cost
- Profit Margin
- Average Orders per Customer

### Calculated Columns Created

- Sales Category
- Profit Type
- Quantity Type
- Profit
- Profit Cost Difference
- Order Year

### Calculated Table Created

- EastRegionOrders

These calculations were used across the dashboard to create KPI cards, charts, filters and insights.

---

# 📊 Dashboard

I divided the dashboard into four pages so that each page focuses on a specific area of the business.

---

## 01 | Sales Overview

The **Sales Overview** page provides a quick view of the overall business performance.

### KPIs

- Total Sales – **94.34M**
- Total Orders – **1K**
- Total Profit – **5.15M**
- Profit Margin – **5.46%**

### Analysis

- Sales by Region
- Sales by Category
- Monthly Sales Trend

### Key Findings

- Total sales are approximately **94.34M**.
- Total profit is approximately **5.15M**.
- The overall profit margin is approximately **5.46%**.
- East is one of the strongest-performing regions.
- Furniture contributes the highest sales among the categories shown.

---

## 02 | Product Analysis

The **Product Analysis** page focuses on product demand, order volume and sales performance.

### KPIs

- Total Orders – **1K**
- Total Products – **9**
- Total Quantity Sold – **3K**

### Analysis

- Order Distribution by Region
- Top 5 Trending Products by Order Count
- Total Sales by Product

### Key Findings

The Top 5 products based on order count are:

| Product | Orders |
|---|---:|
| Monitor | 132 |
| Laptop | 131 |
| Bookshelf | 129 |
| Cabinet | 125 |
| Headphones | 122 |

Monitor is the leading product by order count and also shows strong sales performance, with approximately **12.9M** in sales.

---

## 03 | Customer Analysis

The **Customer Analysis** page looks at customer contribution and purchasing behaviour.

### KPIs

- Unique Customers – **101**
- Total Orders – **1K**
- Total Sales – **94.34M**
- Total Profit – **5.15M**

### Analysis

- Top 10 Customers by Sales
- Customers by Order Count
- Customer Sales Trend

### Key Findings

- The dataset contains **101 unique customers**.
- Jordan Henderson is the highest identified customer by sales, with approximately **2.2M**.
- Tracy House has the highest order count among identified customers, with **22 orders**.
- Some records contain **Unknown** customer values, which were treated as missing customer information rather than actual customers.

---

## 04 | Profitability

The **Profitability** page focuses on profit performance and the relationship between sales, cost and profitability.

### KPIs

- Total Profit – **5.15M**
- Total Cost – **89.21M**
- Profit Margin – **5.46%**

### Analysis

- Profit Cost Difference by Category
- Profit by Sales Category
- Profit by Month
- Profit by Product

### Key Findings

- Total profit is approximately **5.15M**.
- The overall profit margin is **5.46%**.
- The High Sales Category contributes approximately **4.8M** in profit.
- Laptop is the highest-profit product at approximately **0.71M**.
- Bookshelf follows with approximately **0.69M**.
- Monitor contributes approximately **0.65M**.
- August records the highest monthly profit at approximately **0.49M**.

---

# 💡 Business Insights

After analysing the different dashboard pages, a few patterns stood out:

- Sales performance is strongly influenced by a few leading regions and categories.
- Monitor is one of the strongest-performing products in terms of both orders and sales.
- A relatively small number of customers contribute significantly to overall sales.
- High-performing products also provide important opportunities for inventory and promotional planning.
- Profitability varies across products, categories and months.
- The overall profit margin of **5.46%** indicates that there is room for improving profitability through better cost management and product-level decisions.

---

# 📌 Recommendations

Based on the analysis, I would focus on the following areas:

### Product Performance
Prioritize high-demand products and maintain sufficient inventory for products with consistently strong order volumes.

### Customer Retention
Identify high-value and frequent customers and use targeted offers or loyalty strategies to encourage repeat purchases.

### Regional Performance
Continue strengthening high-performing regions while looking for ways to improve the performance of lower-performing regions.

### Profitability
Review costs and pricing for products and categories with lower profit contribution.

### Monthly Performance
Use monthly sales and profit trends to plan promotions and other strategies during weaker-performing periods.

---

# 🛠️ Tools Used

- **Microsoft Power BI Desktop**
- **Power Query**
- **DAX**
- **CSV / Excel Dataset**
- **GitHub**

---

# 📈 Skills Applied

- Data Cleaning
- Data Transformation
- Power Query
- DAX
- Data Analysis
- Data Visualization
- KPI Creation
- Dashboard Development
- Calculated Columns
- Calculated Tables
- Measures
- Interactive Slicers
- Business Insights
- Data Storytelling

---

# 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning & Preparation
     ↓
Power Query Transformations
     ↓
Power BI Data Model
     ↓
DAX Calculations
     ↓
KPI & Visual Creation
     ↓
Interactive Dashboard
     ↓
Insights & Recommendations



**📁 Project Structure**

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

📚 What I Learned

Working on this project helped me understand the complete workflow of a Power BI project, from preparing raw data to presenting the final insights.

Some of the main things I practised were:

Working with messy datasets
Handling missing and duplicate values
Using Power Query for data preparation
Creating and using DAX measures
Creating calculated columns and calculated tables
Designing KPI cards
Choosing appropriate charts for different types of analysis
Using slicers to make a dashboard interactive
Converting analytical results into business insights
Presenting findings in a clear and structured way
