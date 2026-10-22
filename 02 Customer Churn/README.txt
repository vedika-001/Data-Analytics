
CUSTOMER CHURN ANALYTICS — REAL-WORLD RAW DATASET
=================================================

Purpose:
This is intentionally messy, multi-table customer churn data designed to simulate
a real Data Analyst project. Do NOT clean it before starting.

Files:
1. customers_raw.csv
   Customer master/profile, plan, acquisition, signup, churn information.
2. monthly_usage_raw.csv
   Monthly product engagement and usage behavior.
3. payments_raw.csv
   Billing/invoice/payment history.
4. support_tickets_raw.csv
   Customer support interactions, issues, resolution and CSAT.
5. marketing_interactions_raw.csv
   Campaign and customer engagement activity.

Primary key:
- customers_raw.customer_id
- monthly_usage_raw.customer_id -> customers
- payments_raw.customer_id -> customers
- support_tickets_raw.customer_id -> customers
- marketing_interactions_raw.customer_id -> customers

Important:
- The files are deliberately RAW.
- Expect duplicate rows.
- Expect missing values.
- Expect inconsistent capitalization, spaces and date formats.
- Expect invalid/outlier numeric values.
- Expect inconsistent categorical labels.
- Some customer IDs appear multiple times in transaction/event tables.
- Do not simply delete every duplicate: determine whether it is a true duplicate
  or a legitimate repeated transaction/event.
- churn_flag is 1 for customers who churned and 0 otherwise.
- churn_date is blank for non-churned customers.

Suggested business objective:
"Understand why customers churn, identify high-risk customer segments,
measure the financial impact of churn, and recommend actions that could
reduce churn."

Recommended workflow:
1. Data understanding
2. Data quality audit
3. Cleaning and standardization
4. Relationship/key validation
5. Exploratory analysis
6. KPI creation
7. Churn segmentation
8. Cohort/retention analysis
9. Financial impact analysis
10. Customer-level risk analysis
11. Dashboard/storytelling
12. Business recommendations

Important analytical caution:
Do not use churn_date/churn_flag or any post-churn information as a predictor
when building a "pre-churn" customer risk model. Separate descriptive churn
analysis from predictive modeling.
