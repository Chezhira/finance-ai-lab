# Finance ETL Pipeline — Monthly Close Dataset

This is the flagship Finance AI Lab project.

It demonstrates a production-grade finance data engineering workflow for monthly close reporting: raw ERP CSV extracts in, validated curated data out, with BI-ready outputs and an interactive HTML dashboard.

## Business problem

Finance teams often spend days every month cleaning ERP exports, validating data, checking completeness, reconciling transactions, rebuilding reports, and preparing management packs manually.

The problem is not only reporting speed. It is control risk:

- inconsistent source files
- missing or invalid fields
- weak audit trails
- manual spreadsheet transformations
- unclear data quality ownership
- slow month-end reporting cycles

## What the project does

The pipeline automates the monthly close reporting flow:

- ingests raw ERP CSV files
- validates input schemas
- performs data quality checks
- creates curated Parquet outputs
- creates BI-ready star-schema tables
- generates KPI monthly reporting
- produces data quality exception logs
- produces an interactive HTML dashboard
- supports repeatable CLI execution by reporting month

## Skills demonstrated

- finance data engineering
- monthly close automation
- data quality controls
- audit-ready reporting
- Python pipeline design
- CLI design
- Parquet output design
- BI-ready data modeling
- finance KPI design
- reproducible reporting workflows

## Best for

- Controllers
- CFOs
- finance data teams
- AI accounting startups
- ERP/BI implementation teams
- multi-entity businesses with recurring close pressure

## Live project repository

https://github.com/Chezhira/Finance-ETL-Pipeline-Monthly-Close-Dataset

## Suggested screenshots to add later

Create a `screenshots/` folder and add:

- dashboard homepage
- KPI monthly output
- data quality exception report
- sample star schema output
- CLI run screenshot
