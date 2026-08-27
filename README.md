# Superstore Sales Analysis & Business Dashboard

## 📊 Project Overview

This project analyzes the Superstore Orders dataset to understand sales performance, profitability, customer behavior, product performance, and operational efficiency.

The project was developed as an end-to-end Excel Data Analytics case study using Power Query, Pivot Tables, Pivot Charts, slicers, and interactive dashboards.

## 🎯 Business Objective

* Identify revenue-driving categories, regions, and markets
* Understand profit and loss drivers
* Compare customer segments
* Evaluate discount impact on profitability
* Measure delivery and shipping performance
* Analyze quarterly and yearly trends
* Identify best-selling and loss-making products
* Support data-driven business decisions

## 🧩 Business Requirements

The analysis was designed around 21 business questions:

### Sales Performance

* **BR-01:** Which product category generates the highest sales revenue?
* **BR-02:** Which region generates the highest sales?
* **BR-03:** Which market contributes the highest revenue?
* **BR-04:** Which customer segment contributes the highest sales and profit?
* **BR-05:** Which are the Top 5 countries by sales?

### Profitability

* **BR-06:** Which product category generates the highest and lowest profit?
* **BR-07:** Which product categories receive the highest average discount?
* **BR-08:** Which region generates the highest profit and the highest loss?
* **BR-09:** Which products are generating the highest losses?
* **BR-10:** Does discount reduce profitability?
* **BR-11:** Which sub-category generates the highest profit?

### Customer & Market

* **BR-12:** Which customer segment generates the highest profit?
* **BR-13:** Which market has the highest profit margin?

### Operations

* **BR-14:** What is the average delivery time?
* **BR-15:** Which shipping mode is used most frequently?
* **BR-16:** How do Weekend and Weekday sales compare?
* **BR-17:** How does profit margin vary across different quarters?

### Product Performance

* **BR-18:** Which product is sold the most?
* **BR-19:** Which product is sold the least?
* **BR-20:** Which products perform best across different categories and regions?
* **BR-21:** How does profit margin vary across different Sales Ranges?

## 📈 Dashboard Structure

### Page 1 — Executive Sales & Profitability

**Sheet:** `Executive-Sales & Profitability`

Includes:

* Total Orders
* Total Sales
* Total Profit
* Profit Margin
* Average Delivery
* Sales & Profit Margin by Category
* Sales & Profit by Region
* Discount vs Profitability
* Profit Margin by Quarter
* Profit Margin by Market

Interactive slicers:

* Year
* Segment
* Region
* Market

### Page 2 — Product-Customer-Operations

**Sheet:** `Product-Customer-Operations`

Includes:

* Top 5 Products by Profit
* Bottom 5 Products by Profit
* Profit Margin by Segment
* Profit by Subcategory
* Average Delivery Day by Shipping Mode
* Order Volume by Shipping Mode

The dashboards were tested with slicer selections and the KPIs/charts respond dynamically.

## 🔢 Overall KPI Snapshot

With filters cleared, the dashboard shows approximately:

| KPI              |     Value |
| ---------------- | --------: |
| Total Orders     |    51.29K |
| Total Sales      |    12.64M |
| Total Profit     |     1.47M |
| Profit Margin    |    11.62% |
| Average Delivery | 3.97 days |

## 🔎 Key Findings

### Technology leads category sales

Technology generates approximately **4.74M** in sales, compared with Furniture at approximately **4.11M** and Office Supplies at approximately **3.79M**.

### Market profitability varies considerably

Profit margin by market ranges from **5.45% in EMEA** to **26.62% in Canada**. EU is 12.69%, US 12.47%, APAC 12.20%, Africa 11.34%, and LATAM 10.24%.

### Home Office has the highest segment margin

Home Office has an approximately **11.99%** profit margin, followed by Corporate at 11.58% and Consumer at 11.51%.

### Copiers are the strongest sub-category by profit

Copiers generate approximately **258.57K** in profit.

### Tables are a major loss-making sub-category

Tables show approximately **-64.08K** in profit and require further investigation.

### Several products generate significant losses

The bottom-profit analysis highlights products such as Cubify CubeX 3D Printer Double Head Print, Lexmark MX611dhe Monochrome Laser Printer, Motorola Smart Phone, Cordless, Cubify CubeX 3D Printer Triple Head Print, and Bevis Round Table, Adjustable Height.

### Higher discount ranges show weaker profitability

The Discount vs Profitability analysis shows a substantial decline in profitability at higher discount levels, making discount strategy an important area for management review.

## 💡 Business Recommendations

* Review consistently loss-making products and sub-categories.
* Investigate pricing, discounting, shipping costs, and product mix for weak products.
* Protect and expand high-profit product lines such as Copiers.
* Review aggressive discounting and establish margin-aware discount thresholds.
* Investigate why EMEA has much lower profitability than Canada.
* Compare product mix, pricing, discounting, and operating factors across markets.
* Use shipping-volume and delivery metrics to improve logistics planning.

## 🛠️ Data Preparation

Power Query and Excel analysis were used to prepare the data. The project includes analytical fields/calculations such as:

* Delivery Days
* Month Name
* Quarter
* Year
* Profit Margin %
* Sales Range
* Profit Status
* Day Type (Weekday / Weekend)

## 📁 Recommended Repository Structure

```text
Superstore-Sales-Analysis/
├── README.md
├── Excel/
│   └── SuperStoreOrdersProject.xlsx
├── Business-Requirements/
│   └── SuperStore_Business_Requirements_Professional.docx
├── Insights/
│   └── Superstore_Final_Insights.pdf
├── Presentation/
│   └── Superstore_Business_Presentation.pdf
└── Screenshots/
    ├── Executive-Dashboard.png
    └── Product-Customer-Operations.png
```

## 📦 Final Deliverables

1. Interactive Excel Dashboard
2. Business Requirements & 21 Business Questions
3. Final Insights Report
4. Executive Presentation

## 🧠 Analyst Thinking

**Business Question → Data Preparation → Analysis → Visualization → Insight → Business Recommendation**

The purpose of the project is not simply to create charts, but to turn transactional data into actionable business insights.

## 👤 Author

**Prabhat Kumar**
Data Analytics Portfolio Project
Excel • Power Query • Pivot Tables • Pivot Charts • Dashboarding
