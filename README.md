# DecodeLabs Week 1 Project 1 – Data Cleaning and Preparation

## 📌 Project Overview

This project focuses on cleaning and preparing a raw dataset for analysis. The data was checked for missing values, duplicate OrderIDs, date formatting, coupon codes, and price formatting.

## 🛠️ Data Cleaning Performed

* Handled missing CouponCode values by replacing them with `NO COUPON`
* Checked and removed duplicate OrderIDs
* Standardized date format to `YYYY-MM-DD`
* Standardized UnitPrice and TotalPrice to 2 decimal places
* Standardized text fields
* Performed validation checks after cleaning

## ✅ Validation Results

| Check                     |     Result |
| ------------------------- | ---------: |
| Rows after cleaning       |       1200 |
| Missing values remaining  |          0 |
| Duplicate OrderIDs        |          0 |
| Invalid date values       |          0 |
| CouponCode blanks handled |        309 |
| UnitPrice format          | 2 decimals |
| TotalPrice format         | 2 decimals |

## 📂 Project Files

* `DecodeLabs_Project1_Data_Cleaned.xlsx` — Cleaned dataset with Validation and Change_Log sheets
* `DecodeLabs_Project1_Change_Log.pdf` — Documentation of the cleaning changes and their impact

## 🎯 Outcome

The dataset was successfully cleaned, standardized, and validated, making it ready for further analysis.
