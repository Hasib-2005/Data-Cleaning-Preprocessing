# Data Cleaning and Preprocessing Assignment

## Project Overview

This project focuses on identifying and fixing common data quality issues in a dirty dataset using Python, Pandas, NumPy, and data visualization techniques.

The dataset contained various problems such as missing values, duplicate records, inconsistent formatting, outliers, incorrect data types, noisy text data, class imbalance, and schema issues. All problems were cleaned and validated through a Jupyter Notebook.

---

## Dataset Information

* Dataset Type: Employee and Customer Data
* Rows: 10,000
* Columns: 15
* File Used: `dirty_dataset.csv`

---

## Problems Solved

### Task 01 – Missing Values

Handled missing values using appropriate filling techniques.

### Task 02 – Duplicate Records

Detected and removed duplicate rows.

### Task 03 – Inconsistent Text Formatting

Standardized text values and formatting.

### Task 04 – Invalid Email Addresses

Identified and corrected invalid email formats.

### Task 05 – Invalid Phone Numbers

Cleaned and validated phone number entries.

### Task 06 – Date Format Issues

Converted inconsistent date values into a standard format.

### Task 07 – Category Standardization

Unified inconsistent category labels.

### Task 08 – Outliers

Detected salary outliers using the IQR method and capped extreme values.

### Task 09 – Range Violations

Fixed unrealistic values in age and price columns.

### Task 10 – Noisy Reviews

Removed meaningless review texts and standardized missing reviews.

### Task 11 – Boolean as String

Converted string representations of boolean values into proper boolean format.

### Task 12 – Data Type Issues

Corrected incorrect column data types.

### Task 13 – Range Validation

Validated and corrected values based on predefined ranges.

### Task 14 – Class Imbalance

Analyzed class distribution and balanced the target variable using Random Oversampling.

### Task 15 – Schema Validation

Removed invalid columns and verified the dataset schema.

---

## Files Included

* `data_cleaning.ipynb` → Complete solution notebook
* `dirty_dataset.csv` → Original dataset
* `cleaned_dataset.csv` → Final cleaned dataset
* `requirements.txt` → Required libraries
* `README.md` → Project documentation

---

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Open Jupyter Notebook:

```bash
jupyter lab
```

3. Open `data_cleaning.ipynb` and run all cells.

---

## Before vs After

### Before

* Missing values present
* Duplicate records existed
* Invalid formats and noisy data
* Outliers in salary column
* Incorrect data types
* Class imbalance
* Schema issues

### After

* Missing values handled
* Duplicates removed
* Formats standardized
* Outliers capped
* Correct data types assigned
* Balanced target classes
* Clean and validated dataset

---

## Author

Hasib
CSE, SUST
