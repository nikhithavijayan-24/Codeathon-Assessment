# 📊 Nexa Mart Sales Analysis | Power BI

## 📌 About the Project

Nexa Mart Sales Analysis is a Power BI project I worked on as part of my Data Analytics learning journey.

The project started with a sales dataset containing information about orders, customers, products, categories, regions, sales, profit, cost and quantity. I worked through the dataset step by step — from cleaning and preparing the data to creating calculations, building visuals and finally presenting the findings through an interactive dashboard.

The main focus of this project was to understand the data from different business perspectives and turn the analysis into clear insights and recommendations.

---

## 🎯 Project Objectives

Through this project, I worked on:

- Cleaning and preparing the sales dataset
- Handling missing and duplicate values
- Creating the required DAX calculations
- Building KPI cards and interactive visuals
- Analysing sales performance across regions and categories
- Understanding product and customer performance
- Analysing profit, cost and profit margin
- Creating insights from the dashboard
- Providing recommendations based on the findings

---

## 🧹 Data Cleaning & Preparation

I used **Power Query** to prepare the raw dataset before starting the analysis.

The main preparation work included:

- Checking the quality of the dataset
- Identifying missing values
- Handling duplicate records
- Correcting data types
- Cleaning and standardising data where required
- Preparing the date field for analysis
- Validating the cleaned dataset before creating the dashboard

This step helped me understand how important data preparation is before moving into visualisation and analysis.

---

## 🧮 DAX Calculations

I created different DAX calculations to support the analysis and dashboard requirements.

### Measures Created

- Total Sales
- Total Profit
- Total Orders
- Total Products
- Total Quantity Sold
- Total Customers
- Unique Customers
- Total Cost
- Profit Margin
- YTD Sales

### Calculated Columns Created

- Sales Category
- Profit Type
- Quantity Type
- Profit
- Profit Cost Difference
- Order Year

### Calculated Table Created

- East Region Orders

These calculations were used to create the KPI cards, charts, slicers and analysis across the different report pages.

---

# 📊 Dashboard

I organised the report into four pages, with each page focusing on a different area of the business.

---

## 01. Sales Overview

The Sales Overview page gives a high-level view of the overall sales performance.

### Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | 94.34M |
| Total Orders | 1K |
| Total Profit | 5.15M |
| Profit Margin | 5.46% |

### Main Analysis

- Total Sales by Region
- Total Sales by Category
- Total Sales by Month
- Region, Year and Category slicers

### Key Findings

- Total sales reached approximately **94.34M**.
- Total profit was approximately **5.15M**.
- The overall profit margin was **5.46%**.
- East was the strongest-performing region among the identified regions.
- Furniture generated the highest sales among the categories shown.

### Recommendations

- Continue strengthening sales performance in the East region.
- Focus on the Furniture category and its high-performing products.
- Monitor weaker-performing regions and identify opportunities for improvement.
- Use monthly sales trends to plan promotions during lower-performing periods.

---

## 02. Product Analysis

The Product Analysis page focuses on product demand, order volume and sales performance.

### Key KPIs

| KPI | Value |
|---|---:|
| Total Orders | 1K |
| Total Products | 9 |
| Total Quantity Sold | 3K |

### Main Analysis

- Total Orders by Region
- Total Sales by Product
- Top 5 Trending Products by Order Count

### Top 5 Products by Order Count

| Product | Orders |
|---|---:|
| Monitor | 132 |
| Laptop | 131 |
| Bookshelf | 129 |
| Cabinet | 125 |
| Headphones | 122 |

### Key Findings

- **Monitor** recorded the highest order count with **132 orders**.
- Laptop followed closely with **131 orders**.
- Monitor also generated approximately **12.9M** in sales.
- The top-performing products account for a significant share of the overall product demand.

### Recommendations

- Maintain sufficient inventory for consistently high-demand products.
- Give special attention to Monitor and Laptop due to their strong order performance.
- Review lower-performing products and consider targeted promotions where appropriate.

---

## 03. Customer Analysis

The Customer Analysis page focuses on customer contribution and purchasing behaviour.

### Key KPIs

| KPI | Value |
|---|---:|
| Unique Customers | 101 |
| Total Sales | 94.34M |
| Total Profit | 5.15M |

### Main Analysis

- Top 10 Customers by Sales
- Total Orders by Customer
- Total Sales by Year

### Key Findings

- The dataset contains **101 unique customers**.
- **Jordan Henderson** was the highest identified customer by sales, contributing approximately **2.2M**.
- **Tracy House** recorded the highest order count among the identified customers, with **22 orders**.
- Some customer records were marked as **Unknown**, which indicates missing customer information in the dataset.

### Recommendations

- Focus on high-value customers through targeted offers and retention strategies.
- Encourage repeat purchases from customers with higher order frequency.
- Identify frequent customers and consider personalised promotions or loyalty incentives.
- Improve the quality of missing customer information where possible.

---

## 04. Profitability

The Profitability page focuses on profit, cost and overall profitability.

### Key KPIs

| KPI | Value |
|---|---:|
| Total Profit | 5.15M |
| Total Cost | 89.21M |
| Profit Margin | 5.46% |

### Main Analysis

- Profit Cost Difference by Category
- Total Profit by Sales Category
- Total Profit by Month
- Total Profit by Product

### Key Findings

- Total profit was approximately **5.15M**.
- The overall profit margin was **5.46%**.
- The High Sales Category contributed approximately **4.8M** in profit.
- Laptop generated approximately **0.71M** in profit.
- Bookshelf generated approximately **0.69M**.
- Monitor generated approximately **0.65M**.
- August recorded the highest monthly profit at approximately **0.49M**.

### Recommendations

- Focus on products that consistently contribute higher profit.
- Maintain healthy inventory levels for high-profit products.
- Review products and categories with lower profit contribution.
- Monitor costs closely to improve the overall profit margin.
- Use monthly profit trends to identify weaker periods and plan suitable strategies.

---

# 💡 Overall Key Insights

After working through the different areas of the dashboard, the main points I identified were:

- Total sales reached approximately **94.34M**.
- Total profit was approximately **5.15M**.
- The overall profit margin was **5.46%**.
- East was the strongest-performing region in the analysis.
- Furniture was the leading category by sales.
- Monitor was the top product by order count and also generated strong sales.
- A relatively small group of customers contributed significantly to sales.
- Profit performance varied across products and months.
- Cost management is an important area for improving overall profitability.

---

# 📌 Recommendations

Based on the analysis, my main recommendations are:

- Strengthen the performance of high-performing regions and categories.
- Maintain inventory for products with consistently high demand.
- Focus on high-value customers and encourage repeat purchases.
- Review lower-performing products, regions and periods.
- Monitor costs to improve profit margins.
- Use sales and profit trends to plan targeted promotions and business strategies.

---

## 🛠️ Tools Used

- **Microsoft Power BI Desktop**
- **Power Query**
- **DAX**
- **Microsoft Excel / CSV**
- **GitHub**

---

## 📈 Skills Applied

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

## 📁 Project Structure

```text
Codeathon-Assessment/
│
├── Codeathon Answers.pbix
├── Questions.docx
├── SalesData_1000Rows_WithIssues_copy.csv
└── README.md
