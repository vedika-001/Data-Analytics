BANKING RISK ANALYST DATASET

Purpose:
Synthetic, realistic banking-risk data for practicing the full Data Analyst workflow.

Raw-data rule:
DO NOT overwrite the raw files. Create cleaned/staging versions separately.

Tables:
branches_raw.csv — one row per bank branch.
customers_raw.csv — one row per customer, with intentional duplicate records and data-quality issues.
loans_raw.csv — one row per loan, with intentional duplicates, orphan customer IDs, invalid values and date anomalies.
repayments_raw.csv — one row per repayment event, with duplicates, missing values and invalid values.
transactions_raw.csv — one row per transaction, with duplicates, missing values, invalid values, inconsistent categories and future dates.

Relationships:
branches.branch_id -> customers.branch_id
branches.branch_id -> loans.branch_id
customers.customer_id -> loans.customer_id
customers.customer_id -> transactions.customer_id
loans.loan_id -> repayments.loan_id

Suggested tools:
Excel / Power Query
SQL / MySQL
Python / Pandas
Power BI or Tableau

The dataset is synthetic and does not contain real customer or bank data.
