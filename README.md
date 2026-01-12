# Cafe Sales Data Cleaning (Python + Pandas)

This project cleans a messy cafe sales dataset and exports a cleaned CSV for analysis and reporting.

## Dataset
- **Input:** `dirty_cafe_sales.csv`
- **Output:** `cleaned_cafe_sales.csv`
- The dataset contains cafe transaction data with missing values and inconsistent formats.

## What I did
- Loaded the dataset using Pandas
- Checked missing values and data types
- Cleaned inconsistent values (nulls, blanks, wrong formats)
- Exported the final cleaned dataset as a new CSV

## Files in this repo
- `cafe_sales.ipynb` — data cleaning & EDA notebook
- `dirty_cafe_sales.csv` — raw dataset
- `cleaned_cafe_sales.csv` — cleaned dataset
- `README.md` — project summary

## How to run
1. Install requirements:
   ```bash
   pip install pandas numpy
