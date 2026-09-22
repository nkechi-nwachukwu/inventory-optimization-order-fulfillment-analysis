# 📦 Inventory Optimization & Order Fulfillment Analysis



## 📊 Project Overview

This project analyzes inventory, sales, profitability, and order fulfillment data to identify operational inefficiencies, understand product and category performance, and uncover opportunities to improve delivery performance and profitability.

Using **Power BI, Power Query, and DAX**, the analysis transforms raw Global Superstore order data into an interactive business intelligence dashboard covering:

* Inventory and product performance
* Order fulfillment efficiency
* Delivery delays
* Shipping costs
* Sales and profit performance
* Discount impact
* Category and regional performance
* Loss-making products
* Operational trends over time

The goal is to connect **inventory and fulfillment performance with financial outcomes** and provide actionable insights for improving operational efficiency and profitability.

---
# 📊 Dashboard

The Power BI dashboard provides an interactive view of inventory, sales, fulfillment, and profitability performance.

![Dashboard Overview](images/dashboard-overview.png)

--- 

## 🎯 Business Objectives

The analysis addresses four key business questions:

1. **How efficiently are customer orders being fulfilled?**
2. **Which products and categories generate the strongest sales and profit contribution?**
3. **How do discounts and shipping costs affect profitability?**
4. **Where are operational and product-level improvements required?**

### Business Goals

* Reduce late deliveries
* Improve order fulfillment efficiency
* Identify high-performing products and categories
* Detect underperforming and loss-making products
* Monitor shipping cost efficiency
* Evaluate the profitability impact of discounts
* Identify regional and shipping-mode performance patterns
* Improve operational decision-making through KPI monitoring

---

## 📂 Dataset

**Source:** Kaggle — Global Superstore Dataset

The dataset contains **51,000+ orders** and includes information relating to:

* Order ID
* Product
* Category
* Sub-Category
* Region
* Country
* Sales
* Cost
* Profit
* Discount
* Shipping Cost
* Order Date
* Delivery Date
* Shipping Mode
* Customer information
* Geographic information

### Dataset Scale

| Metric                |      Value |
| --------------------- | ---------: |
| Orders                |    51,000+ |
| Total Sales           |    $12.64M |
| Average Shipping Cost | ~$12/order |
| Late Delivery Rate    |     18.16% |
| Profit Margin         |      11.6% |

---

## 🛠️ Tools & Technologies

### Power BI

Used to build the interactive dashboard, visualize operational performance, and communicate business insights.

### Power Query

Used for data preparation and transformation, including:

* Data cleaning
* Handling missing values
* Removing duplicates
* Standardizing date fields
* Preparing fields for analysis
* Creating analysis-ready datasets

### DAX

Used to create calculated measures and KPIs for:

* Sales
* Profit
* Profit margin
* Order processing time
* Delivery performance
* Late delivery rate
* Shipping cost analysis
* Discount impact
* Category performance

---

# 🔄 Project Methodology

## 1. Data Preparation

The raw Global Superstore dataset was imported into Power BI and prepared using Power Query.

The preparation process included:

* Reviewing data types
* Handling missing values
* Removing duplicate records
* Standardizing date fields
* Checking categorical fields
* Preparing calculated fields required for analysis

---

## 2. Data Transformation

Relevant fields were transformed to support analysis of:

* Order processing time
* Delivery performance
* Shipping efficiency
* Product profitability
* Discount impact
* Category performance
* Regional performance

---

## 3. KPI Development

DAX measures were created to monitor the most important business metrics.

### Core KPIs

| KPI                   | Business Meaning                                       |
| --------------------- | ------------------------------------------------------ |
| Total Sales           | Measures overall revenue generated                     |
| Total Profit          | Measures overall profitability                         |
| Profit Margin %       | Measures profit generated relative to sales            |
| Late Delivery %       | Measures the proportion of orders delivered late       |
| Average Shipping Cost | Measures average shipping cost per order               |
| Top Category          | Identifies the category contributing the highest sales |
| Order Processing Time | Measures the time required to process orders           |

---


### Dashboard Features

The dashboard includes:

* KPI cards
* Trend analysis
* Category analysis
* Product performance
* Regional analysis
* Shipping-mode analysis
* Profitability analysis
* Delivery performance
* Interactive slicers
* Map visualizations
* Bar charts
* Treemaps
* Time-series analysis

---

# 📈 Key Analysis

## 🚚 1. Order Fulfillment & Delivery Performance

The analysis measured delivery performance across different shipping modes and regions.

### Key Finding

**18.16% of deliveries were late.**

The analysis identified **Standard Class** as a major area of concern within the fulfillment process.

This indicates an opportunity to monitor standard shipping operations more closely and investigate the operational drivers contributing to delays.

![Late Delivery Rate](images/late-delivery-rate.png)

### Areas Analyzed

* Late delivery rate
* Shipping mode
* Region
* Order date
* Delivery date
* Order processing time

---

# 💰 2. Sales & Profitability

The dataset generated approximately **$12.64M in sales**, but the overall profit margin was approximately **11.6%**.

This highlights the importance of analyzing profitability alongside revenue.

![Total Profit](images/total-profit.png)

### Analysis included:

* Total sales
* Total profit
* Profit margin
* Category profitability
* Product profitability
* Regional profitability
* Discount impact
* Shipping cost impact

---

# 🏷️ 3. Category Performance

Category-level analysis was used to identify which product categories contributed the most revenue.

![Categories by Sales](images/categories-by-sales.png)

The analysis compared categories based on:

* Sales
* Profit
* Profit margin
* Product contribution

This helps identify categories that should receive greater attention in inventory and commercial planning.

---

# 📦 4. Product Performance

Product-level analysis was performed to identify:

* High-performing products
* Low-performing products
* High-revenue products
* Low-margin products
* Loss-making products

![Loss-Making Products](images/loss-making-products.png)

Loss-making products represent an important area for further investigation because continued sales do not necessarily translate into profitable growth.

Potential business actions include reviewing:

* Pricing
* Discounts
* Shipping costs
* Product demand
* Inventory strategy
* Product portfolio decisions

---

# 💸 5. Discount & Profitability Analysis

The project examined the relationship between discounts and profitability.

Discounting can increase sales volume, but excessive discounts on products with already-low margins can reduce overall profitability.

The analysis therefore evaluates discounts alongside:

* Sales
* Profit
* Profit margin
* Product performance
* Category performance

This provides a more complete view than evaluating sales volume alone.

---

# 🚢 6. Shipping Cost Analysis

Shipping costs were analyzed to understand their contribution to operational expenses and profitability.

The average shipping cost was approximately:

**$12 per order**

Shipping efficiency was evaluated across different operational dimensions to identify potential cost and fulfillment improvement opportunities.

---

# 📅 7. Sales Trend Analysis

Sales performance was analyzed over time to identify changes in business performance and potential seasonal patterns.

![Sales Trend](images/sales-trend.png)

The time-series analysis helps evaluate:

* Yearly sales performance
* Changes in revenue
* Category trends
* Periodic fluctuations
* Potential seasonal patterns

---

# 🌍 8. Regional Performance

Geographic analysis was used to understand differences in sales and fulfillment performance across regions.

The dashboard uses map-based visualization alongside other charts to identify geographic patterns.

Regional analysis helps answer questions such as:

* Which regions generate the most sales?
* Where are delivery delays concentrated?
* Which regions contribute the most profit?
* Are shipping costs consistent across regions?

---

# 🔍 Key Insights

The analysis identified several important operational patterns:

### 1. Delivery performance requires attention

**18.16% of deliveries were late**, with Standard Class identified as a key area for monitoring.

### 2. High sales do not automatically mean high profitability

The business generated approximately **$12.64M in sales**, while profit margin was approximately **11.6%**.

This demonstrates the importance of monitoring both revenue and profitability.

### 3. Product concentration creates dependency

A relatively small group of top-performing products contributes significantly to revenue.

This creates an opportunity to monitor product concentration and diversify performance where appropriate.

### 4. Discounts can pressure margins

Discounts applied to low-margin products can reduce profitability and should therefore be evaluated alongside product-level margins.

### 5. Loss-making products require investigation

Products generating negative or weak profitability may require reviews of pricing, discounting, shipping costs, and inventory strategy.

---

# 💡 Business Recommendations

Based on the analysis, the following operational actions can be considered:

### 🚚 Improve Standard Class Fulfillment

Monitor Standard Class delivery performance and investigate the operational causes of delays.

Track:

* Late delivery %
* Average processing time
* Shipping duration
* Regional delivery performance

### 📦 Prioritize High-Margin Products

Use profitability metrics alongside sales volume when making inventory and product planning decisions.

### 💸 Review Discounts

Reduce excessive discounting on products with already-low margins and evaluate discount effectiveness against profitability.

### 🔎 Review Loss-Making Products

Investigate products generating negative or weak profit margins.

Potential actions include:

* Repricing
* Reducing discounts
* Reviewing shipping costs
* Adjusting inventory levels
* Evaluating product portfolio decisions

### 🌍 Monitor Regional Performance

Track sales, profitability, shipping costs, and delivery performance by region to identify operational differences.

### 📊 Establish Ongoing KPI Monitoring

Use the dashboard as a recurring monitoring tool rather than a one-time analysis.

Recommended KPIs include:

* Late delivery rate
* Average shipping cost
* Profit margin
* Total profit
* Sales
* Order processing time
* Product profitability

---

# 📊 KPI Summary

| KPI                   |                      Result | Business Interpretation                                    |
| --------------------- | --------------------------: | ---------------------------------------------------------- |
| Total Sales           |                 **$12.64M** | Strong overall revenue generation                          |
| Late Delivery Rate    |                  **18.16%** | Significant fulfillment performance gap                    |
| Average Shipping Cost |              **~$12/order** | Important operational cost to monitor                      |
| Profit Margin         |                   **11.6%** | Revenue growth should be evaluated alongside profitability |
| Top Category          | **Identified in dashboard** | Highest sales contribution                                 |
| Loss-Making Products  | **Identified in dashboard** | Requires pricing/product strategy review                   |

---

# 🖼️ Dashboard Screenshots

## Dashboard Overview

![Dashboard Overview](images/dashboard-overview.png)

## Category Performance

![Categories by Sales](images/categories-by-sales.png)

## Sales Trend

![Sales Trend](images/sales-trend.png)

## Loss-Making Products

![Loss-Making Products](images/loss-making-products.png)

## Late Delivery KPI

![Late Delivery Rate](images/late-delivery-rate.png)

## Top Category KPI

![Top Category](images/top-category.png)

## Total Profit KPI

![Total Profit](images/total-profit.png)

## Profit Margin KPI

![Profit Margin](images/profit-margin.png)

---

# 📁 Repository Structure

```text
inventory-optimization-order-fulfillment-analysis/
│
├── README.md
│
├── images/
│   ├── dashboard-overview.png
│   ├── categories-by-sales.png
│   ├── sales-trend.png
│   ├── loss-making-products.png
│   ├── late-delivery-rate.png
│   ├── top-category.png
│   ├── total-profit.png
│   └── profit-margin.png
│
├── dashboard/
│   └── inventory-optimization-dashboard.pbix
│
└── data/
    └── README.md
```

---

# 📌 Skills Demonstrated

This project demonstrates practical skills in:

* **Power BI**
* **Power Query**
* **DAX**
* Data cleaning
* Data transformation
* KPI development
* Business intelligence
* Inventory analysis
* Order fulfillment analysis
* Supply chain analytics
* Profitability analysis
* Product performance analysis
* Operational performance monitoring
* Data visualization
* Business recommendations
* Dashboard design

---

# 🎯 Business Impact

The analysis connects **inventory and fulfillment operations with financial performance**, allowing decision-makers to identify where operational improvements can potentially contribute to better profitability.

The central business opportunity is to:

> **Reduce fulfillment inefficiencies, improve delivery performance, optimize product and discount decisions, and strengthen profitability through KPI-driven operational monitoring.**

---

# 🔗 Dashboard

**View the interactive Power BI dashboard:**

<img width="1800" height="1200" alt="Inventory   Order Perf Mockup" src="https://github.com/user-attachments/assets/376489cc-7df2-49a9-8fbd-11890faafadb" />

---

## 👩🏽‍💻 Author

**Dorothy Nwachukwu**

Business Analyst | Data & Operations Analytics

Skills: **Power BI • SQL • Excel • Tableau • Power Query • DAX • ERP & Operations Analytics**

Portfolio: **Dorothy's Data Desk**
