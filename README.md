# GSynergy Data Engineer Challenge 

### 1. Project Overview

This project is a solution to the GSynergy Data Engineer challenge. It involves:

- Extracting and processing raw fact and hierarchy data from .gz compressed files.
- Loading the data into a staging schema in a cloud-based data warehouse.
- Transforming and normalizing data into refined tables.
- Creating an aggregated materialized view (mview_weekly_sales).
- Implementing incremental updates using MERGE.


### 2. Data Sources
The dataset consists of pipe (|) delimited .gz files, classified into:

Fact tables:
- fact.transactions.dlm.gz
- fact.averagecosts.dlm.gz

Hierarchy (Dimension) tables:
- hier.prod.dlm.gz (Product details)
- hier.possite.dlm.gz (Point-of-sale data)
- hier.clnd.dlm.gz (Calendar mapping fiscal dates)
- hier.pricestate.dlm.gz (Pricing regions)

### 3. Tech Stack
- Cloud Storage: AWS S3 / Azure Blob Storage / GCP Cloud Storage
- Data Warehouse: Snowflake / Databricks / Redshift
- Scripting: SQL, Python (for pre-processing if needed)
- Orchestration: dbt (if applicable)

### 4. Schema Design

That I've attached in the word document

### 5. Setup Instructions
#### 5.1 Clone the Repository
#### 5.2 Upload Data to Cloud Storage

### 6. Load Data into Staging Tables

### 7. Transformations & Aggregation
#### 7.1 Normalizing Data
#### 7.2 Aggregation

### 8. Incremental updates
