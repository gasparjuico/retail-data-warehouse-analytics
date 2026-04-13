# Data Warehouse SQL

This folder contains the SQL components used to build a layered retail data warehouse.

## Structure

### scripts/
Core ETL pipeline and schema creation scripts.

Execution order:

1. `01_init_database.sql`
2. `02_bronze/`
3. `03_silver/`
4. `04_gold/`

### tests/
Validation queries used to check data quality, row counts, duplicates, and null values.

## Architecture

Raw CRM + ERP Sources → Bronze → Silver → Gold