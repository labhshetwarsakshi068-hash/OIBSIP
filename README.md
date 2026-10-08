# EDA on Retail Sales Data

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to identify important patterns and insights related to sales performance, customer behavior, product categories, and transaction values.

The analysis helps understand sales trends and provides actionable business recommendations based on the data.

## Objective

The main objectives of this project are:

- Understand the structure and characteristics of the retail sales dataset.
- Analyze monthly and quarterly sales trends.
- Study sales based on gender and age groups.
- Analyze sales performance across product categories.
- Identify the highest-value transactions.
- Study relationships between numerical variables using correlation analysis.
- Generate useful business insights and recommendations.

## Dataset

The dataset contains **1,000 retail transactions** and **9 original columns**:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

Additional columns such as Month, Month Name, Quarter, and Age Group were created during the analysis.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Quality Check

The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Dataset dimensions

Results:

- Rows: 1,000
- Columns: 9
- Missing values: 0
- Duplicate rows: 0

The Date column was converted into datetime format for time-based analysis.

## Analysis Performed

### 1. Descriptive Statistics

Mean, median, mode, and standard deviation were calculated for:

- Age
- Quantity
- Price per Unit
- Total Amount

### 2. Monthly Sales Trend

Monthly sales were analyzed to identify high and low performing months.

May recorded the highest monthly sales, while September recorded the lowest monthly sales.

### 3. Quarterly Sales Trend

Quarterly sales analysis showed that Q4 recorded the highest sales, while Q3 recorded the lowest sales.

### 4. Gender Analysis

Female customers generated slightly higher total sales than male customers.

### 5. Age Group Analysis

The 46-55 age group generated the highest total sales.

An additional analysis of average transaction value showed that younger customers had relatively higher average transaction amounts.

### 6. Product Category Analysis

Sales by product category showed:

- Electronics: ₹156,905
- Clothing: ₹155,580
- Beauty: ₹143,515

Electronics generated the highest total sales.

### 7. Top 10 Highest-Value Transactions

The analysis identified the top 10 transactions based on Total Amount.

The highest transaction value was ₹2,000.

**Note:** The dataset does not contain a Product Name column. Therefore, the analysis identifies the top 10 highest-value transactions rather than specific best-selling product names.

### 8. Correlation Analysis

The correlation heatmap showed:

- Price per Unit and Total Amount: strong positive correlation (0.85)
- Quantity and Total Amount: moderate positive correlation (0.37)
- Age and Total Amount: very weak correlation

### 9. Additional Visualization

Average spending was analyzed by age group.

Customers below 18 showed the highest average transaction amount, while the average transaction amount generally decreased across older age groups.

## Key Findings

- Q4 was the strongest quarter in terms of sales.
- May recorded the highest monthly sales.
- Electronics was the highest-selling product category.
- Female customers generated slightly higher total sales.
- The 46-55 age group generated the highest overall sales.
- Price per Unit had a strong positive relationship with Total Amount.
- Younger customers showed higher average transaction values.

## Business Recommendations

1. **Focus on high-performing periods:** Increase inventory, promotions, and marketing activities during high-sales periods such as Q4 and May.

2. **Strengthen Electronics and Clothing categories:** Maintain sufficient inventory and use targeted promotions for high-performing categories.

3. **Use age-based marketing strategies:** Target the 46-55 age group for overall sales growth while designing suitable high-value offers for younger customers.

## Conclusion

The exploratory data analysis provided useful insights into retail sales performance and customer behavior. The analysis identified important trends across time, gender, age groups, and product categories. These findings can help businesses improve inventory planning, marketing strategies, and customer targeting.