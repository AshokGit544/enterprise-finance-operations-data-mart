# Enterprise Finance Operations Data Mart

I built this project to understand how finance data moves from raw source data into clean reporting data.

In many companies, finance data comes from different systems.  
Before it can be used for reporting, it needs to be cleaned, checked, joined with master data, and organized properly.

This project shows that process.

## What I did

In this project, I created:

- finance master data
- source transaction data
- raw finance data layer
- cleaned and enriched data layer
- finance KPI summary table
- finance exception queue
- SLA summary
- vendor scorecard
- department operations summary
- daily operations queue

## Why I did this project

I did this project to learn how companies prepare finance data for reporting and monitoring.

I wanted to understand:

- how raw finance data is stored
- how it is cleaned and enriched
- how errors and exceptions are tracked
- how KPI tables are created
- how reporting data is prepared

## Main data used

This project uses:

- Vendors
- Cost Centers
- Profit Centers
- GL Accounts
- Source Transactions

## What this project shows

This project shows how to:

- create finance source data
- clean and enrich the data
- check for data issues
- track SLA problems
- find overdue payments
- create an exception queue
- build KPI tables for reporting

## Layers in this project

### Bronze Layer
This is the raw source transaction data.

### Silver Layer
This is the cleaned and enriched data with:
- vendor details
- cost center details
- profit center details
- GL account details
- SLA flags
- overdue flags
- hold flags
- issue reasons

### Gold Layer
This is the final reporting layer with KPI tables and summaries.

## Tools I used

- Python
- pandas
- NumPy
- matplotlib
- Google Colab / Jupyter Notebook

## Project steps

1. Create finance master data
2. Create source transactions
3. Add some data issues and exceptions
4. Save raw data
5. Clean and enrich the data
6. calculate SLA and issue flags
7. Build KPI summary tables
8. Create exception queue
9. Create vendor scorecard
10. Create department summary

## Output files

After running the notebook, it creates files like:

- `vendors.csv`
- `cost_centers.csv`
- `profit_centers.csv`
- `gl_accounts.csv`
- `source_transactions.csv`
- `bronze_transactions.csv`
- `silver_enriched_transactions.csv`
- `gold_finance_kpi_mart.csv`
- `finance_exception_queue.csv`
- `sla_summary.csv`
- `vendor_operations_scorecard.csv`
- `department_operations_summary.csv`
- `daily_finance_operations_queue.csv`

## Example questions this project can answer

- How many transactions were processed each month?
- Which vendors have more issues?
- Which departments have more SLA problems?
- How many invoices are on hold?
- How many payments are overdue?
- Which records should be reviewed first?

## What I learned

From this project, I learned how to:

- process finance data step by step
- clean and enrich source data
- handle data quality issues
- track SLA problems
- create finance KPI tables
- prepare data for reporting

## Why this project is useful

I made this project to show how finance data can be prepared for real reporting use.

It helps turn raw data into something useful for:
- monitoring
- reporting
- dashboards
- operations review

## How to run

1. Open the notebook in Google Colab
2. Install the required libraries
3. Run all cells
4. Review the output files
5. Upload the notebook and outputs to GitHub
