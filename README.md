# 🚀 API-Driven End-to-End Data Engineering Pipeline – Microsoft Azure

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


🔨 Project Implementation
🔄 Implementation Workflow
1. 🌐 Data Extraction: Retrieve AdventureWorks data from GitHub API.
2. ⚙️ Data Ingestion: Use Azure Data Factory to ingest data into ADLS Gen2.
3. 🥉 Bronze Layer: Store raw data in the Bronze container.
4. 🔥 Data Transformation: Clean and transform data using Azure Databricks and PySpark.
5. 🥈 Silver Layer: Store processed data in Parquet format.
6. 🥇 Gold Layer: Create SQL views and external tables using Azure Synapse Analytics.
7. 📊 Reporting: Prepare analytics-ready data for Power BI.
   

📊 Project Results

✅ Source data retrieved from GitHub.
✅ Data ingested into the Bronze layer.
✅ Data cleaning and transformations performed in the Silver layer.
✅ Transformed datasets stored in Parquet format.
🔄 SQL views and external tables created and validated.
📌 Power BI reports developed.


