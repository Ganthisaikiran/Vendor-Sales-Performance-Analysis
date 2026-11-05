# Vendor Sales & Performance Analysis

**A business-focused data analytics portfolio project using Python, SQL, Power BI and Excel.**

## Project Overview

This project explores vendor and sales data to understand business performance across sales, profitability, vendor contribution, inventory and operating costs.

The goal is to turn raw data into clear business insights that can support vendor evaluation, inventory planning and better commercial decisions.

> **Project status:** In progress. Analysis, validated findings and dashboard deliverables will be added as they are completed.

## Business Objectives

- Measure sales and profitability across vendors.
- Identify high-performing and underperforming vendors.
- Compare vendor revenue contribution and profit margins.
- Examine inventory levels and stock turnover.
- Explore purchasing, freight and other operating costs.
- Translate analytical findings into practical recommendations.

## Tools & Technologies

| Tool | Planned use |
|---|---|
| Python | Data preparation and exploratory data analysis |
| Pandas | Data cleaning, transformation and aggregation |
| Matplotlib / Seaborn | Data visualisation |
| SQL | Business analysis, joins, aggregations and ranking |
| Power BI | Interactive KPI dashboards |
| Excel | Validation, summaries and supporting analysis |
| Git / GitHub | Version control and project documentation |

## Business Questions

1. Which vendors generate the highest sales and profit?
2. How concentrated is revenue among the top vendors?
3. Which vendors have strong sales but weak profitability?
4. How do sales and profitability change over time?
5. What do inventory levels and stock turnover indicate?
6. How significant are freight and other operating costs?
7. Which vendors or operational areas need further review?

## Planned Analysis

### 1. Data understanding and preparation
- Inspect tables, columns, data types and relationships.
- Check missing values, duplicates and inconsistent records.
- Document data assumptions and business definitions.
- Prepare analysis-ready datasets.

### 2. Exploratory data analysis with Python
- Analyse sales, purchases, costs and profit distributions.
- Compare vendor-level performance.
- Explore trends and category-level patterns where supported by the data.
- Visualise outliers and investigate unusual values.

### 3. SQL business analysis
- Use filtering, joins and aggregations to answer business questions.
- Rank vendors using window functions.
- Calculate revenue contribution and profitability metrics.
- Analyse inventory and operating-cost measures where the source data supports them.

### 4. Power BI dashboard
The planned report is organised into these views:

**Executive Overview**
- Sales and profit KPIs
- Profit margin
- Sales trends

**Vendor Performance**
- Vendor ranking
- Revenue contribution
- Profitability comparison

**Inventory & Operations**
- Inventory measures
- Stock turnover
- Freight and operating-cost analysis

*Dashboard screenshots and the Power BI file will be added after the report is built and validated.*

## Key Metrics

Metrics will be calculated only after confirming the source fields and business definitions.

| Metric | Definition |
|---|---|
| Total Sales | Sum of the selected sales amount field |
| Total Profit | Sales less the applicable costs, based on the dataset's definitions |
| Profit Margin | Total profit divided by sales |
| Vendor Contribution | Vendor sales divided by overall sales |
| Inventory Turnover | Calculated using a documented inventory/COGS definition |
| Freight Cost | Sum of freight charges, where available |

## Repository Structure

The repository will be expanded as each deliverable is completed. The intended structure is:

```text
Vendor-Sales-Performance-Analysis/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_data_inspection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_exploratory_data_analysis.ipynb
│   └── 04_business_insights.ipynb
├── sql/
│   ├── 01_data_exploration.sql
│   ├── 02_vendor_performance.sql
│   ├── 03_profitability_analysis.sql
│   └── 04_inventory_analysis.sql
├── powerbi/
│   ├── vendor_sales_dashboard.pbix
│   └── screenshots/
├── excel/
│   └── vendor_analysis.xlsx
├── reports/
│   └── business_recommendations.md
├── requirements.txt
├── .gitignore
└── README.md
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Ganthisaikiran/Vendor-Sales-Performance-Analysis.git
cd Vendor-Sales-Performance-Analysis
```

Create and activate a virtual environment on Windows:

```bash
python -m venv .venv
.venv\\Scripts\\activate
```

Install dependencies once the `requirements.txt` file has been added:

```bash
pip install -r requirements.txt
```

## Results & Business Recommendations

This section will contain verified findings, supporting charts and recommendations after the analysis is complete. No performance figures are published here until they have been independently reproduced and checked.

## Author

**Ganthi Sai Kiran**  
Aspiring Data Analyst | Python | SQL | Power BI | Excel

Interested in using data analysis to solve business problems and communicate insights clearly.

---

*Portfolio project for learning and demonstration. Dataset source, licensing and attribution will be documented with the data files before publication.*