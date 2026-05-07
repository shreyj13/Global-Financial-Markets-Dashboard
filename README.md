# Global Financial Market Volatility & Trend Analysis Dashboard

A Power BI dashboard project focused on analyzing global financial markets using volatility metrics, trend analysis, and interactive visualizations.

The dashboard provides insights into:

* Asset performance trends
* Gain vs Loss distribution
* Volatility segmentation
* Market behavior across different asset classes

---

# Dashboard Features

* Interactive Power BI dashboard
* Time-series market analysis
* Volatility classification (High vs Low)
* Gain/Loss trend comparison
* KPI cards for:

  * Average % Change
  * High Volatility %
  * Average Volatility
* Dynamic filtering by:

  * Asset Type
  * Date Range

---

# Technologies Used

* Power BI
* Power Query
* DAX
* Excel / CSV
* Financial Market Data

---

# Key Skills Demonstrated

* Data Cleaning & Transformation
* KPI Engineering
* Data Visualization
* Statistical Trend Analysis
* Financial Analytics
* Dashboard Design
* ETL Concepts

---

# Sample DAX Measures

```DAX id="4rm0gd"
Avg_Pct_Change = AVERAGE(FinancialData[pct_change])

Avg_Volatility = AVERAGE(FinancialData[volatility])
```

---

# Repository Structure

```bash id="y36uhg"
├── dashboard/
│   └── Financial_Market_Analysis.pbix
│
├── data/
│   └── dataset.csv
│
├── screenshots/
│   └── dashboard_preview.png
│
└── README.md
```

---

# How to Use

1. Clone the repository

```bash id="i20w22"
git clone https://github.com/shreyj13/global-financial-market-dashboard.git
```

2. Open the `.pbix` file in Power BI Desktop

3. Refresh data if needed and explore the dashboard

---

# Author

### Shreyas Jain

Power BI • SQL • Python • Data Analytics • Machine Learning
