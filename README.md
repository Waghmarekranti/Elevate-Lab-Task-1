# Elevate-Lab-Task-1
Sales Data Cleaning and Preprocessing: 

1. Data Cleaning and Preparation – Description
Inspect the Dataset
Begin by reviewing the dataset to understand its structure, column names, data types, and potential issues.
Identify missing values, duplicate rows, inconsistent entries, and incorrect data types.

2. Handle Missing Values
Detect null or empty entries in the dataset.
Decide whether to drop rows with missing values or fill them using appropriate methods:

Numeric columns → fill with mean or median.

Categorical columns → fill with mode or a placeholder like “Unknown”.

3.Remove Duplicates

Identify duplicate rows in the dataset.

Remove duplicates to avoid skewing analysis, keeping only one instance of repeated records.

4.Standardize Text Values

Ensure uniformity in categorical data such as gender, country, or product names.

Correct inconsistent spellings, capitalization, or formatting.

Trim unnecessary spaces and unify entries (e.g., “Male” instead of “male” or “M”).

5.Convert Date Formats

Standardize all date columns to a consistent format (e.g., dd-mm-yyyy).

Convert text dates to proper date types to allow proper sorting, filtering, and analysis.

Rename Columns

Clean column headers for consistency and readability.

Use lowercase letters and replace spaces with underscores for easier access in analysis tools.

5.Check and Fix Data Types

Ensure numeric columns are stored as integers or floats.

Ensure dates are stored as date/time types.

Correct any columns that are stored in incorrect formats (e.g., numeric data stored as text).

6.Final Verification

After all cleaning steps, re-check for any remaining missing values, duplicates, or inconsistent entries.

Confirm all columns have the correct data type and consistent formatting.

7.Document Changes

Prepare a short summary of all modifications made to the dataset, including how missing values were handled, duplicates removed, columns renamed, and formats standardized.

Key Points / Best Practices:

Always inspect before cleaning.

Handle missing values thoughtfully; dropping isn’t always best.

Standardize text and date formats to avoid errors in analysis.

Remove duplicates to maintain data accuracy.

Keep a log of all cleaning steps for transparency and reproducibility.
