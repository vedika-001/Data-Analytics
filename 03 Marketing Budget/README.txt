MARKETING BUDGET & PERFORMANCE — REAL-WORLD RAW DATASET

Scenario:
You are a Marketing Data Analyst. Management wants to know whether marketing
budgets are allocated efficiently, which channels produce profitable growth,
where overspending occurs, and how budget should be reallocated.

FILES
campaign_master_raw.csv       Campaign-level master
daily_performance_raw.csv     Daily performance
budget_allocations_raw.csv    Budget allocation/approval history
leads_sales_raw.csv           Lead-to-sales funnel
vendor_invoices_raw.csv       Vendor/media/agency invoices

RAW DATA WARNING
The data intentionally contains duplicates, missing values, inconsistent
capitalization/spaces, different date formats, negative/invalid values,
outliers, and one-to-many relationships.

CRITICAL:
Determine the GRAIN of every table before joining. Do not blindly sum campaign
metrics after merging daily performance, leads, allocations, or invoices.

Business objective:
Determine how marketing budget should be allocated to maximize profitable
revenue while controlling waste and improving campaign efficiency.

Recommended workflow:
1. Understand grain
2. Data quality audit
3. Cleaning
4. Key validation
5. Analytical dataset construction
6. Budget vs actual
7. Channel/campaign analysis
8. Funnel analysis
9. Profitability
10. Waste/anomaly detection
11. Budget reallocation
12. Dashboard
13. Executive recommendations
