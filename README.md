# 📊 SalesPulse™ — FY2024 Sales Analysis Repository

> A complete, client-ready business sales analysis project — from raw data to interactive dashboard to strategic report.

![Dashboard Preview](https://img.shields.io/badge/Dashboard-HTML%20%2B%20Chart.js-0D7C7C?style=flat-square)
![Excel](https://img.shields.io/badge/Workbook-Excel%20%2F%20.xlsx-217346?style=flat-square)
![Python](https://img.shields.io/badge/Built%20with-Python%20%2B%20pandas-3776AB?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

---

## 📁 Repository Structure

```
salespulse-fy2024-analysis/
│
├── sales_data_raw.csv           # Cleaned & validated transaction dataset
├── SalesPulse_Analysis.xlsx     # 5-sheet Excel workbook with charts & KPIs
├── dashboard.html               # Interactive web dashboard (Chart.js)
├── INSIGHTS_REPORT.md           # Full written analysis & recommendations
└── README.md                    # This file
```

---

## 🗂️ What's Inside

### `sales_data_raw.csv`
2,000 cleaned transaction records with 14 columns:
- `Order_ID`, `Date`, `Product`, `Category`, `Region`, `Channel`, `Sales_Rep`
- `Quantity`, `Base_Price`, `Discount_Pct`, `Unit_Price`, `Revenue`, `COGS`, `Profit`

### `SalesPulse_Analysis.xlsx`
Professional Excel workbook with 5 sheets:
| Sheet | Contents |
|---|---|
| **Sales Data (Cleaned)** | Full formatted dataset with alternating row colors |
| **Executive Summary** | KPI tiles, monthly trend table, revenue vs. profit chart |
| **Product Analysis** | Product ranking table, bar chart, margin analysis |
| **Category & Region** | Category pie chart, region bar chart, breakdown tables |
| **Channel & Sales Reps** | Channel mix, rep scorecard table, rep performance bar chart |

### `dashboard.html`
Interactive web dashboard — open in any browser, no server needed:
- 6 KPI cards
- Monthly revenue & profit (bar + line combo chart)
- Quarterly breakdown
- Product ranking with horizontal progress bars
- Category donut chart
- Regional horizontal bar chart
- Channel mix donut
- Sales rep ranking chart and scorecard table

### `INSIGHTS_REPORT.md`
10-section written analysis covering:
1. Executive Summary
2. Revenue & Profitability Overview
3. Revenue Trends Over Time
4. Top-Selling Products
5. Category Performance
6. Regional Performance
7. Sales Channel Analysis
8. Sales Rep Performance
9. **5 Strategic Recommendations**
10. FY2025 Revenue Outlook

---

## 📈 Key Findings (FY2024)

| Metric | Value |
|---|---|
| Total Revenue | **$800,466** |
| Total Profit | **$331,957** |
| Profit Margin | **41.5%** |
| Top Product | Laptop Pro X1 ($261K, 32.7% of revenue) |
| Top Category | Electronics (74.4% of revenue) |
| Top Region | North ($215,898) |
| Top Channel | Online (55%) |
| Top Rep | Eva R. ($112,512) |
| Peak Month | December ($99,036) |
| Weakest Month | November ($58,820) |

---

## 🚀 How to Use

**View the Dashboard:**
```bash
# Simply open in your browser
open dashboard.html
# or double-click the file
```

**Open the Excel Workbook:**
```bash
# Requires Microsoft Excel or LibreOffice Calc
open SalesPulse_Analysis.xlsx
```

**Explore the Raw Data:**
```python
import pandas as pd
df = pd.read_csv('sales_data_raw.csv', parse_dates=['Date'])
df.describe()
```

**Read the Report:**
```bash
# Any Markdown viewer, GitHub renders it automatically
cat INSIGHTS_REPORT.md
```

---

## 🛠️ Built With

- **Python 3** — data generation and Excel workbook creation
- **pandas** — data manipulation and aggregation
- **openpyxl** — Excel formatting, formulas, and chart embedding
- **Chart.js 4** — interactive dashboard visualizations
- **Markdown** — structured insights report

---

## 💡 Skills Demonstrated

This project covers real data analyst workflows:

- ✅ Data cleaning and validation
- ✅ Revenue trend analysis (monthly, quarterly, YoY)
- ✅ Product performance ranking
- ✅ Category and geographic breakdowns
- ✅ Channel and rep performance analysis
- ✅ KPI dashboard design
- ✅ Business writing: insights and strategic recommendations
- ✅ Professional Excel workbook design with charts
- ✅ Interactive HTML dashboard

---

## 📄 License

MIT — free to use, adapt, and share.

---

*SalesPulse™ FY2024 | Data Analytics Portfolio Project*
