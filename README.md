# 📊 Business Performance Analytics
This repository contains a comprehensive Power BI dashboard for end-to-end business performance analysis. It provides actionable insights into sales, profitability, and operational efficiency by tracking key metrics across multiple departments.

##  Page 1: Performance Overview
## 🔍 Key Features  
- **Comprehensive KPI Tracking** → Monitor **Total Revenue**, **Total Cost**, **Total Profit**, **Profit Margin %**, and **Total Orders** at a glance.  
- **Customer Segmentation Insights** → Evaluate **Enterprise**, **SMB**, and **Distributor** contributions to total revenue dynamically.  
- **Customer-Level Profitability Analysis** → Compare customers’ **revenue**, **profit margins**, **average order value**, and **order frequency** to identify growth opportunities.  
- **Revenue & Profitability Trends** → Visualize **month-by-month changes** in revenue and profit margins to detect underlying business patterns.
---
## 📈 Insights & Trend Storytelling
### **1. Overall KPI Snapshot**  
**Jan 2024 – Aug 2025** totals:  
- **Total Revenue:** ₺1.612B  
- **Total Cost:** ₺1.178B  
- **Total Profit:** ₺434M  
- **Profit Margin:** **26.93%**  
- **Total Orders:** **1,000**  
> 💡 **Insight:**  
> While a **26.93% profit margin** may seem reasonable, profitability **varies significantly** across segments and customers.  
> Understanding **where profit comes from** is critical for optimizing growth strategies.
---
### **2. Customer Segment Contribution** *(Pie Chart)*  
- **Enterprise:** **35.52%**  
- **SMB:** **33.81%**  
- **Distributor:** **30.67%**
> 💡 **Insight:**  
> Revenue is **evenly distributed** across segments, which **reduces concentration risk**.  
> However, since no single segment dominates, **profit optimization strategies** must focus on **individual customers** rather than broad segments.
---  
### **3. Customer-Level Profitability Analysis** *(Matrix Table)*  

| Customer   | Total Revenue | AOV          | Profit Margin % | Total Orders |
|-----------|--------------|--------------|-----------------|--------------|
| **CUST-0202** | ₺22.26M | ₺3.18M | **21.79%** | 7 |
| **CUST-0191** | ₺14.90M | ₺2.98M | **34.10%** | 5 |

> 💡 **Insight 1:**  
> **High revenue ≠ high profitability** → **CUST-0202** has the **highest revenue** but only a **21.79% profit margin**, while **CUST-0191** achieves **34.10%**.  
> Possible reasons:  
> • Volume discounts for top customers  
> • Higher servicing or logistics costs  
> • Different pricing strategies  

> 💡 **Insight 2:**  
> **AOV vs. Order Frequency** → CUST-0202 places **more orders** and slightly higher **AOV**, yet profitability is lower.  
> This highlights that **sales volume alone doesn’t guarantee margin growth**.
---
### **4. Revenue & Profit Margin Trends Over Time** *(Clustered Column + Line Chart)*  

| Month      | Total Revenue | Profit Margin % |
|-----------|--------------|------------------|
| **Jan 2024** | ₺105.24M | **33.14%** |
| **Jun 2025** | ₺79.86M  | **40.79%** |
| **Aug 2025** | ₺45.31M  | **29.61%** |

> 💡 **Insight:**  
> The assumption that “**higher revenue = higher profit margin**” **does not always hold true**.  
> For example, **Jun 2025** shows a **40.79% profit margin** despite being **mid-range in revenue**.  
> Likely reasons:  
> • A shift in **product mix** toward higher-margin SKUs  
> • Lower discounting & promotional spending  
> • Improved production efficiency that month  

📌 **Business Implication:**  
Growth strategies should balance **revenue expansion** with **margin optimization** — focusing only on sales volume risks profitability erosion.
## 🚀 Next Steps  
This README currently documents **Page 1: Performance Overview**.  
Upcoming sections will include:  
- **Page 2:** Production & Inventory Analytics  
- **Page 3:** Forecast vs. Actuals & Demand Planning Insights
---
## 📃 Page 2: Profitability & Operations Analysis
## 🔍 Key Features
- **Revenue & Order Trends** → Analyze **month-over-month (MoM)** changes in Revenue and Total Orders to understand sales performance and demand fluctuations.
- **Profitability Deep Dive** → Track **Profit Margin %** to identify periods of both high and low profitability, and correlate them with revenue and order trends.
- **Segment & Category Profitability** → Break down profit margins by **customer segment** and **product category**, revealing which combinations are most profitable.
- **Fulfillment Performance** → Monitor **Total Orders** and **Late Orders %** to evaluate supply chain efficiency and identify areas for improvement.
- **Inventory & Workload Analysis** → Assess **Orders in Progress** and **Inventory in Progress** to gauge operational load and potential bottlenecks.
---
## 📈 Insights & Trend Storytelling
### **1. Overall Performance Snapshot (MoM)**
*(Based on data from Jan 2024 to Aug 2025)*
| Metric | Aug 2025 | MoM Change |
|---|---|---|
| **Revenue** | ₺45.3M | **▼ 42.6%** |
| **Total Orders** | 23 | **▼ 56.6%** |
| **Profit Margin %** | 29.61% | **▲ 7.0%** |

> 💡 **Insight:**
> **Revenue** and **Total Orders** experienced a significant sharp decline in August 2025, falling by over **40%** from the previous month. This indicates a potential major slowdown in sales. However, despite this drop, the **profit margin surprisingly increased by 7.0%**.

> **Business Implication:**
> This divergence suggests that the remaining sales in August likely came from **high-margin products or customer segments**, offsetting the overall volume loss. The business should investigate this shift: was it due to a strategic focus on more profitable SKUs, or was there an unexpected drop-off in low-margin, high-volume sales?
---
### **2. Profitability by Segment & Category** *(Clustered Column Chart)*

> 💡 **Insight 1: Significant Volatility**
> The **Profit Margin %** chart reveals **extreme volatility** across segments and categories. For example, in **Mar 2024**, Home/Enterprise had a **-223.31%** margin, while Electronics/SMB saw a healthy **36.94%**. Similarly, in **Nov 2024**, Electronics/SMB achieved a massive **59.82%** margin.

> **Business Implication:**
> This extreme fluctuation points to potential issues in **pricing strategy, cost management, or production efficiency**. Negative margins, especially large ones, indicate a critical need for root-cause analysis to address specific segments and categories that are actively losing money.

> 💡 **Insight 2: Profitability vs. Revenue**
> The data shows that **high revenue does not guarantee high profitability**. For instance, while some segments consistently perform well, like **Electronics/Enterprise**, others like **Home/Enterprise** have months with significantly negative margins despite generating revenue.

> **Business Implication:**
> To improve the bottom line, focus should shift from simply boosting sales volume to **optimizing the product mix and pricing strategy** for specific customer segments. Identifying and eliminating or re-evaluating underperforming product/segment combinations is crucial.
---
### **3. Fulfillment & Inventory Performance** *(Matrix + Clustered Column Chart)*

> 💡 **Insight 1: Late Orders are a Persistent Problem**
> The **Late Orders %** data shows consistent high percentages across all segments and categories, with many months and product lines reaching over **50%** late delivery rates. Some instances even hit **100%** (e.g., Apr 2024 Distributor/PRD-001).

> **Business Implication:**
> This indicates a major bottleneck in the supply chain, likely due to a lack of available inventory, slow processing times, or logistical failures. This poor performance can lead to **customer dissatisfaction and churn**. Immediate action is needed to identify and fix the root causes of these delays.

> 💡 **Insight 2: Inventory vs. Orders in Progress**
> The **Inventory in Progress** metric shows a cumulative trend, while **Orders in Progress** shows monthly fluctuations. The high value of Inventory in Progress suggests that a significant amount of capital is tied up in unfulfilled orders.

> **Business Implication:**
> The company may be facing a working capital issue. It's critical to investigate why large quantities of inventory are not being shipped. Is it a logistics problem, a lack of personnel to fulfill orders, or simply poor demand forecasting? A healthy operation requires a faster flow from inventory to sales.
