# Data-Cleaning Project with Pandas in Python

## Overview
This project focuses on cleaning and preprocessing a dataset using Python's Pandas library. It demonstrates essential data cleaning techniques such as removing duplicates, handling missing values, standardizing data formats, and splitting fields to create a streamlined and well-structured dataset.

---

## Features
- **Duplicate Removal:**
  - Removed duplicate records and unnecessary columns to streamline the dataset.

- **String Data Cleaning:**
  - Stripped invalid characters from the "Last_Name" field.
  - Replaced invalid or missing values (e.g., 'Na' and 'nan') in the "Phone_Number" column.
  - Split the "Address" column into separate fields: `Street`, `State`, and `Zip Code`.

- **Categorical Data Standardization:**
  - Standardized the "Paying Customer" column by replacing values ('Yes'/'No') with ('Y'/'N').
  - Replaced 'N/a' and NaN values with empty strings.

- **Record Filtering:**
  - Removed records based on specific conditions, such as entries marked "Do_Not_Contact" and those missing phone numbers.

---

## Motivation
Data cleaning is a critical step in any data analysis pipeline. This project showcases the use of Pandas to handle common data quality issues, ensuring the dataset is accurate, consistent, and ready for further analysis or visualization.

---

## Tools and Technologies Used
- **Programming Language:** Python
- **Library:** Pandas

---

## Project Structure
- `data/` - Raw dataset used for cleaning
- `scripts/` - Python script implementing the cleaning process
- `results/` - Cleaned dataset ready for further use

---

## Acknowledgments
- Libraries: Pandas
- Inspiration: Common challenges faced in data preparation for analysis.

---
