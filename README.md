# SQL Data Cleaning Project: Global Layoffs

## Overview
This project demonstrates data cleaning and preparation techniques using MySQL. The goal was to take a raw, messy dataset of global tech layoffs and transform it into a clean, analysis-ready format.

## Tools & Techniques Used
- **Database:** MySQL
- **Staging Tables:** Created isolated staging tables to protect raw data integrity.
- **Duplicate Removal:** Used CTEs and window functions (`ROW_NUMBER()` & `PARTITION BY`) to pinpoint and delete duplicate rows.
- **Data Standardization:** Trimmed trailing punctuation, harmonized inconsistent text categories, and used self-joins to dynamically fill in missing industry values.
- **Type Conversion:** Converted text dates into native `DATE` data types using `STR_TO_DATE()`.
- **Data Pruning:** Filtered out unresolvable null rows.

## Repository Files
- `layoffs_data_cleaning.sql`: The complete script containing all data cleaning steps.
