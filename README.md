# Bank Marketing Data Pipeline
---
## Project Overview
This project focuses on developing an automated, reusable data engineering pipeline. I am using Databricks, PySpark, and SQL to ingest, validate, clean, and transform bank marketing campaign data into reliable analytics ready datasets.

The pipeline follows Databricks' Medallion Architecture (Bronze, Silver, and Gold) and is designed to support marketing campaign analysis and predictive modeling.

Technical objective (Data Engineering): Streamline and automate the processing of bank marketing campaign data so that new data can be consistently ingested, validated, cleaned, and transformed.

Business objective (Data Science): Improve the efficiency of the bank's marketing campaigns by identifying customers who are more likely to subscribe to a term deposit, reducing unnecessary calls and improving conversion rates.

## Dataset
---
The dataset contains historical data collected through telephone marketing campaigns conducted by a Portuguese banking institution.

- Source: UCI Machine Learning Repository — Bank Marketing
- Records: 41,188
- Columns: 21

Task: Binary classification

Target variable: y - whether a customer subscribed to a term deposit.

The dataset includes customer demographic information, credit and loan information, marketing campaign history, economic indicators, and campaign outcomes.

## Pipeline Architecture
---
Bronze: Raw data ingestion and storage using PySpark and Delta Lake.

Silver: Data profiling, quality validation, cleaning, and standardization.

Gold: Business-ready datasets for analytics and predictive modeling.



## Technologies

---

- Databricks

- Apache Spark / PySpark

- Python

- SQL

- Delta Lake

- Github and GitHub Actions
