Data Warehouse & Analytics Project

Welcome to this Data Warehouse & Analytics repository! 📊
This project walks through building a complete end-to-end solution — from ingesting raw data into a warehouse to delivering insights with analytics. The goal is to demonstrate how modern data engineering and analytics practices can be applied in a practical, portfolio-ready project.

🔹 Project Architecture

The design follows a layered Medallion Architecture with three stages:

Bronze Layer – Holds raw source data exactly as received (CSV files ingested into SQL Server).

Silver Layer – Performs transformations such as cleaning, deduplication, and standardization.

Gold Layer – Provides a star-schema model with fact and dimension tables optimized for reporting.

This structure ensures clarity, scalability, and trust in the data across different use cases.

📖 What’s Inside

This project covers:

Architecture Design – Implementing Bronze, Silver, and Gold layers in SQL Server.

ETL Workflows – Scripts to extract, transform, and load raw CSVs into structured models.

Data Modeling – Star schema design for analytical efficiency.

Analytics & Reporting – SQL-based reports that answer key business questions.

🎯 Skills Demonstrated

By working through this project, you’ll gain hands-on practice with:

SQL Development

Data Engineering

ETL Pipeline Design

Data Modeling (fact & dimension tables)

Analytics & Reporting

Perfect for students, analysts, or engineers looking to strengthen their portfolio.

🛠️ Tools & Resources

Datasets – Provided CSVs simulating ERP and CRM systems.

SQL Server Express – Lightweight database server.

SQL Server Management Studio (SSMS) – IDE for database management.

Draw.io – Used to create architecture diagrams and data models.

GitHub – Version control and project collaboration.

🚀 Requirements & Scope
Objective

Build a SQL Server data warehouse that integrates multiple sources (ERP and CRM), cleans the data, and produces actionable insights.

Specifications

Import sales and customer data from CSVs.

Cleanse and standardize datasets before loading.

Integrate into a single warehouse schema for analysis.

Focus only on the latest dataset (no historization).

Document models and flows for business and technical users.

Deliver SQL-based reports on customer behavior, product performance, and sales trends.

📂 Repository Layout
data-warehouse-project/
│
├── datasets/          # ERP and CRM CSV source files  
├── docs/              # Documentation & diagrams  
│   ├── etl_flow.drawio  
│   ├── architecture.drawio  
│   ├── data_catalog.md  
│   ├── data_models.drawio  
│   ├── naming_conventions.md  
│
├── scripts/           # SQL ETL scripts  
│   ├── bronze/  
│   ├── silver/  
│   ├── gold/  
│
├── tests/             # Data quality checks  
├── README.md  
├── LICENSE  
└── requirements.txt  

📊 Example Insights

Some of the analytics you can generate include:

Customer segmentation and purchasing patterns

Top-performing products and categories

Monthly/quarterly sales trends

Key growth metrics for decision-making


👋 About the Author

I’m a data enthusiast passionate about turning raw information into meaningful insights. This project reflects my interest in data engineering and analytics, and my goal is to make complex concepts approachable and practical.

