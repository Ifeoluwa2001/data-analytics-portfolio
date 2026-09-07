# Business Intelligence & Data Analytics Portfolio

Welcome to my data analytics portfolio repository! This repository showcases end-to-end data engineering, star-schema relational modeling, complex DAX metrics, exploratory statistics, and multi-page executive dashboards built using **Power BI** and **Microsoft Excel**.

---

## 📁 Portfolio Projects Directory

| # | Project Name | Primary Tool | Key Architecture & Focus Areas | Folder Link |
| :-: | :--- | :--- | :--- | :--- |
| **1** | **End-to-End Logistics Operations & Fleet Performance** | **Power BI** | Multi-Page Enterprise BI, Star Schema (10+ Tables), Operational Bottlenecks, Cost-to-Revenue Efficiency | [View Folder](./PowerBI-Projects/Project-1-Logistics-Operations) |
| **2** | **Retail Sales Performance & Customer Demographics** | **Power BI** | Star Schema Modeling, Power Query Transformation, DAX Metrics, Demographics Breakdown | [View Folder](./PowerBI-Projects/Project-2-Retail-Sales) |
| **3** | **Nigerian Regional Sales & Profitability Analysis** | **Microsoft Excel** | Regional Profit Metrics, Dynamic Slicers, Anomaly Tracking, Dark Executive Dashboard | [View Folder](./Excel-Projects/Project-3-Regional-Sales) |
| **4** | **E-Commerce Sales Performance & Operations** | **Microsoft Excel** | Descriptive Statistics, Dynamic Slicers, KPI Cards, Order Status Diagnostics | [View Folder](./Excel-Projects/Project-4-Sales-Dashboard) |
| **5** | **E-Commerce Sales Data Cleaning & Standardization** | **Microsoft Excel / Power Query** | Data Quality Auditing, Text Normalization, ISO Date Standardization, Deduplication | [View Folder](./Excel-Projects/Project-5-Data-Cleaning) |

---

## 📌 Featured Project Highlights

### 1. End-to-End Logistics Operations & Performance Analysis System
* **Directory:** [`/PowerBI-Projects/Project-1-Logistics-Operations`](./PowerBI-Projects/Project-1-Logistics-Operations)
* **Tools:** Power BI Desktop, Power Query, DAX (Data Analysis Expressions)
* **Architecture:** Enterprise star schema connecting 10+ relational entities (`Fact_Trips`, `Fact_FuelPurchases`, `Fact_SafetyIncidents`, `Dim_Drivers`, `Dim_Trucks`, `Dim_Trailers`, `Dim_Routes`, `Dim_Customers`, `Dim_Facilities`, `DateTable`).
* **Dashboard Structure:**
  * **Page 1: Executive Overview:** Macro financial indicators, route profitability, and operational delivery reliability.
  * **Page 2: Fleet Utilization & Performance:** Asset utilization metrics, fuel economy decay, and manufacturer maintenance cost profiles.
  * **Page 3: Driver & Safety Logistics:** Safety incident cost tracking, claim exposure analysis, and driver yield metrics.
  * **Page 4: Route Profitability:** Lane cost-to-revenue ratios, operational expense breakdowns, and bidirectional route yield paradoxes.
  * **Page 5: Fuel Management:** Fleet idle time culprits, seasonal MPG variances, and fuel cost per mile fluctuations.
* **Key Financial & Operational Metrics:**
  * **Total Revenue:** **$298.62M** across **85K total trips** and **200 customers**.
  * **Total Net Profit:** **$194.64M** (**65.18% Profit Margin**).
  * **Fleet Maintenance Expenditure:** **$5.73M** across **120 active trucks** (Capacity utilization: **83.04%**).
  * **Safety Incident Exposure:** **$3.0M** in total claim costs across **170 incidents** (Average cost: $15.6K per incident).
  * **Fuel Spending:** **$95.59M** spent on **18.95M gallons** (Average fleet fuel economy: **6.45 MPG**).
* **Core Business & Operational Insights:**
  * **Delivery Bottleneck:** Despite high profit margins (65.18%), the fleet faces severe delivery risk with an **On-Time Delivery Rate of only 55.67%** (75.73K delayed trips vs. 95.1K on-time trips).
  * **Top Transport Lane:** **Charlotte to Portland** is the most lucrative lane, generating **$3.9M in profit**.
  * **Client Risk Concentration:** **First Group** represents the single largest account (**$10.4M in revenue**), highlighting the need for portfolio diversification.
  * **Asset Maintenance Profiles:** **Volvo** serves as the top-grossing truck manufacturer (generating >$60M in revenue) with minimal relative maintenance cost, whereas **Freightliner** ($1.12M / 19.47%) and **Peterbilt** ($1.10M / 19.13%) account for the largest share of maintenance spending.
  * **Idle Time Culprits:** **Volvo** vehicles contribute highest to total fleet idle time (**20.65% / 121.25K hours**).
  * **Safety Liabilities:** Equipment damage is the leading safety cost driver (**$741K / 27.93%**), peaking seasonally in May ($379K) and September ($324K).

---

### 2. Retail Sales Performance & Customer Demographics Dashboard
* **Directory:** [`/PowerBI-Projects/Project-2-Retail-Sales`](./PowerBI-Projects/Project-2-Retail-Sales)
* **Tools:** Power BI Desktop, Power Query, DAX
* **Architecture:** Star schema model connecting `SALES` fact table to `CUSTOMERS` and `PRODUCTS` dimensions.
* **Key Executive Metrics:**
  * **Total Revenue:** **$3.11M** ($3,106.35K) | **Total Profit:** **$932.08K** | **Total Cost:** **$2.17M**.
* **Core Insights:**
  * **Apple** led brand profitability at **$196.89K**, followed by Lenovo ($160.14K).
  * Customers in the **Medium** income tier generated **37.23% ($347K)** of total profit.
  * **White** color finishes drove maximum sales volume (6.12K units).

---

### 3. Nigerian Regional Sales Performance & Profitability Dashboard
* **Directory:** [`/Excel-Projects/Project-3-Regional-Sales`](./Excel-Projects/Project-3-Regional-Sales)
* **Tools:** Microsoft Excel (Pivot Tables, Dynamic Slicers, Dark Executive Layout)
* **Objective:** Track 2,098 sales orders across major commercial hubs (Lagos, Kano, Port Harcourt, Abuja).
* **Key Metrics:** Revenue: **₦2.33B** | COGS: **₦1.86B** | Profit: **₦465.67M**.
* **Core Insights:**
  * **Laptop A13** generated **₦105.3M** in profit—outperforming the next two products combined.
  * Identified a severe customer order drop in **May** (falling to 18 orders from 536 in April).

---

### 4. E-Commerce Interactive Sales & Operational Dashboard
* **Directory:** [`/Excel-Projects/Project-4-Sales-Dashboard`](./Excel-Projects/Project-4-Sales-Dashboard)
* **Tools:** Microsoft Excel (Pivot Tables, Dynamic Slicers, Descriptive Statistics)
* **Objective:** Analyze 1,200 orders totaling **$1.26M** in revenue across product categories and channels.
* **Core Insights:**
  * Cancelled (250) and Returned (247) orders combined (497 total) outnumbered Delivered orders (231), highlighting fulfillment issues.

---

### 5. E-Commerce Sales Data Cleaning & Standardization
* **Directory:** [`/Excel-Projects/Project-5-Data-Cleaning`](./Excel-Projects/Project-5-Data-Cleaning)
* **Tools:** Microsoft Excel, Power Query
* **Objective:** Transform a raw transaction dataset into a production-ready model with 0% error rates.
* **Key Operations:** Imputed 309 missing promo codes to `"NO COUPON"`, trimmed string whitespace, and formatted dates to ISO standards.

---

## 🛠️ Technical Skill Matrix

* **Business Intelligence & Analytics:** Power BI Desktop, Multi-Page Executive Reports, Relational Star Schema Modeling, DAX Measures, Power Query / M-Code Data Transformations.
* **Data Analysis & Statistics:** Advanced Microsoft Excel, Pivot Tables & Pivot Charts, Dynamic Slicers, Descriptive Statistics, Outlier & Anomaly Detection.
* **Data Engineering & Preparation:** Data Auditing, Deduplication, Imputation, Text Normalization, Type Conversion.
