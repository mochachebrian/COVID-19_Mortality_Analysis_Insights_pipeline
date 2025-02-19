## COVID-19 Mortality Data Engineering Project

   This project analyzes COVID-19 mortality data, focusing on demographics (age, sex) and comorbidities (diabetes, hypertension). 
   
   It extracts, transforms, and loads (ETL) the data into a cloud warehouse for analysis and visualization.

## Architecture Overview:
Extract: Download and upload raw data to cloud storage (GCS or S3).

Load: Store the raw data in cloud buckets.

Transform: Clean and process data using Spark or Pandas.

Warehouse: Load cleaned data into BigQuery for analysis.

Modeling: Use dbt to create analytical models for insights.

Data Quality Checks: Validate data using Soda or Great Expectations.

Visualization: Build interactive dashboards with Metabase or Tableau.

##Tech Stack

Storage: Google Cloud Storage / Amazon S3

Processing: Apache Spark / Pandas

Warehouse: Google BigQuery

Orchestration: Apache Airflow

Modeling: dbt

Quality Checks: Soda / Great Expectations

Visualization: Metabase / Tableau

## Workflow
Extract: Ingest dataset from Kaggle into cloud storage.

Transform: Clean and structure data using Pandas/Spark.

Load: Store processed data in BigQuery.

Model: Use dbt to create analytical models.

Validate: Run data quality checks with Soda.

Visualize: Build dashboards in Metabase/Tableau.
