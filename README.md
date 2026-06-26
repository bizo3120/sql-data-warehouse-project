# Data Warehouse and Analytics Project

This repository contains an end-to-end data warehousing and analytics solution: from building the warehouse and modelling the data, through to producing reports that support concrete business decisions.
It is structured as a portfolio project and follows established data engineering and analytics practices. Each stage is documented so the workflow can be followed step by step — from raw source data, through the ETL pipeline and the data model, to the final analyses.

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture]

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.
