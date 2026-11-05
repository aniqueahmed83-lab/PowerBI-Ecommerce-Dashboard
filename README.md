## 📊 Project Overview
This project was developed from scratch to simulate real-world retail analytics reporting. It transforms raw sales and customer data into actionable insights, helping stakeholders track key performance indicators (KPIs) like total revenue, order volumes, and average order value.

---

## 🛠️ Tech Stack & Tools
* **Power BI Desktop:** Data modeling, DAX measures, and dashboard visualization.
* **Power Query:** Data cleaning and transformation.
* **GitHub:** Version control and portfolio hosting.

---

## 📐 Data Architecture & Schema
* **Star Schema Design:** Built using a 1-to-Many relationship model connecting `Fact_Sales` and `Dim_Customer` via the `customer_id` key.
* **Measures Table:** Maintained a dedicated `_Measures` folder/table to keep all DAX calculations organized and industry-compliant.

---

## 💡 Key DAX Measures Developed
* **Total Sales:** Uses `SUMX` to calculate total revenue across transactions.
* **Total Orders:** Utilizes count logic to measure order frequency.
* **Average Order Value (AOV):** Implemented using `DIVIDE` to safely compute average revenue per order.

---

## 📈 Dashboard Features & Visuals
1. **High-Level KPI Cards:** Instant visibility into `Total Orders`, `Total Sales`, and `Average Order Value`.
2. **Region-Wise Performance:** Bar chart breaking down sales distribution across regions (Dammam, Khobar, Riyadh, Jeddah).
3. **Category Breakdown:** Donut chart illustrating sales proportions by product categories.
4. **Sales Trend Analysis:** Line chart tracking revenue movement over time based on `order_date`.
5. **Interactive Filtering:** Region slicers for dynamic cross-filtering across all visual elements.

---

## 🚀 How to View
1. Download the `.pbix` file from this repository.
2. Open it using **Power BI Desktop** to explore the data model, DAX formulas, and interactive filters.
