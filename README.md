# 🧹 MySQL - Layoffs Data Cleaning Project

This project is part of a hands-on SQL portfolio series designed to demonstrate real-world data cleaning techniques using MySQL. The dataset contains records of global company layoffs and required substantial cleaning to prepare it for meaningful analysis.

---

## 📊 Dataset Overview

The dataset (`layoffs.csv`) includes:
- Company names
- Locations
- Dates of layoffs
- Number of employees laid off
- Percentage laid off
- Industry and other relevant fields

The original data was messy, inconsistent, and contained duplicates, missing values, and irregular formatting — making it ideal for a practical data cleaning challenge.

---

## 🎯 Project Objectives

- Clean and standardize the dataset using SQL.
- Handle missing values and formatting issues.
- Remove duplicate and inconsistent records.
- Prepare the data for analysis or use in BI tools.

---

## ❓ Key Cleaning Steps

✔ Trimmed extra spaces and standardized casing for company names.  
✔ Removed duplicate rows using `ROW_NUMBER()` with CTEs.  
✔ Converted string-based dates to SQL `DATE` format using `STR_TO_DATE()`.  
✔ Addressed NULL and empty values in key columns (e.g., industry, total layoffs).  
✔ Dropped or fixed rows with incomplete or inconsistent data.  
✔ Ensured numeric values (e.g., `percentage_laid_off`) were in usable format.  

---

## 🛠️ Tools Used

- **MySQL**
- **VS Code / MySQL Workbench**
- **CSV (original data source)**

---

## 📂 Files

- `Portfolio Project - Data Cleaning.sql`: All SQL queries used during the cleaning process.
- `layoffs.csv`: The raw dataset used in this project.

---

## ✅ Outcome

After cleaning, the dataset is:

- Consistent and standardized
- Free of duplicate and null-heavy records
- Ready for analysis or importing into a BI tool like Tableau or Power BI

---

## 📌 What You’ll Learn

This project is a great demonstration of:
- SQL data cleaning best practices
- CTEs and window functions (e.g., `ROW_NUMBER()`)
- Handling NULLs and irregular data types
- Preparing real-world data for business analysis

---

## 📎 License

This project is for educational and portfolio purposes. Dataset credit goes to [original source if available].

---

