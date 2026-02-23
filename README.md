# Anil-Enterprise-Lakehouse-Medallion-Project-01

Automated Medallion Architecture with Azure Data Factory &amp; Databricks. Engineered a 3-layer pipeline (Bronze, Silver, Gold) for raw data processing. Features ADF orchestration, PAT-based security, and PySpark transformations. Optimized for scalability and cost-efficiency in end-to-end data engineering workflows.

Project Overview

This project demonstrates the implementation of a modern Medallion Architecture (Bronze, Silver, and Gold layers) using Azure Data Factory. The goal is to build a structured data lake that transforms raw, unorganized data into high-quality, business-ready insights.

Tech Stack

Orchestration: Azure Data Factory (ADF)
Storage: Azure Data Lake Storage (ADLS) Gen2
Database: Azure SQL Database
Architecture: Medallion (Bronze/Silver/Gold)

Key Features & Implementation

Bronze Layer: Ingested raw source data into ADLS Gen2 in its original format.
Silver Layer: Cleaned and standardized the data to ensure consistency and removed duplicates.
Gold Layer: Modeled the data into business-level aggregates for reporting and analytics.
Data Pipelines: Developed modular ADF pipelines to move and transform data across different layers seamlessly.
