# Commercial Business Intelligence - Power BI Dashboard

![Commercial Business Intelligence - -_page-0001](https://github.com/user-attachments/assets/f4cc07db-fc9e-4f0f-b274-b445d0e40852)


## Overview

This project analyzes sales, inventory, and vendor performance for a multi-location retail operation over the 2024 calendar year. The analysis reveals significant opportunities for optimization and strategic improvement across vendor relationships, inventory management, and product mix.

**Key Metrics:** Total Sales: $451.6M | Gross Profit: $129.7M | Profit Margin: 28.7% | Analysis Period: January - December 2024

**Tech Stack:** Python | Pandas | NumPy | SQLite3 | Matplotlib | Seaborn | SciPy | Microsoft Power BI | Jupyter Notebook

---

## Project Workflow

**Data Collection** → Downloaded 2GB dataset from raw CSV file

**Data Ingestion** → Loaded into SQLite database (206K+ records)

**Data Cleaning** → Handled missing values, standardized formats, merged sources using Pandas

**EDA & Analysis** → Performed sales distribution, inventory turnover, vendor performance, and geographic analysis

**Visualization** → Generated statistical insights and charts using Matplotlib and Seaborn

**Output** → Exported cleaned datasets and analysis results

**Dashboard** → Built interactive Power BI dashboards with KPIs, vendor comparisons, and trend analysis

---

## Quick Links

| Resource | Description |
|----------|-------------|
| [Raw Dataset](01_raw_dataset.csv) | Source data file (2GB CSV) |
| [Analysis Report](Analysis%20Report.md) | Complete insights and strategic recommendations |
| [EDA Notebook](03_Exploratory%20Data%20Analysis.ipynb) | Jupyter notebook with data exploration |
| [Vendor Analysis Notebook](04_Vendor%20performance%20Analysis.ipynb) | Jupyter notebook with vendor metrics |
| [Power BI Dashboard](Commercial%20Business%20Intelligence.pbix) | Interactive dashboard |

## Project Structure

```
├── 01_raw_dataset.csv                    Raw dataset (2GB)
├── 03_Exploratory Data Analysis.ipynb   EDA notebook
├── 04_Vendor performance Analysis.ipynb Vendor analysis notebook  
├── Analysis Report.md                    Strategic analysis report
├── Commercial Business Intelligence.pbix Power BI dashboard
└── README.md                            Project documentation
```

## Expected Outputs

**Analysis Phase:**
- Jupyter notebooks with comprehensive data analysis
- Statistical insights and visualizations
- Vendor performance metrics and risk assessment

**Reporting Phase:**
- Professional analysis report with strategic recommendations
- Interactive Power BI dashboard with KPIs and trends
- Data-driven insights for business decision making

## Key Findings

The analysis uncovered several critical insights that warrant immediate attention:

**Revenue Drivers:** Premium spirits brands dominate sales performance, with Jack Daniels, Tito's Vodka, and Grey Goose leading the portfolio. These established brands demonstrate consistent consumer preference and strong market positioning.

**Vendor Concentration Risk:** A single vendor accounts for 58.3% of stock turnover, creating significant supply chain vulnerability. This concentration level exceeds industry best practices and requires strategic diversification.

**Inventory Optimization:** Approximately $9 million in unsold capital has been identified across various product categories. This represents both a challenge and an opportunity, with projected recovery rates of 64-72% through targeted liquidation strategies.

**Growth Potential:** Strategic initiatives focused on vendor diversification, inventory optimization, and margin enhancement could generate approximately $37.7 million in total value creation over the next 12 months.

## Analysis Scope

The analysis examines multiple dimensions of business performance:

- Vendor performance rankings and relationship dynamics
- Product-level revenue analysis and brand positioning
- Inventory turnover rates and capital efficiency
- Monthly sales trends and seasonal patterns
- Geographic performance across locations
- Strategic recommendations with financial projections

## Strategic Recommendations

Based on the analysis, four priority areas have been identified:

1. **Vendor Diversification** - Reduce primary vendor dependency from 58.3% to below 40% through strategic partnerships with alternative suppliers.

2. **Inventory Liquidation** - Implement aggressive pricing and promotional strategies to recover $6+ million from the $9 million unsold capital within 90 days.

3. **Margin Enhancement** - Focus on premium product categories and renegotiate vendor terms to improve gross margin from 28.7% to 32%+.

4. **Demand Forecasting** - Deploy predictive analytics to optimize stock levels and reduce future inventory accumulation.

---

**Dataset Period:** January 2024 – December 2024 | **Analysis Date:** March 30, 2025
