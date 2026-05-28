<div align="center">

# 🛒 Zepto SQL Data Analysis Project

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&pause=1000&color=36BCF7&center=true&vCenter=true&width=800&lines=SQL+Data+Analysis+Project+📊;Zepto+Inventory+Analysis+🛒;PostgreSQL+%2B+Business+Insights+🚀" />

![SQL](https://img.shields.io/badge/SQL-PostgreSQL-blue?style=for-the-badge&logo=postgresql)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-success?style=for-the-badge)
![Project](https://img.shields.io/badge/Project-Portfolio-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</div>

---

# 📌 Project Overview

This project focuses on **end-to-end SQL data analysis** using a real-world inspired **Zepto e-commerce inventory dataset**.

The goal of this project is to simulate how data analysts work in retail and e-commerce industries by:

✅ Creating a structured database  
✅ Cleaning messy inventory data  
✅ Performing Exploratory Data Analysis (EDA)  
✅ Writing business-driven SQL queries  
✅ Extracting meaningful insights from inventory and pricing data

This project demonstrates practical SQL skills used in real analyst workflows.

---

# 🎯 Objectives

The project was designed to:

- Understand real-world inventory datasets
- Practice SQL data cleaning techniques
- Perform exploratory data analysis
- Analyze pricing and stock patterns
- Generate business insights using SQL
- Strengthen SQL portfolio and interview skills

---

# 🗂 Dataset Information

The dataset represents **Zepto product inventory data**.

Each row corresponds to a unique product SKU.

### Dataset Columns

| Column | Description |
|---|---|
| sku_id | Product ID |
| name | Product name |
| category | Product category |
| mrp | Original product price |
| discountPercent | Discount offered |
| discountedSellingPrice | Final selling price |
| availableQuantity | Available stock |
| weightInGms | Product weight |
| outOfStock | Stock status |
| quantity | Product quantity |

---

# ⚙️ Tech Stack

- PostgreSQL
- SQL
- pgAdmin
- CSV Dataset
- Data Analysis

---

# 🏗 Project Workflow

This project follows a structured SQL analysis workflow.

## 1️⃣ Database Creation

Created the inventory database and defined table schema with proper data types.

```sql
CREATE TABLE zepto (
    sku_id SERIAL PRIMARY KEY,
    category VARCHAR(120),
    name VARCHAR(150),
    mrp NUMERIC,
    discountPercent NUMERIC,
    availableQuantity INTEGER,
    discountedSellingPrice NUMERIC,
    weightInGms INTEGER,
    outOfStock BOOLEAN,
    quantity INTEGER
);
