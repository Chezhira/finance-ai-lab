# 06 - FinSight Lite: Finance Intelligence Dashboard

FinSight Lite is a control-first finance intelligence dashboard that turns raw ERP/accounting exports into validated finance marts, anomaly detection, KPI dashboards, and CFO-style commentary.

This is a portfolio proof-of-capability project. It is not positioned as a production SaaS product.

## Business problem

Finance teams often receive messy accounting or ERP exports and are expected to produce reliable management insight quickly. The data needs validation, transformation, exception checks, and finance-friendly modelling before commentary or insight can be trusted.

## What it demonstrates

- Raw finance CSV ingestion
- Data quality validation before reporting
- DuckDB-based local finance database
- dbt finance staging and mart models
- Monthly P&L and KPI outputs
- Budget vs actual analysis
- Explainable anomaly detection
- CFO-style commentary generated from governed finance outputs
- Control-first finance AI design

## Tech stack

- Python
- Pandas
- DuckDB
- dbt
- Streamlit
- Plotly
- Pytest
- Ruff / Black

## Verified MVP outputs

- 966 GL transaction rows processed
- 72 monthly P&L rows generated
- 6 data quality exceptions surfaced
- 30 finance anomalies generated
- dbt models and tests passing
- pytest checks passing
- Streamlit dashboard running locally

## Standalone repository

https://github.com/Chezhira/finsight-lite

## How it fits into the Finance AI Lab

FinSight Lite extends the Finance AI Lab beyond workflow automation into finance analytics engineering.

The MCP and agent projects demonstrate controlled finance workflows, approvals, and operational automation. FinSight Lite demonstrates the analytics layer: validated finance data, governed transformation, anomaly detection, dashboards, and CFO-style commentary.
