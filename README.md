**📦 RetailLake Analytics E-Commerce Lakehouse Pipeline**
 End-to-End E-Commerce Lakehouse Analytics Pipeline using Databricks, PySpark, and Delta Lake



## ⚙️ Tech Stack

### Data Processing
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge)

### Data Platform
![Databricks](https://img.shields.io/badge/Databricks-FE6B1A?style=for-the-badge)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-1E90FF?style=for-the-badge)

### Querying & Version Control
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge)

**🚀 Project Overview**

This end-to-end data engineering project simulates and processes e-commerce transactional data to generate meaningful business insights and analytics dashboards. We built a scalable data pipeline using Databricks, Apache Spark, and Delta Lake, following a Medallion Architecture (Bronze → Silver → Gold) to progressively transform raw data into analytics-ready datasets.

## 🏗️ End-to-End Pipeline Architecture

The following diagram illustrates the complete data flow and Medallion Architecture implementation used in this project:

![Pipeline Architecture](architecture/pipeline_architecture.png.JPG)

## 📂 Project Structure

```text
E-com-Project/
│
├── notebooks/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── data/
│   └── raw/
│
├── sql/
│   ├── revenue_analysis.sql
│   ├── top_products.sql
│   ├── customer_spending.sql
│   ├── yearly_orders.sql
│   └── category_revenue.sql
│
├── dashboards/
│   └── dashboard_notes.md
│
├── architecture/
│   ├── architecture.md
│   └── pipeline_architecture.png.JPG
│
├── README.md
└── .gitignore
```
