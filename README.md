# Data-warehouse
Built a SQL Server Data Warehouse using Bronze, Silver, and Gold layers for data cleaning, transformation, and business-ready analytics, with Excel reporting.

 SQL Server Data Warehouse & Analytics Project

Welcome to my SQL Server Data Warehouse & Analytics Project! 🚀

This project demonstrates the development of a data warehouse using SQL Server, following a Medallion Architecture with Bronze, Silver, and Gold layers. The project processes raw source data, performs data cleaning and transformation, and prepares business-ready data for analysis and reporting.

---

 🏗️ Data Architecture

The project follows a Bronze, Silver, and Gold architecture:

![Data Architecture](docs/data_architecture.png)

 🥉 Bronze Layer

Stores the raw data loaded from source CSV files into SQL Server.

- Raw data
- No major transformations
- Full and batch loading
- Stored as SQL Server tables

 🥈 Silver Layer

Contains cleaned and standardized data prepared for analysis.

- Data cleansing
- Data standardization
- Data normalization
- Data type conversions
- Derived columns
- Data enrichment

 🥇 Gold Layer

Contains business-ready data for reporting and analytics.

- Business logic
- Data integration
- Aggregations
- Analytical views
- KPI calculations

---

 📖 Project Overview

This project includes:

1. Data Ingestion – Loading raw CSV data into SQL Server.

2. Bronze Layer – Storing raw source data without major transformations.

3. Silver Layer – Cleaning, standardizing, and transforming the data.

4. Gold Layer – Creating business-ready views for analysis.

5. Excel Reporting – Using the Gold Layer data for analysis and reporting.

6. SQL Analytics – Performing analytical and ad-hoc SQL queries.

---

 🛠️ Technologies Used

- SQL Server
- T-SQL
- SQL Server Management Studio (SSMS)
- Microsoft Excel
- CSV Files
- Git & GitHub

---

 📊 Data Flow

```text
CSV Files
   │
   ▼
┌───────────────┐
│ Bronze Layer  │
│   Raw Data    │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│ Silver Layer  │
│ Cleaned Data  │
└───────┬───────┘
        │
        ▼
┌───────────────┐
│  Gold Layer   │
│ Business Data │
└───────┬───────┘
        │
        ├──────────────► Excel Reporting
        │
        └──────────────► SQL Analysis

