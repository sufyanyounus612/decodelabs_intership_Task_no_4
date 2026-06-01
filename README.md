# decodelabs_intership_Task_no_4
# Data Analytics Project 4 — Data Visualization
**DecodeLabs Industrial Training Kit | Batch 2026**

## Overview
This repository contains the complete Python solution for **Project 4: Data Visualization**, the optional mastery milestone of the DecodeLabs Data Analytics Industrial Training programme.

The goal is to transform 1,200 rows of raw e-commerce order data into boardroom-ready visual insights — applying the three pillars of professional data storytelling:

| Pillar | Role | Principle |
|---|---|---|
| 1 | The Architect | Choose the right chart for the business question |
| 2 | The Editor | Maximise data-ink ratio, eliminate chartjunk |
| 3 | The Storyteller | Write action titles, apply the SCR framework |

## Dataset
- **File:** `Dataset for Data Analytics.xlsx`
- **Rows:** 1,200 e-commerce orders
- **Columns:** OrderID, Date, CustomerID, Product, Quantity, UnitPrice, PaymentMethod, OrderStatus, ReferralSource, TotalPrice, and more
- **Date Range:** January 2023 – June 2025

## Charts Generated
| # | Chart Type | Business Question |
|---|---|---|
| 1 | Horizontal Bar | Which product generates the most revenue? |
| 2 | Line + Rolling Avg | Is monthly revenue trending upward? |
| 3 | Stacked Bar | How do order statuses break down by product? |
| 4 | Scatter Plot | Does cart size predict order value? |
| 5 | Bar Chart | Which referral channel drives the most revenue? |
| 6 | Heat Map | Which product × payment method has the highest cancellation rate? |
| 7 | YoY Bar (zero-baseline) | Did revenue grow year-over-year? |
| 8 | Executive Dashboard | Full SCR narrative — Situation → Complication → Resolution |

## Key Insights
- **Chairs** drove the highest total revenue among all products
- **Instagram** was the top revenue-generating referral channel
- A **20.8% cancellation rate**, concentrated in Gift Card + Chair combinations, poses a significant business risk
- Monthly revenue shows a **positive upward trend** from 2023 to 2025

## Tech Stack
- Python 3.x
- Pandas
- Matplotlib

## How to Run
```bash
pip install pandas matplotlib openpyxl
python data_analytics_project4.py
```
Charts are saved to the `charts/` folder.

## Project Context
Completed as part of the **DecodeLabs Data Analytics Industrial Training — Batch 2026**.
