# Anil-Enterprise-Lakehouse-Medallion-Project-01

Automated Medallion Architecture with Azure Data Factory &amp; Databricks. Engineered a 3-layer pipeline (Bronze, Silver, Gold) for raw data processing. Features ADF orchestration, PAT-based security, and PySpark transformations. Optimized for scalability and cost-efficiency in end-to-end data engineering workflows.

Project Overview

This project demonstrates the implementation of a modern Medallion Architecture (Bronze, Silver, and Gold layers) using Azure Data Factory. The goal is to build a structured data lake that transforms raw, unorganized data into high-quality, business-ready insights.

Tech Stack

Orchestration: Azure Data Factory (ADF)
Transformation Engine: Azure Databricks (PySpark)
Storage: Azure Data Lake Storage (ADLS) Gen2
Database: Azure SQL Database
Security: Azure Key Vault
Architecture: Medallion (Bronze/Silver/Gold)

Key Features & Implementation

Bronze Layer: Ingested raw source data into ADLS Gen2 in its original format using ADF Copy Activities.

Silver Layer (Databricks): Utilized Azure Databricks to perform data cleaning, schema validation, and deduplication using PySpark to ensure data consistency.

Gold Layer (Databricks): Leveraged PySpark notebooks to perform complex business aggregations and loaded the final reporting-ready data into Azure SQL Database.

Data Pipelines: Developed modular ADF pipelines to orchestrate and trigger Databricks notebooks, moving and transforming data across different layers seamlessly.

Security: Implemented Azure Key Vault to securely manage and access sensitive credentials and connection strings.
