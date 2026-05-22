# customer-sales-etl-pipeline
This project demonstrates an end‑to‑end ETL pipeline for customer sales data using Databricks, Snowflake, and Power BI. Raw CSV files are ingested and cleaned in Databricks, enriched with calculated fields (Gross Margin, Net Revenue, Sales Year, Sales Month), and stored as a curated analytics view (sales_data_final). The cleaned dataset is then published to Snowflake for centralized storage and scalable querying. Finally, Power BI dashboards visualize revenue trends, profitability, salesperson performance, and discount impacts, enabling data‑driven business insights and reducing manual reporting effort.

# Tech Stack
Databricks (data ingestion & transformation)
Snowflake (cloud data warehouse)
Power BI (visualization)
SQL & Python (data transformation, scripting)

# Workflow
Ingest raw CSV data into Databricks
Clean and transform data (handle nulls, categories, outliers)
Feature engineering (GrossMargin, NetRevenue, SalesYear, SalesMonth)
Save curated view sales_data_final
Publish to Snowflake for centralized storage
Visualize in Power BI dashboards

# Key Features
Automated ETL pipeline
Curated analytics layer
KPI metrics for profitability and trends
Interactive dashboards for business insights
