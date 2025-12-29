# Interactive Business Dashboard in Streamlit (Amazon Global Sales)

## 📌 Project Objective
The objective of this project is to build an interactive, web-based business intelligence dashboard using **Streamlit**. The dashboard analyzes Amazon's global sales data to provide stakeholders with real-time insights into revenue trends, profitability, and regional performance, enabling data-driven decision-making.

---

## 📊 Project Overview
This project transforms raw global sales data into an intuitive visual experience. It allows users to slice and dice data across various dimensions such as time, geography, and product categories.

### 1. Key Business Metrics (KPIs)
The dashboard highlights four critical metrics at a glance:
* **Total Sales:** The aggregate revenue generated across all regions.
* **Total Profit:** The net profit after accounting for costs and discounts.
* **Total Quantity:** The volume of items sold.
* **Average Shipping Cost:** A key metric for operational efficiency analysis.

### 2. Interactive Features
* **Sidebar Filters:** Users can filter the entire dashboard by **Date Range**, **Region**, **Market**, and **Product Category**.
* **Dynamic Visuals:** All charts and KPIs update instantly based on the selected filters.
* **Data Exploration:** A dedicated section to view and download the filtered raw data for further offline analysis.

---

## 📈 Visualizations & Insights
The dashboard includes several high-impact visualizations:

* **Sales & Profit Trends:** A time-series line chart showing how revenue and profit fluctuate monthly/yearly, helping identify peak seasons.
* **Regional Performance Map:** A geographic heat map displaying sales volume across different countries and markets (e.g., APAC, EU, LATAM, US).
* **Category Analysis:** A breakdown of sales by Category and Sub-Category (Technology, Furniture, Office Supplies) to identify top-performing product lines.
* **Segment Profitability:** A tree-map or bar chart comparing performance across Consumer, Corporate, and Home Office segments.
* **Shipping & Logistics:** Analysis of shipping modes (First Class, Second Class, etc.) and their impact on delivery times and costs.

---

## 🔍 Strategic Business Recommendations
Based on the dashboard analysis:
1.  **Market Expansion:** Identify regions with high sales but low profit margins to investigate localized operational costs or high discount rates.
2.  **Inventory Management:** Align stock levels with seasonal peaks identified in the time-series analysis.
3.  **Product Focus:** Prioritize marketing spend on high-margin sub-categories within the Technology and Office Supplies sectors.
4.  **Shipping Optimization:** Optimize logistics for regions with disproportionately high average shipping costs.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** Streamlit (for the web interface)
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Plotly Express (for interactive maps and charts), Matplotlib/Seaborn
* **Source Data:** Amazon Global Sales Dataset (CSV/Excel)

---

## 🚀 How to Run the Dashboard
1.  **Clone the Repository:**
    ```bash
    git clone [[https://github.com/your-username/amazon-sales-dashboard.git](https://github.com/taimoordata607-arch/Task-5---Interactive-Business-Dashboard-in-Streamlit/new/main)
    ```
2.  **Install Requirements:**
    ```bash
    pip install streamlit pandas plotly
    ```
3.  **Launch the App:**
    ```bash
    streamlit run app.py
    ```
4.  **View in Browser:** The dashboard will automatically open at `http://localhost:8501`.
