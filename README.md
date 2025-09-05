# 📊 Business Performance Analytics
This repository contains a comprehensive Power BI dashboard for end-to-end business performance analysis. It provides actionable insights into sales, profitability, and operational efficiency by tracking key metrics across multiple departments.

##  Page 1: Performance Overview
## 🔍 Key Features  
- **Comprehensive KPI Tracking** → Monitor **Total Revenue**, **Total Cost**, **Total Profit**, **Profit Margin %**, and **Total Orders** at a glance.  
- **Customer Segmentation Insights** → Evaluate **Enterprise**, **SMB**, and **Distributor** contributions to total revenue dynamically.  
- **Customer-Level Profitability Analysis** → Compare customers’ **revenue**, **profit margins**, **average order value**, and **order frequency** to identify growth opportunities.  
- **Revenue & Profitability Trends** → Visualize **month-by-month changes** in revenue and profit margins to detect underlying business patterns.
---
## 📈 Initial Insights & Key Takeaways
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
## 📌 **Business Implication:**
> The overall 26.93% profit margin is a positive sign, but it's not the full story. True strategic growth requires moving beyond this high-level view. The business must **analyze profitability by segment and customer** to identify where profit is actually being generated. This approach enables targeted strategies that focus on **margin optimization**, rather than just general revenue expansion.
---
### **2. Customer Segment Contribution** *(Pie Chart)*
- **Enterprise:** **35.52%**
- **SMB:** **33.81%**
- **Distributor:** **30.67%**
> 💡 **Insight:**
> While the overall revenue distribution across segments appears balanced, a deeper look reveals significant and volatile monthly fluctuations within each segment's performance. This lack of consistency poses a strategic challenge for supply chain management.
> - **Unpredictable Performance:** All segments show major month-over-month swings. For example, the **SMB** segment's revenue spiked from ₺22.9M in December 2024 to a record high of ₺51.4M in January 2025. Such drastic changes can make future demand forecasting and resource planning highly difficult.
> - **Supply Chain Implications:** These sharp fluctuations suggest potential misalignments between sales and operational planning (S&OP). Revenue spikes could lead to inventory shortages or operational bottlenecks, while sudden drops might result in idle capacity.
## 📌 **Business Implication:**
> It is critical to move beyond the high-level revenue balance and **investigate the root causes** of this monthly volatility. Understanding the specific factors driving these dramatic swings is essential for **creating a more resilient and predictable supply chain**. The focus should be on stabilizing month-to-month performance to optimize operational efficiency and minimize risk.
---  
### **3. Customer-Level Profitability Analysis** *(Matrix Table)*

| Customer | Total Revenue | AOV | Profit Margin % | Total Orders |
| :--- | :--- | :--- | :--- | :--- |
| **CUST-0202** | ₺22.26M | ₺3.18M | **21.79%** | 7 |
| **CUST-0191** | ₺14.90M | ₺2.98M | **34.10%** | 5 |

> 💡 **Insight:**
> This table challenges the assumption that high revenue equals high profitability. While **CUST-0202** is the highest revenue generator, its profit margin of **21.79%** is significantly lower than that of **CUST-0191**, which achieves **34.10%** on a smaller sales volume.
> **CUST-0202's** lower margin, despite having a high AOV and more frequent orders, is a clear indicator that its high volume may be tied to **increased operational costs** associated with order fulfillment, such as **packaging, shipping, and handling**. This suggests that as sales volume rises for this customer, the operational costs erode the profit margin.
> Conversely, **CUST-0191's** high margin, on fewer orders, highlights its efficiency and the potential for a more profitable customer profile. This customer may require fewer resources or purchase a more lucrative mix of products.
## 📌 **Business Implication:**
> True business health is measured by **profitable growth, not just revenue expansion**. This analysis highlights the need to shift from a broad, volume-based strategy to a more granular approach that focuses on **margin optimization at the customer level**. By identifying and replicating the success factors of high-margin customers like CUST-0191, the business can enhance overall profitability without sacrificing growth.
---
### **4. Revenue vs. Profitability Trends** *(Line Chart/Table)*

| Month | Total Revenue | Profit Margin % |
| :--- | :--- | :--- |
| **Dec 2024** | ₺103.27M | **24.74%** |
| **Apr 2025** | ₺54.46M | **36.18%** |
| **Jun 2025** | ₺79.86M | **40.79%** |
| **Jul 2025** | ₺79.01M | **22.63%** |

> 💡 **Insight:**
> This table demonstrates the complex and often unpredictable relationship between revenue and profitability. A look at recent data reveals three critical scenarios:
> **1. High Revenue, Low Margin (December 2024):** This month generated high revenue but had a low profit margin. This may indicate a period of aggressive, high-volume sales driven by promotions or end-of-year discounts, which increased top-line revenue but eroded profitability.
> **2. Low Revenue, High Margin (April 2025):** In contrast, April 2025 achieved one of the highest profit margins despite having a low revenue month. This suggests that sales during this period were highly strategic, likely focusing on high-margin items or a significant reduction in operational costs.
> **3. The Revenue-Profitability Gap (June vs. July 2025):** The most critical insight is the dramatic gap between June 2025 and July 2025; despite nearly identical revenues, their profit margins have a massive 18% difference. This highlights a significant inconsistency in profitability drivers.
## 📌 **Business Implication:**
> True business health is not measured by revenue alone. These trends show that a robust strategy must prioritize **margin optimization** and **understanding the underlying factors** behind monthly volatility to ensure consistent, sustainable growth.

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
> 💡 **Insight:**
> This dashboard highlights significant complexities in revenue and profitability across regions. The data proves that a one-size-fits-all strategy is not effective, and each region has its own unique market dynamics and operational challenges.
> - **Aegean's Exceptional Profitability Spike (April 2025):** The Aegean region showed remarkable performance in April, with revenue increasing by **153.9%** from the previous month, while its profit margin surged by **98.4%**. This suggests that revenue growth was not just from volume but was coupled with successful strategic sales of high-margin products or exceptional cost management.
> - **Central Anatolia's Inconsistent Profitability:** Central Anatolia demonstrated resilience in April 2025 by increasing its profit margin despite a drop in revenue. However, a contrasting trend in **July 2025** shows a revenue increase of 21.1% accompanied by a significant **50.1% drop** in profit margin. This highlights that revenue growth does not always correlate with profitability and can be achieved at the cost of margin erosion.
> - **The Dramatic Profitability Gap (August 2025):** A critical insight emerges from comparing the Aegean and Mediterranean regions in August 2025. Despite both regions experiencing a sharp revenue drop, the Aegean’s profit margin **increased by 29.8% to 67.88%**, while the Mediterranean’s plummeted by 4.9% to a mere 5.71%. This massive disparity underscores a fundamental difference in operational efficiency and cost management between the two regions.
## 📌 **Business Implication:**
> These regional performance disparities call for a shift from broad strategies to localized, data-driven approaches. The business must analyze the specific drivers of success in high-margin regions like the Aegean to identify best practices that can be applied elsewhere, while simultaneously investigating the operational inefficiencies in underperforming regions to stabilize their profitability.
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
