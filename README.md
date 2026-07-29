# End-to-End ETL Pipeline using Databricks & PySpark

## Project Overview

This project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline built using Databricks and PySpark following the Medallion Architecture (Bronze, Silver, and Gold layers).

The pipeline ingests raw e-commerce data, performs data cleaning and validation, transforms it into business-ready datasets, and generates analytical insights to support business decision-making.

---

## Dataset


This project uses the **Brazilian E-Commerce Public Dataset by Olist**.

You can download the dataset from Kaggle:
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

---

## Technologies Used

- Databricks
- PySpark
- Spark SQL
- Delta Tables
- GitHub

---

## Project Architecture

Raw CSV Files
        │
        ▼
Bronze Layer
- Raw Data Ingestion

        │
        ▼
Silver Layer
- Data Cleaning
- Data Validation
- Schema Standardization
- Data Transformation

        │
        ▼
Gold Layer
- Gold Sales Summary
- Gold Customer Summary

        │
        ▼
Business Insights

---

## Gold Layer KPIs

### Gold Sales Summary

- Total Revenue
- Total Orders
- Average Order Value

### Gold Customer Summary

- Total Orders per Customer
- Total Amount Spent
- Customer Segmentation

---

## Business Insights

- Customer Order Distribution
- Top 10 Highest Spending Customers
- Customer Segment Distribution
- Top 10 Revenue Generating Product Categories
- Top 10 Least Revenue Generating Product Categories

---

## Key Learnings

- Built an end-to-end ETL pipeline using the Medallion Architecture.
- Applied data cleaning and validation using PySpark.
- Designed business-ready Gold tables.
- Performed customer and sales analytics.
- Generated actionable business insights from transactional data.

---

## Repository Structure

```
📂 databricks-pyspark-etl-project
│
├── Databricks_PySpark_ETL_Project.ipynb
├── README.md
└── LICENSE
```

---

## Author

**Usman Shaikh**



GitHub: https://github.com/yourusername
