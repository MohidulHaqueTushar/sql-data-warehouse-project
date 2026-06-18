## Develop a Modern Data Warehouse Using SQL Server
- The warehouse can be used to make analytical reports to add value to the decision-making process.

---

## Architecture

The data architecture for this project follows the Medallion Architecture across **Bronze**, **Silver**, and **Gold** layers.

### Overall Architecture & Data Flow
![Overall Architecture](architechture_and_dataflows/overall_architecture.svg)

![Data Flow Between Layers](architechture_and_dataflows/data_flow_between_layers.svg)

### Database Layer Breakdown
1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into the SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

### Medallion Database View
![Medallion DB View](architechture_and_dataflows/medallion_db_view.svg)

---

## Project Overview

This project involves:

### 1. Data Architecture
Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.

### 2. ETL Pipelines
Extracting, transforming, and loading data from source systems into the warehouse.
![Data Integration Pipeline](architechture_and_dataflows/data_integration.svg)

### 3. Data Modeling
Developing fact and dimension tables optimized for analytical queries.
![Data Modeling Schema](architechture_and_dataflows/data_modeling.svg)

---

## Skills
- SQL Development
- Data Architecture
- Data Engineering  
- ETL Pipeline   
- Data Modeling

---

## Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.