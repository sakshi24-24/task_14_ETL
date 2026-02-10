🚀 Bank Customer Churn - ETL Pipeline

📌 Project Overview

A mini ETL (Extract, Transform, Load) pipeline built with Python and Pandas. This project processes raw customer churn data, cleans it, and loads it into a structured SQLite database for analysis.


🛠️ The ETL Process

Extract: Imported raw churn data from CSV 📂.

Transform: * Cleaned duplicates and nulls 🧼.

Categorized customers into Age Groups and Credit Segments 🏷️.

Normalized data into Dimension and Fact tables 📉.

Load: Exported processed data to .csv and a .sqlite database 💾.


📁 Repository Structure

processed/: Cleaned CSV files (customers, bank_details, churn).

output/: Final SQLite database file.

task14_etl.ipynb: Full Python implementation.


🧪 Validation

Verified row counts (10,000) across all stages ✅.

Validated primary key integrity for customerid ✅.
