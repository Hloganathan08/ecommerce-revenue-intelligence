# E-Commerce Revenue Intelligence Dashboard

## 📊 Live Dashboard
👉 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/harshita.loganathan/viz/E-CommerceRevenueIntelligenceDashboard/Dashboard1)

---

## Project Overview
End-to-end revenue intelligence analysis of 100K+ Brazilian e-commerce orders.
Diagnosed a revenue growth plateau, segmented customers by value, forecasted
future revenue, and delivered an executive Tableau dashboard.

---

## Key Findings

| Finding | Number |
|---|---|
| Total revenue analyzed | $15.4M |
| Peak revenue month | Nov 2017 — $1.15M |
| Champions revenue contribution | 27.3% from 15.9% of customers |
| At Risk customers | 13,660 worth $896K |
| Top 5 states revenue share | 73.2% |
| Nov 2018 revenue forecast | $1.69M |

---

## The Business Story
- **Revenue plateaued at ~$1M/month from Jan 2018** after strong 2017 growth
- **Top 15% of customers (Champions) generate 27% of revenue** — protecting them is critical
- **13,660 At Risk customers** represent $896K in revenue at risk of being lost
- **SP (São Paulo) drives 37.4%** of all revenue — geographic concentration risk
- **Prophet forecast projects $1.69M** for Nov 2018 — driven by seasonal uplift

---

## Analyses Performed

### 1. Revenue Trend Diagnosis
Monthly revenue trend analysis identifying the exact growth plateau point
and quantifying the revenue ceiling effect in 2018.

### 2. RFM Customer Segmentation
Recency, Frequency, Monetary scoring across 96K+ orders — segmented
customers into Champions, Loyal, Potential, At Risk, and Lost with
revenue contribution per segment.

### 3. Delivery Performance Analysis
Correlation between delivery speed and order value — found that slower
deliveries correlate with higher-value orders (logistics complexity).

### 4. Geographic Revenue Intelligence
State-level revenue concentration analysis — top 5 states generate
73.2% of revenue with SP alone contributing 37.4%.

### 5. Revenue Forecasting (Prophet)
Facebook Prophet model forecasting Sep–Nov 2018 revenue with
confidence intervals — projecting 36% growth from Sep to Nov 2018.

---

## Project Structure
```
ecommerce-revenue-intelligence/
├── data/
│   ├── olist_orders_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_customers_dataset.csv
│   ├── ecommerce_master.csv          # Cleaned + scored master dataset
│   └── monthly_revenue.csv           # Monthly aggregated revenue
├── notebooks/
│   ├── 01_eda_revenue.ipynb          # EDA + RFM + Delivery + Geographic
│   └── 02_forecasting.ipynb          # Prophet forecasting model
└── dashboard/
    └── dashboard_screenshot.png
```

---

## Tech Stack
- **Python** — pandas, numpy, matplotlib, seaborn, prophet
- **SQL** — DuckDB for analytical queries
- **Tableau Public** — interactive executive dashboard
- **GitHub** — version control

---

## Dataset
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
— 100K+ orders, 9 tables, real transactional data

---

## Author
**Harshita Loganathan**
[LinkedIn](https://www.linkedin.com/in/harshitaloganathan) | [Tableau Public](https://public.tableau.com/app/profile/harshita.loganathan)