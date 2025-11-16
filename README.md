# Data Analyst Internship -- Task 1

## Data Cleaning & Preprocessing

This repository contains the completed **Task 1: Data Cleaning &
Preprocessing** for the Elevate Labs Data Analyst Internship.

------------------------------------------------------------------------

## 📌 Objective

Clean and prepare a raw dataset by fixing issues such as: - Missing
values\
- Duplicates\
- Inconsistent formatting\
- Incorrect data types

Tools Used: **Python (Pandas)**

------------------------------------------------------------------------

## 🛠️ Steps Performed During Cleaning

### 1. Date Formatting

-   Converted the `Date` column to proper `datetime` format using
    Pandas.

### 2. Standardized Text Columns

Standardized text formatting for: - `Month`\
- `Age_Group`\
- `Customer_Gender`\
- `Country`\
- `State`\
- `Product_Category`\
All values were trimmed and converted to **Title Case**.

### 3. Duplicate Handling

-   Checked for duplicates using `df.duplicated()`\
-   **No duplicate rows were found**.

### 4. Data Type Fixes

Converted the following columns to numeric:\
- `Order_Quantity`\
- `Profit`\
- `Cost`\
- `Revenue`\
- `Year`\
- `Customer_Age`

### 5. Final Output

A cleaned dataset named **cleaned_sales_data.csv** was produced and is
ready for analysis/visualization.

------------------------------------------------------------------------

## 📂 Files in This Repository

-   `cleaned_sales_data.csv` -- Final cleaned dataset\
-   `README.md` -- Documentation for Task 1

------------------------------------------------------------------------

## 📘 How to Use

You can load the cleaned dataset using:

``` python
import pandas as pd
df = pd.read_csv("cleaned_sales_data.csv")
df.head()
```

------------------------------------------------------------------------

## 📞 Contact

If you need help or further improvements, feel free to reach out.
