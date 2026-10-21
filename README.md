<p align="center">
  <a href="https://thrinesh13.github.io/"><img src="./assets/banner.svg" alt="Thrinesh Vuribindi, Data Analyst" width="100%" /></a>
</p>

<p align="center">
  <a href="https://thrinesh13.github.io/"><img src="https://img.shields.io/badge/Portfolio-thrinesh13.github.io-0D6A61?style=flat-square" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/thrineshv/"><img src="https://img.shields.io/badge/LinkedIn-thrineshv-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:vuribindithrinesh@gmail.com"><img src="https://img.shields.io/badge/Email-vuribindithrinesh%40gmail.com-4A5A56?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://learn.microsoft.com/en-us/users/trineshvuribindi-2141/credentials/ee8e4ff074331db2"><img src="https://img.shields.io/badge/Microsoft%20Certified-DP--600%20Fabric%20Analytics%20Engineer-0078D4?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft Certified DP-600" /></a>
</p>

Data Analyst at **UnitedHealth Group** with 4.5+ years building the pipelines, data models, and Power BI dashboards behind claims, cost, and performance reporting.

This GitHub holds my project work, with the code and documentation behind each analysis, so you can trace how the numbers were produced, not only the final dashboard.

## Projects

### [Medicare Claims Payment Integrity](https://github.com/thrinesh13/Medicare-Claims-Payment-Integrity-Analytics)
**Question:** Which Medicare Part B claims can rules safely approve or deny before payment, and where does human review still matter?<br>
**Result:** 10 SQL prepayment edits route 96% of claims at 93.3% accuracy, catch 82% of improper claims, and cut modeled review cost from $425K to $120K.<br>
**In the repo:** 3 notebooks (data cleaning → core tables → payment integrity rules), staging, core, and mart layers in PostgreSQL, and a 4-page Power BI report (`.pbix`).

<sub>SQL · PostgreSQL · Python · Power BI · DAX</sub>

### [Surgical Scheduling Variance Analysis](https://github.com/thrinesh13/Surgical-Scheduling-Variance-Analysis) · [Live dashboard](https://thrinesh13.github.io/Surgical-Scheduling-Variance-Analysis/dashboard/)
**Question:** How often do booked surgery durations miss, and which procedures drive the cost?<br>
**Result:** 53.3% of 48.1K cases miss by 30+ minutes. 133 of 418 procedures drive 53.6% of an estimated $15.8M to $27.1M yearly cost exposure.<br>
**In the repo:** bronze, silver, and gold notebooks in Microsoft Fabric (PySpark, 1.88M records), the Power BI semantic model as TMDL source files, and data lineage, data quality, and dashboard guide docs.

<sub>Microsoft Fabric · PySpark · Spark SQL · Power BI · DAX</sub>

### [Statistical Time-Series Analysis](https://github.com/thrinesh13/Statistical-Time-series-analysis)
**Question:** Do four common beliefs about a fast-growing stock hold up against five years of Apple trading data?<br>
**Result:** 3 of 4 were rejected. Volatility held near 1.65% a day as the price rose from $146 to $311, and volume did not predict price.<br>
**In the repo:** one notebook covering cleaning, trend, correlation, distribution, and hypothesis testing on 1,254 trading days, plus a data dictionary and charts.

<sub>Python · pandas · SciPy · Matplotlib</sub>

## Toolkit

| Stage | Tools |
| :--- | :--- |
| **Ingest and integrate** | SQL · Python · Azure Data Factory · SSIS · Airflow · dbt |
| **Store and model** | Snowflake · Microsoft Fabric · SQL Server · Oracle · PostgreSQL · Databricks |
| **Validate and govern** | Data profiling · Reconciliation · Data lineage · Row-level security |
| **Analyze** | SQL (CTEs, window functions) · Python (pandas) · Excel · Statistical testing · Forecasting |
| **Report** | Power BI (DAX, Power Query, Power BI Service) · Tableau · SSRS |

<p align="center"><sub>Open to data roles · Open to relocation · <a href="https://thrinesh13.github.io/">Full experience on my portfolio</a></sub></p>
