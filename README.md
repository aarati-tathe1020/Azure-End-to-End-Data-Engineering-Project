#🚀 API-Driven End-to-End Data Engineering Pipeline – Microsoft Azure

## 📌 Project Overview

This project demonstrates an end-to-end cloud-based data engineering solution using Microsoft Azure services and the Medallion Architecture (Bronze, Silver, and Gold).

The API-Driven End-to-End Data Engineering Pipeline uses GitHub as the data source for AdventureWorks business data. Azure Data Factory manages data ingestion, Azure Data Lake Storage Gen2 stores raw and processed data, and Azure Databricks with PySpark performs data transformations.

The transformed data is made available through Azure Synapse Analytics for querying and Power BI for reporting and visualization.



## 🎯 Business Objective

To develop a scalable cloud-based data engineering pipeline that retrieves data from GitHub, ingests and stores raw data, processes it using Azure Databricks, and prepares structured, analytics-ready datasets for business reporting.


## 🏗️ Project Architecture

![End-to-End Azure Data Engineering Project Architecture](Architecture/Project%20Architecture.jpeg)


## 🛠️ Technology Stack

- GitHub API – Data Source
- Microsoft Azure
- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Apache Spark
- PySpark
- Azure Synapse Analytics
- SQL
- Power BI
- GitHub

##  🏗️ Medallion Architecture 

### 🥉 Bronze Layer – Raw Data Ingestion

- Source: GitHub API – AdventureWorks dataset.
- Ingestion: Azure Data Factory dynamic copy pipeline.
- Storage: Azure Data Lake Storage Gen2.
- Stores raw source files for further processing.
  
### 🥈 Silver Layer – Data Transformation

- Processing: Azure Databricks.
- Language: PySpark.
- Reads raw datasets from the Bronze layer.
- Performs data cleaning and dimension data transformations.
- Stores transformed datasets in Parquet format in ADLS Gen2.
  
### 🥇 Gold Layer – Analytics and Data Warehousing

- Platform: Azure Synapse Analytics.
- Uses OPENROWSET() to query Parquet files.
- Creates SQL views and external tables.
- Prepares structured data for analytics and reporting.


## 📸 Project Screenshots

### 1. Azure Resources

![Azure Resource Group](Screenshots/Resource_group.png)

Storage Account

![ADLS Storage Account](Screenshots/Storage_account.png)

### 2. Azure Data Factory

ADF – Source Dataset Configuration

![ADF Copy Source](Screenshots/adf-dynamic-copy-source.png)

ADF – Sink Dataset Configuration

![ADF Copy Sink](Screenshots/adf-dynamic-copy-sink.png)

### ADF Pipeline Success

Azure Data Factory – Successful Pipeline Execution

![ADF Pipeline Success](Screenshots/ADF_dynamc_pipeline_success.png)

### 3. Bronze Layer

Bronze Layer – Raw Data Storage

![Bronze Layer](Screenshots/Bronze%20Container.png)

### 4. Databricks Transformation

Databricks – Dimension Data Transformation

![Databricks Transformation](Screenshots/ADB_data_dimension_transformation.png)

### 5. Silver Layer

Databricks – Silver Layer Data Loading

![Silver Layer Loading](Screenshots/ADB_silver_layer_data_loading.png)

Silver Layer – Transformed Data Storage

![Silver Container](Screenshots/Silver%20Container.png)

### 6. Synapse Gold Layer

Synapse Analytics – Gold SQL Views

![Gold Views](Screenshots/create-gold-views.png)

Synapse Analytics – External Table Creation

![External Table](Screenshots/create-external-table-sql.png)

Gold Layer – Analytics Data Storage

![Gold Container](Screenshots/Gold%20Container.png)


## 📊 Project Output

✅ Successfully retrieved AdventureWorks data from GitHub API.

✅ Ingested raw data into ADLS Gen2 using Azure Data Factory.

✅ Processed and transformed data using Azure Databricks and PySpark.

✅ Stored transformed datasets in Parquet format in the Silver layer.

✅ Created SQL views and external tables using Azure Synapse Analytics.

✅Prepared analytics-ready data using Medallion Architecture.



## 🎓 Learning Outcomes

- Hands-on experience with Azure Data Engineering services.
- Understanding of API-based data ingestion.
- Practical knowledge of Medallion Architecture.
- Experience with PySpark data transformations.
- Understanding of cloud-based data pipeline development.
- Experience querying Parquet data using Synapse Analytics.
- Knowledge of organizing and documenting projects using GitHub.

## 👩‍💻 Author

Aarati Tathe

[LinkedIn](https://www.linkedin.com/in/aarati-tathe-7549b7263/)





