# Internship-Task-1 – Customer Personality Analysis

This repository contains my solution for **Task 1** of the Elevate Internship program.  
The task involves performing basic data cleaning and preparation on a customer dataset provided in Excel format.

## 📄 File Included

- `Elevate task 1 ANS.xlsx`: The processed Excel file containing cleaned customer data.

## 🔧 Data Cleaning Performed

- Checked and handled missing values 
- Removed duplicate rows using `.drop_duplicates()`
- Standardized text values (e.g., gender, city names)
- Converted date formats to `dd-mm-yyyy` using `pd.to_datetime()`
- Renamed column headers to clean format (`lowercase_with_underscores`)
- Verified and corrected data types (`int`, `datetime`, `category`)

## 📌 Tools Used

- Excel (for initial viewing and minor adjustments)

## 🔍 Goal

To demonstrate understanding of basic data cleaning techniques in both Excel and Python, as well as practical skills in preparing a dataset for analysis or modeling.
