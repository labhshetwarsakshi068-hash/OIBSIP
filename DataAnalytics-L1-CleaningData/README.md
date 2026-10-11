# Task 3: Data Cleaning

## Project Overview
This project focuses on cleaning a messy customer dataset using Python, Pandas, and NumPy.

## Dataset
The dataset contains 30 rows and 8 columns related to customer information, including age, gender, city, joining date, annual income, and purchase amount.

## Tools Used
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Data Cleaning Steps
1. Inspected the dataset and checked data types.
2. Identified missing values and duplicate records.
3. Converted numeric columns to appropriate data types.
4. Corrected invalid age values.
5. Standardized gender values and city names.
6. Converted joining dates to datetime format.
7. Handled missing numeric values using the median.
8. Handled missing gender values using the mode.
9. Handled missing or invalid dates using a median valid date.
10. Detected outliers using the IQR method.
11. Capped the extreme purchase amount at the upper IQR limit.
12. Saved the cleaned dataset as a separate CSV file.

## Results
- Original records: 30
- Cleaned records: 30
- Columns: 8
- Missing values after cleaning: 0
- Duplicate rows after cleaning: 0
- Invalid ages after cleaning: 0
- Negative purchase amounts after cleaning: 0

## Files
- `messy_customer_dataset.csv` — Original dataset
- `cleaned_customer_dataset.csv` — Cleaned dataset
- `data_cleaning.ipynb` — Jupyter Notebook with the cleaning process

## Conclusion
The dataset was cleaned and standardized to improve its quality and prepare it for further analysis.