# Netflix_DataEngineering_Project

## Overview

This project is a real-time, end-to-end Azure Data Engineering solution built using the latest tools and technologies. It covers data ingestion, transformation, validation, and orchestration to create a production-grade pipeline leveraging the Medallion Architecture (Bronze, Silver, and Gold layers)

## Features

1. Dynamic, parameterized data pipelines in Azure Data Factory (ADF)

2. Incremental data ingestion using Databricks Autoloader

3. Delta Live Tables for efficient ETL workflows

4. Orchestrated workflows in Databricks

5. Data validation and monitoring using ADF & Azure Monitoring

6. Seamless data integration with Azure Synapse Analytics & Power BI

## Architecture

### Technologies Used:

1. Azure Data Factory (ADF) – for data ingestion from GitHub & Azure Data Lake

2. Azure Data Lake Storage (ADLS Gen2) – for scalable cloud storage

3. Azure Databricks – for data transformation, ETL, and orchestration

4. Azure Synapse Analytics – for data warehousing and reporting

5. Power BI – for data visualization

### Workflow

1. Data Source: Netflix data is stored in GitHub and Azure Data Lake.

2. Data Ingestion: ADF copies data dynamically into ADLS (Bronze Layer).

3. Incremental Loading: Databricks Autoloader reads new data and stores it in the Silver Layer.

4. Transformation: Databricks processes data using Delta Live Tables, applying business logic and aggregations.

5. Gold Layer: Refined data is stored in the Gold Layer (Delta Lake) for analysis.

6. Data Consumption: The final dataset is available for Azure Synapse Analytics & Power BI.


