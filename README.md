🏦 Bank Customer Churn: ETL Pipeline 🚀
📊 Project Overview
This project implements a complete ETL (Extract, Transform, Load) pipeline using Python to process bank customer data. The goal is to convert raw, flat data into a cleaned, relational format suitable for production databases.

🛠️ Step-by-Step Implementation
Extract: Ingested raw churn data from a 10k-record CSV 📥.
Transform: * Cleaned duplicates and standardized schemas 🧼.
Feature Engineering: Created age_group and credit_segment flags for deeper analysis 🏷️.
Data Normalization: Split the dataset into Customer, Bank, and Churn tables to reduce redundancy 📉.
Load: Persisted the transformed data into a relational SQLite database and exported modular CSVs 💾.

📁 Repository Structure
raw/: Source dataset.
processed/: Normalized CSV files.
output/: Final SQLite database (database.sqlite).
task14_etl.ipynb: Documented Python workflow.

✅ Quality Assurance
Validation: Confirmed 100% record retention (10,000 rows) post-transformation.
Integrity: Verified primary key consistency across all relational tables.
