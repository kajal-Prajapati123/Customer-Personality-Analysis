# Customer Personality Analysis - Data Cleaning Task

## ✅ Internship Task: Data Cleaning & Preparation Summary

As part of the data cleaning task, I performed the following steps using Python and Pandas:

1. Read the raw dataset into a Pandas DataFrame.
2. Checked the shape of the dataset to understand the number of rows and columns.
3. Identified and removed null values using `df.isnull().sum()` and `dropna()`.
4. Converted the `date` column from object to datetime format using `pd.to_datetime()`.
5. Handled invalid dates by coercing errors and dropping rows where conversion failed.
6. Checked and removed duplicate rows using `df.duplicated().sum()` and `drop_duplicates()`.
7. Standardized text values (e.g., gender, marital status) to lowercase using `.str.strip().str.lower()`.
8. Renamed all column headers to be clean and uniform (all lowercase and no spaces) using:
   ```python
   df.columns = df.columns.str.strip().str.lower().str.replace(' ', '_')
9. Saved the cleaned dataset into a new CSV file inside a new directory called Customer Personality Analysis.


10. Also, saved the code script used for cleaning in the same directory.
  
