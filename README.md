# SaaS Revenue Leak & Customer Retention Dashboard

A portfolio data analytics project that analyzes synthetic B2B SaaS customer, subscription, usage, and invoice data to identify revenue leakage, payment risk, and retention issues through a Power BI dashboard.

## Overview

This project simulates a fictional SaaS business and answers a simple executive question:



## Business Problem

SaaS businesses often track growth but miss the operational signals behind revenue loss, such as failed payments, weak product engagement, and segment-level leakage.

This dashboard is built to help answer:
- How much billed revenue is actually being collected?
- Which industries, plans, or customer groups contribute the most revenue leakage?
- Which accounts appear high-risk from a payment and engagement perspective?
- How is revenue trending over time?

## Dashboard Summary

The Power BI dashboard provides an executive view of:
- Total billed revenue
- Total paid revenue
- Revenue leakage
- Failed invoices
- Average paid per customer
- Revenue trend over time
- Revenue leakage by industry
- High-risk customer accounts

This layout follows a one-page executive dashboard style with top-level KPIs, supporting trend visuals, and an action-oriented risk table.

## Dataset

The dataset is fully synthetic and generated in Python.

### Core tables
- `customers.csv` – customer profile data such as industry, region, company size, and acquisition channel
- `subscriptions.csv` – plan, billing cycle, pricing, seats, and contract dates
- `usage_monthly.csv` – monthly activity, sessions, API usage, and feature adoption signals
- `invoices.csv` – billed amount, paid amount, discounts, and payment status

The synthetic dataset is designed to resemble a B2B SaaS operating environment while remaining fully reproducible for portfolio use.

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Faker
- Power BI
- DAX
- Git / GitHub

## Key KPIs

The dashboard focuses on the following metrics:
- Total Billed
- Total Paid
- Revenue Leakage
- Failed Invoices
- Active Customers
- Average Paid per Customer

## Key Insights

Example insights surfaced by the dashboard include:
- Total paid revenue trails billed revenue, indicating measurable leakage in collections.
- Certain industries contribute disproportionately to revenue leakage.
- Failed invoices and lower customer engagement signals can help identify higher-risk accounts for follow-up.
- Revenue trends over time provide context for operational and customer health performance.

## Repository Structure

```text
saas-revenue-leak-retention-dashboard/
├── data/
│   ├── customers.csv
│   ├── subscriptions.csv
│   ├── usage_monthly.csv
│   └── invoices.csv
├── images/
│   └── dashboard screenshot(s)
├── notebooks/
│   └── 01_generate_synthetic_data.ipynb
├── powerbi/
│   └── SaaS Revenue Leak Dashboard.pbix
├── README.md
└── requirements.txt
```

## How to Use

1. Open the Jupyter notebook in the `notebooks/` folder to review or regenerate the synthetic data.
2. Use the CSV files in the `data/` folder as the Power BI data source.
3. Open the Power BI report in the `powerbi/` folder.
4. Explore the dashboard using slicers such as region, industry, company size, plan, and invoice month.






## Future Improvements

Possible next steps:
- Add churn event modeling
- Add customer health scoring
- Add cohort retention analysis
- Add Net Revenue Retention (NRR) and expansion/contraction revenue tracking
- Publish a lighter `.pbit` template alongside the `.pbix`


