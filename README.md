# 📊 Business Performance Analytics
This repository contains a comprehensive Power BI dashboard for end-to-end business performance analysis. It provides actionable insights into sales, profitability, and operational efficiency by tracking key metrics across multiple departments.

## 🛒 Tools Used
- Power BI Desktop (Data visualization, dashboard design, and data modeling)
- Power Query (Data cleaning, transformation)
- DAX (All custom measures and KPIs)
- Excel (Initial data structure design and preparing the fictional dataset)
- GitHub (Version control and project documentation)

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
- **Total Revenue:** ₺1.612.450.363 
- **Total Cost:** ₺1.178.251.569  
- **Total Profit:** ₺434.198.794 
- **Profit Margin:** 26.93%  
- **Total Orders:** 1,000
  
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
> High revenue doesn’t necessarily translate into high profitability. While CUST-0202 leads in revenue, its lower profit margin (21.79%) reflects higher operational costs per order. In contrast, CUST-0191 achieves a 34.10% margin on fewer orders, demonstrating greater efficiency and a more profitable customer profile.

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
> - **1. High Revenue, Low Margin (December 2024):** This month generated high revenue but had a low profit margin. This may indicate a period of aggressive, high-volume sales driven by promotions or end-of-year discounts, which increased top-line revenue but eroded profitability.
> - **2. Low Revenue, High Margin (April 2025):** In contrast, April 2025 achieved one of the highest profit margins despite having a low revenue month. This suggests that sales during this period were highly strategic, likely focusing on high-margin items or a significant reduction in operational costs.
> - **3. The Revenue-Profitability Gap (June vs. July 2025):** The most critical insight is the dramatic gap between June 2025 and July 2025; despite nearly identical revenues, their profit margins have a massive 18% difference. This highlights a significant inconsistency in profitability drivers.

## 📌 **Business Implication:**
> True business health is not measured by revenue alone. These trends show that a robust strategy must prioritize **margin optimization** and **understanding the underlying factors** behind monthly volatility to ensure consistent, sustainable growth.

---
## 📃 Page 2: Profitability & Operations Analysis

## 🔍 Key Features
- **Revenue & Order Trends** → Analyze **month-over-month (MoM)** changes in Revenue and Total Orders to understand sales performance and demand fluctuations.
- **Segment & Category Profitability** → Break down profit margins by **customer segment** and **product category**, revealing which combinations are most profitable.
- **Inventory & Workload Analysis** → Assess **Orders in Progress** and **Inventory in Progress** to gauge operational load and potential bottlenecks.
  
---
## 📈 Insights & Trend Storytelling

### **1. Overall Performance Snapshot (MoM)**
> 💡 **Insight:**
> The Marmara region demonstrates **severe profit margin instability** from **late 2024 through 2025**, indicating potential challenges in **demand planning, pricing strategy, and cost management**.
> From **Nov 2024** to **Feb 2025**, revenue remained relatively stable, but profit margins collapsed:  
> - **Nov 2024 → Feb 2025**: Margins dropped from **34.73%** to **10.82%** (**-68.9% MoM decline**).  
> - Despite steady revenue, operational efficiency weakened, suggesting **rising production costs** or **aggressive discounting** to drive sales.
>
> - **Mar 2025** saw a sharp rebound to **26.12%**, but by **May 2025**, margins plunged to **4.09%** (**-84.3% MoM**).  
> - Indicates **short-term corrective tactics** rather than sustainable profitability — possibly **temporary promotions** or **bulk sales**.
>
> - **Jun 2025**: Margins peaked at **44.55%**, marking the region’s highest profitability since early 2024.  
> - **Aug 2025**: Margins dropped to **-15.32%**, entering **negative territory** despite moderate revenue declines.  
> - Suggests **cost overruns**, **excess inventory clearances**, or **pricing misalignments**.

## 📌 **Business Implication:**
> The Marmara region’s extreme **profit margin volatility** highlights an urgent need for:  
> - Better **demand forecasting** to align production with market realities.  
> - Stronger **cost-control mechanisms** to protect margins during revenue fluctuations.  
> - More **sustainable pricing strategies** to avoid short-term profitability swings.
>
Stabilizing profitability will require a **data-driven approach** combining **forecast accuracy**, **cost optimization**, and **strategic pricing alignment**.

---
### **2. Profitability by Segment & Category** *(Clustered Column Chart)*

> 💡 **Insight:**
> The data reveals **significant instability in profit margins** across multiple segments, especially within **Electronics SMB and Home Distributor**.
> 
> ❗ **Potantial Causes:**
> - **Sudden pricing adjustments** and **discounting strategies** appear to have triggered **extreme short-term fluctuations.**
> - **Possible inventory misalignments** — either excess stock leading to markdowns or shortages driving up prices.
> - Demand volatility in certain customer segments, particularly **SMBs**, may indicate inconsistent forecasting accuracy.
> - **Implications of Instability:**
> - Unstable profit margins can **distort revenue predictability** and impact **cash flow planning.**
> - Sudden margin drops — such as Electronics SMB (-21.0%) in May 2025 — could **reflect operational inefficiencies** or **reactive pricing policies.**
> - High spikes, like the 69.9% Electronics Distributor margin in Jun 2025, may suggest short-term wins but also **carry risks** if they are not sustainable.

## 📌 **Business Implication:**
> - The significant fluctuations in profit margins indicate **potential pricing inefficiencies**, **demand forecasting gaps**, and **inventory misalignments.**
Such volatility can **undermine revenue predictability** and **cash flow stability,** making it harder to plan operations effectively.
A more integrated Sales & Operations Planning (S&OP) approach, **combined with tighter pricing control** and **improved cost tracking,** is essential to ensure **sustainable profitability.**

---
### **3. Segment-wise Total Profit** **(Waterfall Chart)**

> 💡 **Insight:**  
> - **Backlog Exposure:** Months with high monetary value of Inventory in Progress, such as March 2024 (₺16M) and February 2025 (₺16M), indicate **significant capital tied up in unfulfilled orders**.
> - **Operational Risk:** Periods where the monetary value remains high despite fewer orders, e.g., March 2025 (6 orders, ₺13M), suggest **delays in fulfillment or large-value orders pending**, which could impact customer satisfaction and cash flow.

## 📌 **Business Implication:**  
> Monitoring both order count and monetary value of pending orders is essential for **cash flow management, prioritization, and operational planning**.  
> - **Recommendation:** Introduce **backlog prioritization rules** based on order value and urgency, and **align production/shipping capacity** with monetary exposure to reduce risk.

---
## 🧠 Analytical Approach
This dashboard uses a **layered, data-driven approach**:  
- **KPI Overview:** Tracks Total Revenue, Profit, Orders, and Profit Margin % at both overall and segment levels.  
- **Trend & Volatility Analysis:** Monitors month-over-month changes to detect fluctuations in revenue, profit, and workload.  
- **Customer & Segment Drill-Down:** Examines profitability by segment, category, and customer to identify high-margin opportunities and operational risks.  
- **Backlog & Orders Monitoring:** Assesses pending orders’ count and monetary value to manage cash flow and fulfillment risk.  
- **Actionable Insights:** Focuses on understanding causes behind fluctuations and provides prescriptive recommendations for pricing, inventory, and operational efficiency.  
> ⚡ **Goal:** Help decision-makers understand performance patterns, identify risks, and guide strategic actions for sustainable growth.

---
## 👤 About the Creator
This dashboard was built as part of my journey to master advanced Power BI techniques and DAX calculations. While working on it, I explored how to make data tell a story and highlight trends dynamically.

- **VAR & RETURN:** I learned how to store intermediate values and output final results cleanly, making complex calculations more readable and manageable.  
- **ISBLANK & BLANK:** Handling empty values became essential to avoid misleading results and keep visuals accurate.  
- **FORMAT & ABS:** I discovered how to present numbers clearly, including absolute values, so trends and magnitudes are immediately understandable.  
- **ALLSELECTED:** This function taught me how to respect user selections while still calculating totals or cumulative metrics across the dashboard.  

Using these techniques, I created dynamic indicators—like upward and downward arrows for month-over-month revenue or order changes—that make trends instantly visible. This project not only sharpened my technical skills but also reinforced the importance of **turning raw data into actionable insights**.


