# ☕ E-Commerce Data Cleaning & Wrangling Pipeline

## 📊 Python for Data Analysis | Week 4 Project

## 📌 Project Overview

In real-world data science, datasets are rarely "clean." This project demonstrates a robust data cleaning pipeline built to handle a messy dataset from a fictional retail chain. The goal was to transform raw, inconsistent data into a structured format ready for Exploratory Data Analysis (EDA) and machine learning.

The pipeline addresses common "real-world" issues such as inconsistent date formats, mixed-type currency strings, missing values, and duplicate entries.

## 🛠️ Skills & Tools

This project focuses heavily on the **Data Preparation** phase of the data science lifecycle. Key concepts implemented include:

- **Data Audit & Inspection:** Identifying structural issues and missingness using `.info()`, `.describe()`, and `.isna()`.
- **Handling Missing Values:** Using `dropna()` for critical features (dates) and `fillna()` with median/logical defaults for non-critical features.
- **Type Casting & Standardization:** \* Converting currency strings to floats using `pd.to_numeric` with `errors='coerce'`.
- Parsing irregular date formats using `pd.to_datetime`.
- Normalizing text data using `.str` methods (strip, title, replace).

- **Deduplication:** Identifying and removing exact duplicates to prevent skewed analysis.
- **Feature Engineering:**
- Creating derived columns (Total Revenue).
- **Binning:** Using `pd.cut` to segment orders into 'Budget', 'Mid-Range', and 'Premium' categories.
- **Time Features:** Extracting day names and weekend flags using `.dt` accessors.

## 📊 Key Transformations

| Feature           | Issue                                         | Solution                         |
| ----------------- | --------------------------------------------- | -------------------------------- |
| **Order Date**    | Mixed strings like 'Jan 5th' and '2023-01-01' | `pd.to_datetime` conversion      |
| **Item Price**    | Strings containing '$' and commas             | Regex replacement + `to_numeric` |
| **Customer Name** | Inconsistent casing and white spaces          | `.str.strip().str.title()`       |
| **Revenue**       | Column did not exist                          | `price * quantity` calculation   |
| **Order Segment** | Need for high-level categorization            | `pd.cut` binning                 |

## 💡 Key Takeaways

1. **Inspect First:** Always check data types before performing arithmetic operations.
2. **Handle Junk Data:** Using `errors='coerce'` ensures the script doesn't crash when encountering unexpected text in numeric columns.
3. **Preserve Raw Data:** The pipeline always reads from a raw file and saves to a _new_ file, ensuring data lineage is maintained.
