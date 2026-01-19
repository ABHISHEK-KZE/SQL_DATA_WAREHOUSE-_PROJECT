## 🧱 SQL Data Warehouse & Analysis 

This project focused on designing and implementing a modern data warehouse using SQL and a Star Schema model. The goal is to consolidate operational data from multiple source systems (ERP and CRM) into an optimized, business-ready format for high-performance analytical queries and reporting.

## 🎯 Objectives

Design a Modern DWH: Implement a scalable data warehouse following the Medallion Architecture (Bronze, Silver, Gold layers).

Build ETL Pipelines: Develop robust SQL scripts to handle data extraction, cleansing, transformation, and loading (ETL).

Model Data for Analytics: Transform source data into a Star Schema model optimized for reporting efficiency.


## 🏗️ Data Architecture: The Medallion Approach

The project utilizes a layered data architecture to ensure data quality, traceability, and consistency before it reaches the end-user.

| Layer                 | Purpose         | Content                              | SQL Activity                                   |
| --------------------- | --------------- | ------------------------------------ | ---------------------------------------------- |
| **Bronze (Raw)**      | Ingestion       | Raw source data exactly as received  | Initial loading                                |
| **Silver (Cleansed)** | Standardization | Cleaned, validated, structured data  | Deduplication, type fixes, normalization       |
| **Gold (Analytical)** | Business-Ready  | Star Schema: Fact & Dimension tables | Fact creation, dimension loading, aggregations |


