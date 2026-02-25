# Vendor Performance Analysis — End-to-End Data Analytics Project

## Project Overview
An end-to-end data analytics project analyzing vendor performance
for an electronics retail business. Built to demonstrate real-world
data analyst skills across the full pipeline from raw data to insights.

**Industry:** Electronics Retail (Samsung, LG, Sony, Bosch and more)
**Time Period:** FY2024
**Tools Used:** Python, SQL, SQLite, Pandas, Matplotlib, Seaborn,
SciPy, Jupyter Notebook, Power BI

---

## Business Problem
Retail companies lose profitability through three main areas:
- Inefficient pricing strategies
- Poor inventory turnover  
- Over-dependence on certain vendors

This project identifies and quantifies these issues across
10 vendors and 15 product brands.

---

## Project Notebooks (Run in Order)

| Notebook | What it does |
|---|---|
| 01_generate_data | Creates realistic synthetic sales and purchase data |
| 02_sql_and_database | Loads CSVs into SQLite, teaches SQL queries |
| 03_etl_pipeline | Builds vendor_sales_summary using optimized SQL joins |
| 04_eda_and_visualization | EDA, 8 charts answering 5 research questions |
| 05_statistics | Confidence intervals and hypothesis testing |
| 06_final_summary | Executive summary and full project checklist |

---

## How to Run

1. Install Anaconda from anaconda.com
2. Clone or download this repository
3. Open Anaconda Prompt and run: `jupyter notebook`
4. Run notebooks in order from 01 to 06
5. Open Power BI Desktop and connect to `outputs/vendor_sales_summary.csv`

---

## Key Findings

| Research Question | Finding |
|---|---|
| Which brands need promotion? | Brands with margin above 80% but low sales identified |
| Who are top vendors? | Samsung India and LG Electronics drive highest sales |
| How concentrated is procurement? | Top 3 vendors account for majority of spend |
| Does bulk buying reduce cost? | Large orders cost significantly less per unit |
| Who has poor inventory turnover? | Vendors below 1.0 turnover flagged for intervention |
| Do margins differ significantly? | Yes, confirmed by two-sample t-test (p < 0.05) |

---

## Technical Skills Demonstrated

- **SQL** — joins, GROUP BY, aggregations, query optimization
- **Python / Pandas** — ETL pipeline, data cleaning, feature engineering
- **Statistics** — confidence intervals, hypothesis testing with SciPy
- **Visualization** — Matplotlib and Seaborn, 11 chart types
- **Power BI** — interactive dashboard with KPI cards and filters
- **Jupyter Notebook** — end-to-end reproducible analysis pipeline

---

## Author
**Anurag**
Location: Ghaziabad, Uttar Pradesh