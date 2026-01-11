# sql-data-cleaning-layoffs
SQL data cleaning project using a global layoffs dataset.

# SQL Data Cleaning Project – Layoffs Dataset

## Background and Overview
This project focuses on cleaning and preparing a real-world layoffs dataset using SQL.
The goal is to transform raw data into a clean, structured format suitable for analysis.

---

## Data Structure Overview
- layoffs.csv: Raw dataset containing company layoffs information
- Columns include company, industry, total_laid_off, percentage_laid_off, date, and location

---

## Executive Summary
The dataset contained missing values, duplicates, inconsistent formatting,
and invalid records. SQL queries were used to clean, standardize, and validate
the data to ensure accuracy and usability.

---

## Insights Deep Dive
Key cleaning steps included:
- Removing duplicate records
- Handling null and missing values
- Standardizing company names and industries
- Converting date fields to proper formats
- Removing irrelevant or invalid rows

---

## Recommendations
- Always validate raw datasets before analysis
- Use SQL CTEs and window functions for efficient cleaning
- Maintain raw and cleaned versions of datasets separately
