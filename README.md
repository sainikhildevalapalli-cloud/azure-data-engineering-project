# Azure Data Engineering Project

## Project Overview

This project demonstrates an end-to-end Azure Data Engineering pipeline using the Olist E-commerce dataset.

The objective is to ingest raw data into Azure Data Lake Storage Gen2, transform it using Azure Databricks (PySpark), orchestrate the pipeline using Azure Data Factory, store curated data in Azure SQL Database, and visualize business insights using Power BI.

---

## Architecture

```
Raw CSV
    │
    ▼
Azure Data Lake Storage Gen2
(Bronze)
    │
    ▼
Azure Databricks
(PySpark Cleaning)
    │
    ▼
Silver Layer
    │
    ▼
Gold Layer
    │
    ▼
Azure SQL Database
    │
    ▼
Power BI Dashboard
```

---

## Azure Services Used

- Azure Resource Group
- Azure Data Lake Storage Gen2
- Azure SQL Database

Future additions:

- Azure Data Factory
- Azure Databricks
- Power BI

---

## Dataset

**Dataset:** Olist Brazilian E-Commerce Dataset

Source:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## Current Progress

- ✅ Resource Group Created
- ✅ Storage Account Created
- ✅ ADLS Gen2 Enabled
- ✅ Bronze/Silver/Gold Containers Created
- ✅ Raw Dataset Uploaded
- ✅ Azure SQL Database Created
- ⏳ Azure Data Factory
- ⏳ Azure Databricks
- ⏳ Power BI Dashboard

---

## Project Structure

```
azure-data-engineering-project
│
├── data
├── docs
├── images
├── notebooks
├── pipelines
└── README.md
```

---

## Screenshots

### Resource Group

(Add screenshot)

### Storage Account

(Add screenshot)

### Containers

(Add screenshot)

### Azure SQL Database

(Add screenshot)

---

## Next Steps

- Build Azure Data Factory pipeline
- Load Bronze data
- Create Silver layer
- Transform data using PySpark
