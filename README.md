# Marketing_compaign_analysis_jayab
# 🧼 Data Cleaning & EDA: Customer Personality Analysis

This repository contains data cleaning and basic exploratory data analysis (EDA) for the **Customer Personality Analysis** dataset from Kaggle. This project is part of a Data Analyst Internship Task focused on handling real-world data quality issues.

## 📊 Dataset Overview
The dataset contains marketing-related data about customer demographics, behaviors, and purchasing habits.

- Source: Kaggle
- Format: Tab-separated values
- Records: ~2,200 rows
- Features: Demographics, products purchased, campaign responses, etc.

## 🧹 What Was Done

| Task | Description |
|------|-------------|
| ✅ Data Loading | Used `sep='\t'` to correctly parse the file |
| ✅ Column Renaming | Renamed all columns for clarity and consistency |
| ✅ Missing Values | Filled `income` nulls with the median |
| ✅ Duplicate Removal | Dropped duplicate records |
| ✅ Infinite Values | Converted `inf/-inf` to `NaN` and treated them |
| ✅ Standardization | Normalized text data (e.g., marital status) |
| ✅ Date Conversion | Converted `enrollment_date` to datetime |
| ✅ Derived Fields | Created `age`, `total_spent`, `kids_total`, etc. |
| ✅ Export | Saved cleaned data to `cleaned_marketing_campaign.csv` |

## 📈 EDA Highlights

- Most customers are aged 30–60
- Spending is not always proportional to income
- Single and married customers dominate
- Most customers enrolled between 2012–2015

## 🗂 Files Included

- `marketing_compaign_jaya.ipynb` — full cleaning and EDA code
- `cleaned_marketing_campaign.csv` — ready-to-analyze dataset
- `README.md` — project summary and explanation

## 🚀 How to Run

```bash
pip install pandas matplotlib seaborn
jupyter notebook marketing_compaign_jaya.ipynb

 ---

## 👤 Author

**Jaya Bijore**  



