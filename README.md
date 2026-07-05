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

<img width="1920" height="1080" alt="Resource_Group" src="https://github.com/user-attachments/assets/a3e3f53f-2a20-451a-a81f-5cb229bdaa11" />

### Storage Account

<img width="1920" height="1020" alt="Storage_account" src="https://github.com/user-attachments/assets/23c052ab-a783-4d53-ae2e-522ec6ccb35a" />

### Containers

<img width="1920" height="1080" alt="Container" src="https://github.com/user-attachments/assets/1bf29d06-60ad-403f-8fd7-e8864d541a44" />

### Bronze Layer

<img width="1920" height="1080" alt="bronze_layer" src="https://github.com/user-attachments/assets/93adfaf3-01e9-45b3-a624-bacb59a653aa" />

### Azure SQL Database

<img width="1920" height="1080" alt="azure_SQL_DB" src="https://github.com/user-attachments/assets/5bab29f3-dd66-4dec-a605-b6c55654a1ab" />


---

## Next Steps

- Build Azure Data Factory pipeline
- Load Bronze data
- Create Silver layer
- Transform data using PySpark
