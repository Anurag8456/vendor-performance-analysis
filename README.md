# 📊 Vendor Performance Analysis — End-to-End Data Analytics Project

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org)
[![SQL](https://img.shields.io/badge/SQL-SQLite-lightgrey)](https://www.sqlite.org)
[![Power BI](https://img.shields.io/badge/Power_BI-Dashboard-yellow)](https://powerbi.microsoft.com/)

An end-to-end data analytics pipeline analyzing vendor performance for an electronics retail business. This project demonstrates the full lifecycle of a data analyst's workflow: from raw data generation to statistical validation and executive visualization.

## 🏢 Business Context
In the competitive electronics retail sector (Samsung, LG, Sony, etc.), profitability is often leaked through:
* **Inefficient Pricing:** Misalignment between margins and sales volume.
* **Inventory Stagnation:** Poor turnover rates tying up working capital.
* **Vendor Concentration:** High-risk over-dependence on a limited supplier base.

This analysis evaluates **10 vendors** and **15 brands** across **FY2024** to optimize procurement and sales strategies.

---

## 🛠️ Tech Stack
* **Languages:** Python (Pandas, Matplotlib, Seaborn, SciPy), SQL
* **Database:** SQLite
* **Tools:** Jupyter Notebook, Anaconda, Power BI Desktop
* **Statistics:** Hypothesis Testing (T-Tests), Confidence Intervals

---

## 📂 Project Pipeline
*To replicate the analysis, run the notebooks in the following order:*

| Order | Notebook | Purpose |
| :--- | :--- | :--- |
| 1️⃣ | `01_generate_data` | Synthesizes realistic retail datasets (Sales/Purchases). |
| 2️⃣ | `02_sql_and_database` | Database schema creation and core SQL querying. |
| 3️⃣ | `03_etl_pipeline` | Optimized SQL joins to build the `vendor_sales_summary`. |
| 4️⃣ | `04_eda_and_visualization` | Exploratory analysis answering 5 core research questions. |
| 5️⃣ | `05_statistics` | Statistical rigor via SciPy (Hypothesis testing). |
| 6️⃣ | `06_final_summary` | Executive conclusions and project sign-off. |

---

## 📈 Key Insights & Findings

| Research Question | Key Finding |
| :--- | :--- |
| **Promotion Strategy** | Identified high-margin (>80%) but low-volume brands for marketing intervention. |
| **Market Leaders** | **Samsung India** and **LG Electronics** dominate total sales volume. |
| **Risk Profile** | High procurement concentration; Top 3 vendors control the majority of spend. |
| **Economy of Scale** | Confirmed: Bulk purchase orders significantly reduce per-unit costs. |
| **Efficiency** | Flagged vendors with < 1.0 inventory turnover for contract review. |
| **Statistical Significance** | T-test confirmed margin differences are statistically significant ($p < 0.05$). |

---

## 🚀 How to Run
1.  **Environment:** Install [Anaconda](https://www.anaconda.com/).
2.  **Clone:** `git clone https://github.com/your-username/vendor-performance-analysis.git`
3.  **Launch:** Open Anaconda Prompt, navigate to the folder, and type `jupyter notebook`.
4.  **Execute:** Run notebooks `01` through `06` sequentially.
5.  **Dashboard:** Open the `.pbix` file in Power BI Desktop and link to `outputs/vendor_sales_summary.csv`.

---

## 👤 Author
**Anurag**
📍 Ghaziabad, Uttar Pradesh, India

---
*Developed as a showcase of data engineering, statistical analysis, and business intelligence.*
