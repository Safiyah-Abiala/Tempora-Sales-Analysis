# ⏳ Tempora Sales Analysis Dashboard (Power BI)

## 📋 Project Overview
The **Tempora Sales Analysis** project is a multi-page interactive Power BI dashboard designed to evaluate business performance across sales execution, product categories, and marketing customer acquisition strategies. 

By converting transactional data into granular operational metrics, this dashboard equips stakeholders with critical insights regarding territory profitability, promotional discount efficiency, and customer retention.

---

## 📊 Dashboard Pages & Deep Dives

### 🏢 Main Overview Dashboard
![Overview Dashboard](images/Overview%20Dashboard.png)

* **High-Level Snapshot:** This central hub tracks core company KPIs at a glance, showing **\$70.33M in Total Sales**, **\$6.49M in Total Profit**, and a **9.22% Profit Margin** across all divisions. It serves as the primary navigation landing page connecting the specialized reports.

---

### 1️⃣ Sales Report
| Main Dashboard | Slide-out Insights Modal |
| :---: | :---: |
| ![Sales Report](images/Sales%20report.png) | ![Sales Insight](images/Sales%20insight.png) |

* **Core Metrics:** Generated **\$70.33M in Total Sales**, driving **\$6.49M in Total Profit** at an overall **9.22% Profit Margin**.
* **Sales Representative Execution:** **David** emerged as the top contributor, producing **\$16.4M** in sales with maximum profit conversion, while **Charlie** tracked at the lower bound with **\$11.55M**.
* **Regional Trends:** The **East region** consistently anchored strongest baseline performance across reps, whereas the **South and West regions** showed signs of market saturation or lower penetration.
* **Seasonality:** Sales performance spiked aggressively in **January** followed by secondary peaks in **August and October**, signaling clear seasonal demand triggers.

---

### 2️⃣ Product Performance Report
| Main Dashboard | Slide-out Insights Modal |
| :---: | :---: |
| ![Product Report](images/Product%20report.png) | ![Product Insight](images/Product%20insight.png) |

* **Volume Drivers:** **Clothing** is the core flagship category, pulling in **\$19.29M** in revenue and leading the category mix at **27.42%** of total volume.
* **Profit Optimization:** While **Furniture** ranks second in overall sales (\$18.33M), it delivers the **highest absolute profit margins (\$1.78M)**, showcasing phenomenal pricing power and structural efficiency.
* **Channel Behavior:** Customer preferences split clearly by segment: **Clothing** thrives heavily in **Retail environments**, while **Furniture and Electronics** capture larger operational volume via **Online platforms**.

---

### 3️⃣ Marketing & Customer Acquisition Report
| Main Dashboard | Slide-out Insights Modal |
| :---: | :---: |
| ![Marketing Report](images/Marketing%20report.png) | ![Marketing Insight](images/Marketing%20insight.png) |

* **Acquisition Mix:** Marketing efforts successfully acquired **504 New Customers** vs. **496 Returning Customers**, maintaining a stable baseline **Retention Rate of 49.60%**.
* **Territory Winning:** The **North Region** proved to be the most fertile ground for business development, capturing the highest volume of new customer acquisitions (**145 new accounts**).
* **Transaction Infrastructure:** Payment channels are exceptionally well-balanced, led by **Credit Cards (345 orders)** and **Bank Transfers (342 orders)**, indicating a highly modern digital checkout pattern.

---

## 🛠️ Data Architecture & Cleaning (ETL)
The dataset was processed in Power Query to build a highly optimized star schema layout:
* **Data Transformation:** Structured messy row items into clean, explicitly typed columns covering margins, customer types, and fulfillment channels.
* **Granular Relationships:** Created composite lookup markers like `Region_and_Sales_Rep` to isolate specific field team performance dynamics without inflating base table architecture.
* **Discount Standardization:** Isolated baseline unit costs against scaled sales items to accurately track the financial drag of promotional discount allocations (\$10.64M total).

---

## 💡 Strategic Recommendations
1.  **Re-evaluate Discount Policies:** The analysis shows a steep line of discount impact (\$10.64M total discount vs. \$6.49M total profit). Promotional campaigns should be tightened to protect overall margins, particularly in lower-yield categories like **Electronics**.
2.  **Scale the Furniture Playbook:** Because **Furniture** has the highest profit margin conversion despite lower sales counts than Clothing, tactical resources should be directed toward expanding this premium catalog line.
3.  **Targeted Retention in the South:** Address weaker customer retention profiles in the South region by replicating the acquisition frameworks that made the **North** market highly successful.

---

## 🧠 Technical Skills Demonstrated
* **Data Modeling:** Advanced data layout principles including custom key generation and normalized table relationships.
* **DAX Architecture:** Formulated foundational KPIs: Average Order Value (AOV), Total Profit, Dynamic Retention Rates %, and Category Margins.
* **User Interface (UI) Design:** Implemented a modern custom color palette, consistent vertical navigation layouts, and dynamic pop-up modal filters for insights.

---

## 📂 Repository Content
* `Tempora Sales Analysis.pbix` - Complete Power BI dashboard file.
* `Tempora sales data.csv` - Transformed database snapshot.
* `/images` - Dashboard page visual assets.

---

## 👩‍💻 Author
**Ms_Safiyah** *Data Analyst | Bridging Business Operations with Intelligence*
