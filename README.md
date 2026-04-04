# Business Insight 360 | Global Enterprise BI Suite
**Advanced Business Intelligence & Decision Support System**

## 📌 Project Overview
Business Insight 360 is a high-performance Power BI ecosystem developed to consolidate fragmented data into a unified "Single Source of Truth." [cite_start]This suite provides 360-degree visibility into organizational health across Finance, Sales, Marketing, Supply Chain, and Executive leadership[cite: 1, 2, 14].

### 🛠️ Core Analytical Engines
I engineered five specialized views, each optimized for a specific business vertical:

* [cite_start]**Finance View:** Generates dynamic P&L statements for any customer, product, or country[cite: 4, 5].
    * **KPIs:** Net Sales ($19.37B), Gross Margin (36.41%), and Net Profit (-20.71%).
* [cite_start]**Sales View:** Evaluates customer performance via Profitability/Growth matrices[cite: 6, 7].
    * **Insight:** Maps Gross Margin % against Net Sales to identify high-value segments.
* [cite_start]**Marketing View:** Analyzes product performance and market share[cite: 8, 9].
    * **Visuals:** Waterfall charts for Net Sales & Gross Margin bifurcation.
* [cite_start]**Supply Chain View:** Tracks operational efficiency and risk[cite: 11].
    * **KPIs:** Forecast Accuracy (91.41%) and Net Error ($1M).
* [cite_start]**Executive View:** A strategic C-suite dashboard consolidating top-level insights from all dimensions[cite: 13, 14].

---

## 🏗️ Technical Architecture
### 1. Data Modeling
* **Schema:** Implemented a robust Star Schema for optimized query performance.
* [cite_start]**Standardization:** All financial values are standardized in **USD (Millions)** for global reporting consistency[cite: 17].

### 2. Advanced DAX (Data Analysis Expressions)
* **Dynamic Benchmarking:** Developed logic to toggle between **Last Year (LY)** and **Target** benchmarks.
* **Risk Profiling:** Engineered "Risk" indicators for Supply Chain (OOS - Out of Stock vs. EI - Excess Inventory).

### 3. Business Logic Implementation
* **P&L Engineering:** Modeled the full flow from **Gross Sales ($38.84B)** down to **Net Profit** post-operational expenses.
* **Market Intelligence:** Segmented performance by region (APAC, NA, EU, LATAM).

---

## 📈 Strategic Business Impact
By leveraging this suite, stakeholders can move from reactive reporting to proactive strategy:
* **Optimization:** Identified that while APAC leads in Net Sales ($10.34B), the Net Profit margin reflects significant optimization opportunities.
* **Reliability:** High Forecast Accuracy (91.41%) minimizes capital tied up in excess inventory.

---

## 🔧 Tech Stack
* **Tool:** Power BI Desktop
* **Data Prep:** Power Query (ETL)
* **Modeling:** DAX & Relational Schema
* [cite_start]**Documentation:** Saturday, April 04, 2026 [cite: 15]

---

## 📂 Repository Structure
* `Dashboard_Files/`: Contains the `https://app.powerbi.com/view?r=eyJrIjoiZTQzNzc0NmItMjFkYS00NmNkLWFmZGItM2U4MmYxN2U2YmJlIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9` source file.



---
*Developed as a Data Analyst to bridge the gap between raw data and executive decision-making.*
