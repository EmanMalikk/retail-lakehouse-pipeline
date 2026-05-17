# E-Commerce Lakehouse Architecture

## Project Overview
This project implements an end-to-end Data Engineering pipeline using Medallion Architecture in Databricks.

The pipeline processes e-commerce data through multiple layers:
- Bronze Layer
- Silver Layer
- Gold Layer

The final output is used for analytics and dashboard reporting.

---

# Architecture Flow

Raw CSV Data
    ↓
Bronze Layer (Raw Delta Tables)
    ↓
Silver Layer (Cleaned & Standardized Data)
    ↓
Gold Layer (Business Analytics Tables)
    ↓
Dashboards & Reporting

---

# Layers Explanation

## Bronze Layer
Stores raw ingested CSV data as Delta tables.

Tables:
- bronze_customers
- bronze_orders
- bronze_products
- bronze_order_items
- bronze_payments
- bronze_shipping

---

## Silver Layer
Performs:
- data cleaning
- deduplication
- datatype standardization
- null handling
- derived columns

Tables:
- silver_customers
- silver_orders
- silver_products
- silver_order_items
- silver_payments
- silver_shipping

---

## Gold Layer
Contains business-ready analytics tables.

Tables:
- gold_revenue
- gold_top_products
- gold_customer_revenue

---

# Technologies Used

- Databricks
- Apache Spark
- Delta Lake
- Python
- SQL
- GitHub

---

# Pipeline Orchestration

Databricks Workflows Jobs were used to orchestrate:
1. Raw data generation
2. Bronze ingestion
3. Silver transformations
4. Gold analytics generation

---

# Final Outcome

The pipeline delivers:
- Revenue analytics
- Product performance metrics
- Customer spending insights
- Dashboard-ready business KPIs