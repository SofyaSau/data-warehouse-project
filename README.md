# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repositury! 🚀  
This project demonstrates a comprehensive data warehouse and analytics solution, from building a data warehouse to grnrrating actionable insights. Designed as a portfolio project highlights industry best practices in data engineering and analyticd.

---

## 📖 Project Overview

This project involves:
1. **Data Architecture:** Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver** and **Gold** layers.
2. **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling:** Development fact and dimension tables optimized for analytical queries.
4. **Analitycs & Reporting:** Creating SQL-based reports and dashboards for actionable insights.

🎯 This repository is an excellent resource for professionals and students looking to showcase exppertise in:
- SQL Delelopment
- Data Architecture
- Data Engineering
- ETL Pipeline Developer
- Data Modeling
- Data Analitycs

---

## 🔨 Important Links & Tools:

Evrething is for Free!

- [Datasets](datasets): Acces to the project dataset (csv files)
- [SQL Server Express](https://learn.microsoft.com/en-us/sql/linux/quickstart-install-connect-ubuntu?view=sql-server-ver17&tabs=ubuntu2004%2C2505ubuntu2404%2Codbc-ubuntu-1804): Lightweight server for hosting your SQL database.
- [SQL Server Managment Studio (SSMS)](https://learn.microsoft.com/en-us/ssms/install/install): GUI for managing and interacting with databases.
- [Git Repository](https://github.com/): Set up A GitHub account and repository to manage, verson and collaborate on your code efficiently.
- [DrawIO](https://www.drawio.com/): Design data architecture, models, flows, and diagrams.
- [Notion](https://www.notion.so): All-in-one tool for project managment and organization/
- [Notion Project Steps](https://www.notion.so/Data-Warehouse-Project-cd61a661c75442969d85353b9c4b8099?source=copy_link): Access to All Project Phases and tasks.

---

## 🚀 Project Requirements

### Building the Data Warehouse (Dana Engineering)

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources:** Import data from two source system (ERP and CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope:** Focuse on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analytics)

#### Objective
Develop SQL-based analitycs to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

---

## 🚧 Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver** and **Gold** layers:  
<img width="1039" height="636" alt="architecture_dwh" src="https://github.com/user-attachments/assets/543d33bd-a372-4352-97ff-67bdc791486a" />

1. **Bronze Layer:** Stores raw data as-is from the source system. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer:** This layer includes data cleansing, standartization, and normalization processes to prepare data for analysis.
3. **Gold Layer:** Houses business-ready data modeled into a star schema required for reporting and analytics.

---

## License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify and share this project with proper attribution.

## About Me

Hi there! I'm Sofia Sautych, a Business Intelligence specialist focused on building end-to-end BI systems and handling analytics platform migrations.
