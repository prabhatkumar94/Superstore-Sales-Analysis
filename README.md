# 📊 Superstore Sales Analysis & Business Dashboard

> An end-to-end Excel Data Analytics project analysing 51K+ orders to understand sales, profit, customers, products, markets, and delivery performance.

---

## 📌 Project Overview

This project analyses the **Superstore Orders dataset** using Microsoft Excel to answer real business questions and turn the results into useful business insights.

The project covers the complete analytics process:

**Data Cleaning → Data Preparation → Analysis → Dashboard → Insights → Recommendations**

I used **Power Query, Pivot Tables, Pivot Charts, and Slicers** to analyse the data and build an interactive dashboard.

The analysis is organised around **21 Business Requirements (BR01–BR21)** covering sales, profitability, customers, markets, products, and operations.

---

## 🎯 Business Objectives

The main objectives of this project were to:

- Identify the categories, regions, markets, and countries driving sales
- Understand which products and categories generate profit or loss
- Compare customer segment performance
- Study the relationship between discounts and profit margin
- Analyse delivery and shipping performance
- Compare weekday and weekend sales
- Analyse quarterly profit margin
- Identify best-selling and slow-moving products
- Understand profitability across different transaction sizes
- Convert analysis into practical business recommendations

---

## 🛠️ Tools Used

- **Microsoft Excel**
- **Power Query**
- **Pivot Tables**
- **Pivot Charts**
- **Slicers**
- **Data Cleaning & Transformation**
- **Data Analysis**
- **Data Visualization**
- **Dashboard Development**

---

# 📊 Dashboard

The project contains two interactive dashboard pages.

## Page 1 — Executive Sales & Profitability

**Sheet:** `Executive-Sales & Profitability`

### KPIs

- Total Orders
- Total Sales
- Total Profit
- Profit Margin
- Average Delivery

### Analysis

- Sales & Profit Margin by Category
- Sales & Profit by Region
- Discount vs Profitability
- Profit Margin by Quarter
- Profit Margin by Market

### Slicers

- Year
- Segment
- Region
- Market

---

## Page 2 — Product, Customer & Operations

**Sheet:** `Product-Customer-Operations`

### Analysis

- Top 5 Products by Profit
- Bottom 5 Products by Profit
- Profit Margin by Segment
- Profit by Subcategory
- Average Delivery by Shipping Mode
- Order Volume by Shipping Mode

The dashboard is interactive, and the KPIs and charts update when different slicer selections are applied.

---

# 📷 Dashboard Preview

### Executive Dashboard

![Executive Dashboard](Screenshots/Executive-Dashboard.png)

### Product, Customer & Operations

![Product Customer Operations](Screenshots/Product-Customer-Operations.png)

---

# 🔢 Overall KPI Snapshot

With all dashboard filters cleared:

| KPI | Value |
|---|---:|
| **Total Orders** | **51.29K** |
| **Total Sales** | **12.64M** |
| **Total Profit** | **1.47M** |
| **Profit Margin** | **11.62%** |
| **Average Delivery** | **3.97 days** |

---

# 🔎 Key Findings

### 1. Technology leads category sales

Technology generated approximately **4.74M** in sales, followed by Furniture at **4.11M** and Office Supplies at **3.79M**.

### 2. Central leads regional sales and profit

Central generated approximately **2.82M** in sales and **311.40K** in profit.

### 3. APAC is the largest market by sales

APAC contributed approximately **3.59M**, or **28.36%** of total sales.

### 4. Consumer is the largest customer segment

Consumer generated approximately **6.51M** in sales and **749.24K** in total profit.

Home Office had the highest segment profit margin at **11.99%**.

### 5. Higher discounts are linked with lower profit margins

Profit margin fell from **25.32% at 0% discount** to **-51.27% above 30% discount**.

This shows a strong relationship between higher discount levels and weaker profitability, although the analysis does not prove that discounting alone causes the losses.

### 6. Tables is the only loss-making subcategory

Tables generated approximately **-64.08K** in profit, while Copiers generated the highest subcategory profit at approximately **258.57K**.

### 7. Canada has the highest market margin but a very small sales base

Canada recorded the highest market profit margin at **26.62%**, but contributed only approximately **66.93K (0.53%)** in sales.

EMEA had the lowest market margin at **5.45%**.

### 8. Standard Class dominates shipping

Standard Class was used for **30,775 orders** and had the longest average delivery time at approximately **5.00 days**.

### 9. Weekdays generate most of the business

Weekdays generated approximately **88.92% of sales** and **88.63% of profit**.

### 10. Larger transactions generally have stronger margins

Profit margin increased across the Sales Band analysis:

| Sales Band | Profit Margin |
|---|---:|
| 0–100 | **5.37%** |
| 101–500 | **9.03%** |
| 501–1,000 | **10.74%** |
| 1,001–5,000 | **14.89%** |
| 5,000+ | **26.46%** |

The 5,000+ band has the highest margin, but its sales volume is much lower than the 1,001–5,000 band.

---

# 💡 Business Recommendations

Based on the analysis:

### Review high discount orders

Higher discount bands show much weaker margins. The business should review high-discount transactions and use clear discount limits that protect profitability.

### Review the Tables subcategory

Tables is the only loss-making subcategory. Pricing, discounts, product cost, shipping cost, and demand should be reviewed to understand the reason for the loss.

### Protect strong product categories

Technology and Copiers generate strong profit. Their pricing, stock availability, and margins should be monitored while looking for opportunities to grow profitable sales.

### Study the Canadian market

Canada has a high profit margin but a very small sales base. The business should understand what is driving the margin before trying to scale the market.

### Improve Standard Class delivery

Standard Class has the highest order volume and the longest delivery time. Delivery delays and logistics costs should be reviewed.

### Increase transaction value carefully

Higher-value transactions show stronger margins. The business can explore bundles, cross-selling, and upselling while keeping discounts under control.

### Investigate EMEA profitability

EMEA has the lowest market profit margin. Product mix, pricing, discounts, and operating costs should be compared with better-performing markets.

---

# 🧩 Business Requirements

The project was built around 21 business questions.

## Sales Performance

- **BR-01:** Which product category generates the highest sales revenue?
- **BR-02:** Which region generates the highest sales?
- **BR-03:** Which market contributes the highest revenue?
- **BR-04:** Which customer segment contributes the highest sales and profit?
- **BR-05:** Which are the Top 5 countries by sales?

## Profitability

- **BR-06:** Which product category generates the highest and lowest profit?
- **BR-07:** Which product categories receive the highest average discount?
- **BR-08:** Which region generates the highest profit, and which region has the lowest profit?
- **BR-09:** Which products are generating the highest losses?
- **BR-10:** Does discount reduce profitability?
- **BR-11:** Which sub-category generates the highest profit?

## Customer & Market

- **BR-12:** Which customer segment generates the highest profit?
- **BR-13:** Which market has the highest profit margin?

## Operations

- **BR-14:** What is the average delivery time?
- **BR-15:** Which shipping mode is used most frequently?
- **BR-16:** How do Weekend and Weekday sales compare?
- **BR-17:** How does profit margin vary across different quarters?

## Product Performance

- **BR-18:** Which product is sold the most?
- **BR-19:** Which product is sold the least?
- **BR-20:** Which products perform best across different categories and regions?
- **BR-21:** How does profit margin vary across different Sales Bands?

---

# 🛠️ Data Preparation

Power Query and Excel were used to prepare the dataset for analysis.

### Main preparation steps

- Checked data types
- Checked missing values
- Checked exact duplicate rows
- Reviewed zero and negative values
- Created analytical fields
- Prepared PivotTables for each business requirement
- Built PivotCharts and dashboard visuals

### Analytical fields created

- Delivery Days
- Month Name
- Quarter
- Year
- Profit Margin %
- Sales Band
- Profit Status
- Day Type — Weekday / Weekend

### Data Quality Note

The dataset contains **51,290 transaction rows**.

No exact duplicate transaction rows were identified.

Repeated Order IDs are expected because one order can contain multiple product line items.

There is one zero-sales transaction, which results in a blank Profit Margin value because:

**Profit Margin = Profit / Sales**

cannot be calculated when Sales = 0.

---

# 🔄 Analysis Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Power Query Transformation
   ↓
Feature Creation
   ↓
21 Business Requirements
   ↓
Pivot Table Analysis
   ↓
Dashboard
   ↓
Business Insights
   ↓
Recommendations
