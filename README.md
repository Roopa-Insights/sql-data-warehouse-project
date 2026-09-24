
# SQL Data Warehouse and Analytics Project

Welcome to my **SQL Data Warehouse and Analytics Project**! 🚀

This project demonstrates how to build a data warehouse using **SQL Server**, from loading raw data to cleaning, transforming, modeling, and analyzing the data.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** with three layers:

1. **Bronze Layer**: Stores raw data loaded from CSV files.
2. **Silver Layer**: Cleans, transforms, and standardizes the data.
3. **Gold Layer**: Stores business-ready data for analytics and reporting.

---

## 📖 Project Overview

This project involves:

1. **Data Architecture**: Building a data warehouse using Bronze, Silver, and Gold layers.
2. **ETL Process**: Extracting, transforming, and loading data using SQL Server.
3. **Data Cleaning**: Identifying and fixing data quality issues.
4. **Data Modeling**: Creating fact and dimension tables using a Star Schema.
5. **Data Analytics**: Using SQL to analyze customers, products, and sales.

---

## 🎯 Project Requirements

### Building the Data Warehouse

* **Data Sources**: ERP and CRM data provided as CSV files.
* **Data Quality**: Clean and resolve data quality issues before analysis.
* **Integration**: Combine data from different sources into one analytical model.
* **Data Modeling**: Create fact and dimension tables for reporting.
* **Documentation**: Document the data warehouse, data flow, and data model.

### Analytics

The project focuses on:

* **Customer Behavior**
* **Product Performance**
* **Sales Trends**
* **Business Insights**

---

## 🛠️ Tools Used

* **SQL Server**
* **SQL Server Management Studio (SSMS)**
* **T-SQL**
* **Draw.io**
* **Git & GitHub**

---

## 📂 Repository Structure

```text
data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information for the repository
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
```

---

## 📚 What I Learned

* SQL Server
* T-SQL
* ETL
* Data Cleaning
* Data Transformation
* Medallion Architecture
* Star Schema
* Fact and Dimension Tables
* SQL Analytics
* Data Quality Testing



