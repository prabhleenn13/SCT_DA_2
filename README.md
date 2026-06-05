# SCT_DA_2
Data Cleaning Project using Python and Pandas
# Global Superstore Data Cleaning Project

## Overview

This project focuses on data cleaning and preprocessing using Python and Pandas. The Global Superstore dataset was loaded into a Jupyter Notebook environment and prepared for further analysis by addressing data quality issues such as missing values and incorrect data types.

Data cleaning is a critical step in the analytics workflow because accurate insights depend on clean, reliable, and well-structured data.

---

## Project Objectives

* Load and explore a real-world retail dataset using Pandas.
* Identify missing values and assess data quality.
* Handle missing data appropriately.
* Check for and remove duplicate records.
* Convert date columns to proper datetime format.
* Export the cleaned dataset for future analysis and visualization.

---

## Dataset Information

**Dataset:** Global Superstore

**Records:** 51,290

**Columns:** 24

The dataset contains information on customer orders, products, sales, profits, shipping details, and geographical markets across multiple countries.

---

## Tools & Technologies

* Python
* Pandas
* Jupyter Notebook

---

## Data Cleaning Process

### 1. Data Loading

The dataset was imported into a Jupyter Notebook using Pandas and inspected to understand its structure and data types.

### 2. Missing Value Analysis

A missing value audit was performed using:

```python
df.isnull().sum()
```

The analysis revealed missing values in the **Postal Code** column.

### 3. Missing Value Handling

Missing values in the Postal Code field were handled to improve dataset completeness and consistency.

### 4. Duplicate Record Validation

Duplicate records were checked using:

```python
df.duplicated().sum()
```

Result:

* Duplicate Rows Found: 0

No duplicate records were identified in the dataset.

### 5. Data Type Conversion

The following columns were converted from string (object) format to datetime format:

* Order Date
* Ship Date

This enables time-series analysis and date-based calculations in future projects.

### 6. Exporting Cleaned Data

The cleaned dataset was exported as:

```text
Global_Superstore_Cleaned.csv
```

---

## Key Outcomes

* Successfully loaded and explored a dataset containing over 51,000 records.
* Identified and handled missing values.
* Validated dataset integrity by checking for duplicate records.
* Standardized date fields using datetime conversion.
* Generated a clean dataset ready for exploratory data analysis, dashboard creation, and business intelligence applications.

---

## Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Pandas DataFrame Operations
* Missing Value Treatment
* Data Type Conversion
* Data Quality Assessment
* Jupyter Notebook Workflow
* CSV File Handling

---

## Future Enhancements

Potential next steps include:

* Exploratory Data Analysis (EDA)
* Sales Performance Analysis
* Customer Segmentation
* Regional Sales Insights
* Interactive Power BI Dashboard Development
* SQL-Based Business Analytics

---

## Project Author

Prabhleen Bains

Economics with Data Science & AI | Aspiring Data Analyst

---
