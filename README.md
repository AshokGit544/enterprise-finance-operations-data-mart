# Enterprise Finance Operations Data Mart

Enterprise finance data pipeline project using Python for source-to-curated processing, KPI mart creation, SLA monitoring, exception queue generation, vendor scorecards, and finance operations reporting.

## Project Overview

This project simulates how enterprise companies process finance transaction data from source systems into reporting-ready analytical datasets.

The project follows a practical data pipeline approach where raw finance transactions are ingested, enriched with master data, validated for operational issues, and transformed into curated outputs for reporting and monitoring.

It is inspired by enterprise finance operations environments where teams need to monitor transaction flow, SLA performance, data quality, payment delays, and exception handling across finance processes.

## Business Use Case

In large organizations, finance operations teams work with invoice and payment data coming from multiple source systems.  
Before the data can be used for business reporting or AI-driven analysis, it must be cleaned, validated, enriched, and transformed into reliable reporting layers.

This project shows how that process can be done using Python and pandas.

It helps answer questions such as:

- How many finance transactions were processed each month?
- Which departments have the highest operational issue rates?
- Which vendors have the most invoice processing issues?
- How many invoices are on hold?
- How many payments are overdue?
- Which records should go into the exception queue for finance review?
- How can we create a KPI mart for downstream reporting tools like Power BI?

## What This Project Does

This project includes:

- finance master data generation
- source transaction generation
- data issues and exception simulation
- bronze layer raw data storage
- silver layer enrichment and validation
- gold layer KPI mart creation
- finance exception queue generation
- SLA summary generation
- vendor operations scorecard creation
- department operations summary creation
- daily finance operations queue generation

## Data Model Used

The project works with the following core finance entities:

- Vendors
- Cost Centers
- Profit Centers
- GL Accounts
- Source Transactions

The source transactions are enriched with finance master data to create a curated operational reporting layer.

## Pipeline Layers

### Bronze Layer
Raw finance transactions as received from source systems.

### Silver Layer
Standardized and enriched transaction data with:

- vendor enrichment
- cost center enrichment
- profit center enrichment
- GL account enrichment
- SLA calculations
- overdue payment flags
- hold flags
- master data issue flags
- operational exception reasons

### Gold Layer
Business-ready KPI marts and reporting tables for operational analysis.

## Key Features

- Synthetic enterprise finance master data
- Synthetic source transaction feed
- Bronze / Silver / Gold pipeline design
- Master data enrichment
- SLA monitoring
- Exception detection
- Exception priority assignment
- KPI mart generation
- Vendor operations scorecard
- Department operations summary
- Daily finance operations queue
- Output files ready for reporting

## Tech Stack

- Python
- pandas
- NumPy
- matplotlib
- Jupyter Notebook / Google Colab

## Project Flow

1. Create enterprise finance master data
2. Generate finance source transactions
3. Simulate operational issues and data quality exceptions
4. Save raw data as Bronze layer
5. Enrich and validate data in Silver layer
6. Calculate SLA and operational flags
7. Create Gold layer KPI mart
8. Build exception queue for finance operations
9. Create vendor and department scorecards
10. Export reporting datasets

## Operational Metrics Covered

This project tracks practical finance operations metrics such as:

- validation SLA
- approval SLA
- posting SLA
- payment overdue rate
- master data error rate
- hold invoice rate

These are common operational monitoring metrics used in enterprise finance reporting.

## Main Outputs

After running the notebook, the project generates files such as:

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

## Why This Project Is Strong

This project is strong because it looks like actual enterprise work.

It is not just a basic data analysis notebook.  
It shows how raw finance data moves through a processing pipeline and becomes useful for finance operations monitoring and business reporting.

It demonstrates:

- enterprise data processing
- master data enrichment
- data quality handling
- SLA monitoring
- exception management
- operational KPI reporting
- reporting dataset creation for downstream dashboards

## Example Business Questions

This project can help answer questions like:

- Which vendors have the highest finance processing issue rate?
- Which departments have the most SLA breaches?
- What percentage of invoices are on hold?
- How many payments are overdue?
- Which records are high priority in the exception queue?
- What is the monthly finance processing trend?
- Which gold-layer KPIs can be used in a Power BI dashboard?

## Skills Demonstrated

- Python
- pandas
- NumPy
- enterprise data pipeline design
- bronze / silver / gold processing
- finance data modeling
- SLA monitoring
- exception queue generation
- KPI mart creation
- operational reporting

## Suggested Interview Explanation

I built an Enterprise Finance Operations Data Mart project that simulates how finance transaction data is processed in a real enterprise environment. The project starts with raw source transactions, enriches them with vendor, cost center, profit center, and GL account master data, then applies validations for SLA breaches, overdue payments, hold invoices, and master data issues. I created bronze, silver, and gold layers, along with KPI marts, exception queues, vendor scorecards, and department-level operational summaries for reporting use cases.

## How to Run

1. Open the notebook in Google Colab
2. Install dependencies
3. Run all cells from top to bottom
4. Review the generated output files
5. Upload the notebook and outputs to GitHub

## Suggested Repository Name

`enterprise-finance-operations-data-mart`

## Suggested Repository Description

Enterprise finance data pipeline project using Python for source-to-curated processing, KPI mart creation, SLA monitoring, exception queue generation, vendor scorecards, and finance operations reporting.
