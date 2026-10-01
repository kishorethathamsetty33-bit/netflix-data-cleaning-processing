# netflix-data-cleaning-processing

# Netflix Data Cleaning & Preprocessing

## 📌 Project Overview

This project focuses on cleaning and preprocessing the "Netflix Movies and TV Shows dataset" using Python and Pandas. The goal is to transform raw data into a "clean, consistent, structured, and analysis-ready dataset".

This project was completed as part of a **Data Analyst Internship – Task 1: Data Cleaning and Preprocessing**.

The preprocessing workflow focuses on identifying and resolving common data quality issues, including **missing values, duplicate records, inconsistent data types, date-format issues, and numerical data quality problems**.

---

## 🎯 Objectives

- Inspect and understand the structure of the raw dataset
- Identify and remove duplicate records
- Detect and handle missing values
- Standardize date formats
- Validate numerical columns and identify potential outliers
- Handle identified numerical data quality issues
- Correct and validate appropriate data types
- Produce a clean and structured dataset ready for further analysis

---

## 📊 Dataset

**Dataset:** Netflix Movies and TV Shows

The dataset contains information about Netflix movies and TV shows, including:

- Show ID
- Type
- Title
- Director
- Country
- Date Added
- Release Year
- Rating
- Duration
- Listed In
- Description

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **Jupyter Notebook**

---

## 🔄 Data Cleaning Process

### 1. Data Loading

The raw Netflix dataset was loaded into Python using Pandas for inspection and preprocessing.

### 2. Data Inspection

The dataset structure and basic information were examined using:

- `head()`
- `tail()`
- `shape`
- `info()`

This helped understand the number of records, columns, and existing data types.

### 3. Duplicate Detection & Removal

Duplicate records were identified using Pandas and removed to prevent repeated records from affecting the quality of the dataset.

### 4. Date Format Standardization

The `date_added` column was converted from string format to **datetime format** to ensure consistent and reliable date handling.

### 5. Missing Value Analysis

Missing values were identified using:

```python
df.isnull().sum()

### 7. Handling Missing Values

The identified missing values were handled appropriately based on the respective columns and their data types.

### 8. Data Type Correction

After handling missing values, the release_year column was converted to integer format to ensure the correct data type for analysis.

### 9. Final Data Validation

The cleaned dataset was validated again to confirm that missing values, duplicate records, and data type issues were appropriately addressed.
