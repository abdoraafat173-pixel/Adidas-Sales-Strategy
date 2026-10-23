# 📊 Adidas Sales Strategy & Analytics Dashboard

An interactive and comprehensive **Power BI** business intelligence solution designed to analyze **Adidas** regional sales performance, optimize category growth, and deliver data-driven strategic recommendations.

---

## 🎨 Project Cover
![Project Cover](Screanshot1_2.jpg)

---

## 📈 Interactive Sales Dashboard
Key features included in the main dashboard:
* **KPI Cards:** Gross Sales ($217.6M), Net Sales ($190.4M), Quantity Sold (6M), and Discount Value ($27.2M).
* **Geographic Breakdown:** Interactive Map displaying regional revenue across Egyptian governorates (Cairo, Alexandria, Ismailia, Luxor, etc.).
* **Category Breakdown:** Performance tracking across Bikes, Clothing, Accessories, and Components.
* **Trend Analysis:** Annual Sankey flow and Monthly sales fluctuation line chart.

![Main Sales Dashboard](Screenshot%202026-10-23%20232307_2.jpg)

---

## 💡 Recommendations & Growth Strategy
Strategic action plan derived from the analytical findings:

* 🔵 **Positive Highlights:**
  * **Core Growth:** Focus inventory and marketing on **Bikes** ($148.1M top revenue generator).
  * **Geographic Reach:** Capitalize on high-density active regions visible on the map.
  * **Peak Revenue Timing:** Launch targeted promotional campaigns during peak sales months.

* 🔴 **Areas for Improvement:**
  * **Low Performers:** Revise sales strategy for weak categories like **Components** ($7.5M).
  * **Discount Control:** Monitor high discount total ($27.2M) to safeguard net margins.
  * **Stock Reallocation & Inventory Optimization:** Shift resources from stagnant items to high-demand regional hubs.
  * **Targeted Marketing:** Bridge sales gaps in low-performing cities.

![Strategic Recommendations](Screenshot%202026-10-23%20232345_2.png)

---

## ⚙️ Data Preparation & ETL Process (Power Query)
* **Data Cleaning & Transformation:** Handled missing values, standardized text casing, and ensured optimal data types across all fields.
* **Profiling & Integrity:** Verified column distribution and zero-error rates across dataset dimensions.

![Power Query ETL](Screenshot%202026-10-23%20145528_2.png)

---

## 📐 Data Modeling (Star Schema)
* Designed an efficient **Star Schema** with `SalesT` as the central Fact table connected via 1-to-Many relationships to Dimension tables (`Product` and `Location`).
* Optimized performance for handling large-scale datasets seamlessly.

![Data Model Schema](Screenshot%202026-10-23%20145947_2.png)

---

## 🧮 Calculated Columns & DAX Measures
Custom DAX measures and columns created to track gross sales, net sales, discount impacts, and aggregate quantities:

![DAX Measures](Screenshot%202026-10-23%20152625_2.png)

---

## 🛠️ Tools & Technologies Used
* **Power BI Desktop** (Dashboard & Visualizations)
* **Power Query** (ETL & Data Transformation)
* **DAX** (Calculated Columns & Measures)
* **GitHub Desktop** (Version Control & Documentation)

---
*Created by **AbdO RaAfat** | Data Analyst & BI Specialist*
