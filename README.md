# SQL Data Warehouse Analytics

This project demonstrates the creation and analysis of a mini data warehouse using SQL Server.  
It includes scripts to create a dimensional model, load data from CSV files, and perform exploratory analytics on customers, products, and sales data.

---

## Features
- **Database & Schema Setup**
  - Creates the `DataWarehouseAnalytics` database
  - Defines `gold` schema for dimensional modeling
- **Tables**
  - `gold.dim_customers` – Customer demographic details
  - `gold.dim_products` – Product catalog with categories and costs
  - `gold.fact_sales` – Transactional sales data
- **Data Loading**
  - Uses `BULK INSERT` to populate tables from CSV files
- **Exploratory Analytics**
  - Customer demographic insights (countries, gender, ages)
  - Product performance analysis (categories, top/bottom products)
  - Sales metrics (total sales, items sold, average price, total customers)

---

## Project Structure
