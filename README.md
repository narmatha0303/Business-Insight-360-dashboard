# AtliQ Hardware Business Insight 360 

## 📌 Project Overview
Business Insight 360 is a high-performance Power BI ecosystem developed to consolidate fragmented data into a unified "Single Source of Truth." This suite provides 360-degree visibility into organizational health across Finance, Sales, Marketing, Supply Chain, and Executive leadership.

### 🛠️ Core Analytical Engines
I engineered five specialized views, each optimized for a specific business vertical:

*## 🔍 Module-Specific Insights & Strategic Actions

### 1. Finance View: Global Profitability Analysis
* **Insight:** Captured a total **Net Sales of $19.37B** with a **Gross Margin of 36.41%**.
* **Observation:** While Gross Sales reached $38.84B, post-invoice deductions and COGS ($12.31B) significantly impact the bottom line.
* **Action:** Implemented dynamic P&L statements to identify specific product/country aggregations where "Other Costs" or "Freight Costs" are eroding the Gross Margin %.

### 2. Sales View: Customer & Product Performance
* **Insight:** Utilized a **Profitability/Growth Matrix** to segment the customer base
* **Observation:** Identified high-volume products like **AQ Smash 1 ($744M NS)** maintaining healthy margins, while others show a decline in GM% variance.
* **Action:** Established a performance toggle to compare current performance against **Last Year (LY)** and **Targets**, allowing sales teams to pivot strategies for underperforming accounts.

### 3. Marketing View: Market Share & Bifurcation
* **Insight:** Analyzed the **Net Sales & Gross Margin Bifurcation** to visualize the flow from revenue to profit.
* **Observation:** The **APAC region** dominates with **$10.34B in Net Sales**, but the **Net Profit (-21.22%)** indicates high operational expenses ($11.06B).
* **Action:** Recommended a review of operational spend in high-revenue regions like APAC and NA to bring Net Profit into a positive trajectory.

### 4. Supply Chain View: Reliability & Risk Mitigation
* **Insight:** Achieved a high **Forecast Accuracy of 91.41%**, significantly reducing the Net Error to $1M.
* **Observation:** Identified specific customers (e.g., Amazon, Atliq Exclusive) with "EI" (Excess Inventory) or "OOS" (Out of Stock) risk profiles.
* **Action:** Developed an "Absolute Error" trend tracker to help the logistics team adjust safety stock levels and minimize capital tied up in excess inventory.

### 5. Executive View: C-Suite Decision Support
* **Insight:** Consolidated high-level KPIs including **Net Profit % (-20.71%)** and **Revenue Contribution** by channel.
* **Observation:** The "Retailer" channel remains the primary driver of revenue at **69.7%**, while "Direct" and "Distributor" channels offer room for growth.
* **Action:** Provided a unified view of sub-region performance (ANZ, NA, LATAM, etc.) to allow executives to allocate resources based on regional risk and market share.
---

## 🏗️ Technical Architecture
### 1. Data Modeling
* **Schema:** Implemented a robust Star Schema for optimized query performance.
* **Standardization:** All financial values are standardized in **USD (Millions)** for global reporting consistency.

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
* **Modeling:** DAX & Star Schema
* **Documentation:** Saturday, April 04, 2026 

---

## 📂 Repository Structure
* `Dashboard_Files/`: https://app.powerbi.com/view?r=eyJrIjoiOTA3NjJhMTctYWUxYS00ZjM2LTljZjktNTRjYWNmNDJlMjllIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9


