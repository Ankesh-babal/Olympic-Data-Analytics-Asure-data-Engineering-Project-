# Olympic Data Analytics Project
## Cloud-Based Data Analysis & Insight Generation Using Azure
### 📌 Project Summary

This project demonstrates how raw Olympic historical data can be transformed into meaningful business insights using Azure cloud services, SQL, and Python.

The objective was not just to build a pipeline, but to create an analytics-ready dataset that supports reporting, trend analysis, and data-driven decision making — similar to how data teams operate in banking, insurance, and enterprise 

### 🛠️ Tools & Technologies

Azure Data Factory – Data ingestion & orchestration

Azure Data Lake Storage Gen2 – Data storage (raw & curated layers)

Azure Databricks (PySpark) – Data cleaning & transformation

Azure Synapse Analytics – SQL analytics & querying

SQL – Data analysis

Python – Data preparation

<img width="1536" height="1024" alt="img olympics" src="https://github.com/user-attachments/assets/90c328c7-85eb-4ce5-80d6-c7127be804ab" />


### 🔄 End-to-End Workflow

#### Data Ingestion

Loaded Olympic CSV datasets into Azure Data Lake

Used Azure Data Factory pipeline to move data into structured storage layers

#### Data Cleaning & Preparation

Using PySpark in Databricks:

Handled missing values

Standardized column formats

Removed duplicates

Created derived metrics (e.g., total medals per athlete)

Structured data into fact-style analytical tables

#### SQL-Based Analysis

Using Azure Synapse:

Created external tables

Performed aggregations and joins

Generated country-level and year-level insights
