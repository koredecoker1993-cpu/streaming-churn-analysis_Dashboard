# Subscriber Churn Analysis (Interactive Dashboard using Excel & Power BI)
---
## KEY METRICS SUMMARY

| Metric | Value |
| --- | --- |
| Peak Churn Rate (Aug 2024) | 18.74% |
| Customers Churned (Spike Months) | 1,420 |
| Top Churn Reason | Price Increase (39.08%) |
| Revenue Lost (Spike Months) | £18.91K |

## PROJECT OBJECTIVES

The goal of this project is to diagnose a churn spike for a fictional streaming subscription business, identify its root causes, and quantify its commercial impact using Excel and Power BI. It focuses on cleaning messy raw data, building KPI analyses, and delivering a stakeholder-ready interactive dashboard.


## DATASET USED
- <a href="https://github.com/koredecoker1993-cpu/streaming-churn-analysis_Dashboard/blob/main/streaming_subscription_churn_ra.xlsx">Dataset</a>

## QUESTIONS (KPIs)
- What is the monthly churn rate trend, and when did it spike?
- Which plan and region combinations were most affected by the spike?
- What are the top reasons customers churned during the spike months?
- What was the financial impact of the churn spike in lost revenue?

## PROCESS
- Data Preparation: imported and structured raw subscriber data containing plan, region, tenure, cancellation date, cancellation reason, and monthly charge.
- Data Cleaning: standardized inconsistent text casing, normalized ten spelling variants of the churn flag into a clean binary field, fixed a locale-based date parsing issue, removed duplicate rows, and handled nulls across Region, PaymentMethod, and CancellationDate.
- Data Transformation: created derived columns including TenureMonths, CancelMonth, and EngagementTier; built DAX measures in Power BI for spike-month filtering, churn rate, revenue lost, and top churn reason.
- Dashboard Build: designed an interactive Power BI dashboard with four KPI pages and a summary dashboard page featuring drill-down visuals and slicers by Plan and Region.


## DASHBOARD`
<img width="720" height="398" alt="Screenshot (670)" src="https://github.com/user-attachments/assets/fc08a22c-37fd-46a6-8008-b0e57a6e4084" />

   
