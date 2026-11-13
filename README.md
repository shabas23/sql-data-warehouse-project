# SQL Data Warehouse Project

Welcome to the **SQL Data Warehouse Project** repository! This project demonstrates a comprehensive, end-to-end data warehousing and analytics solution—from ingesting raw data to building a star schema ready for business intelligence and reporting.

> ⭐ **If this project helps you, please star the repository so other learners can find it too!**

---

## 📖 Project Overview

In this project, you take raw CSV files from two separate systems (**CRM** and **ERP**) and build a unified data warehouse in **SQL Server**. By the end, the data is cleansed, standardized, and modeled for analytical queries.

1. **Design the Architecture:** Implement a modern data warehouse using a three-layer Medallion Architecture (Bronze, Silver, Gold).
2. **Build ETL Pipelines:** Extract raw source files, load them into SQL Server, and transform the data across layers.
3. **Model the Data:** Create business-ready Fact and Dimension tables using a Star Schema.
4. **Analyze & Test:** Validate data quality and answer key business questions using SQL.

---

## 🏗️ Data Architecture

This project follows the **Medallion Architecture** with three distinct layers:

* **🥉 Bronze Layer:** Stores raw data *as-is* directly from the source CSV files into SQL Server tables.
* **🥈 Silver Layer:** Handles data cleansing, standardization, and normalization to resolve data quality issues and prepare the data for integration.
* **🥇 Gold Layer:** Houses business-ready data modeled into a **Star Schema** (Facts & Dimensions), optimized for analytical reporting.

---

## 🚀 Project Requirements & Specifications

**Objective:** Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

* **Data Sources:** Import sales, customer, and product data from two source systems (ERP and CRM) provided as CSV files.
* **Data Quality:** Cleanse and resolve data anomalies, duplicates, and formatting issues prior to analysis.
* **Integration:** Combine both sources into a single, user-friendly analytical data model.
* **Scope:** Focus on the latest dataset only (historization/SCD is not required).
* **Documentation:** Provide clear data catalogs, architecture diagrams, and data flow documentation for stakeholders and analysts.
