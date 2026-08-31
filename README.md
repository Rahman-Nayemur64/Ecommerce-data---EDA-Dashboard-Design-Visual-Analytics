# Messy Ecommerce Data Analysis

A comprehensive data cleaning and analysis project for messy ecommerce sales data using Python, Pandas, and visualization libraries.

## Project Overview

This project demonstrates a complete data cleaning and exploratory data analysis (EDA) workflow on real-world messy ecommerce sales data. The notebook identifies and resolves common data quality issues including missing values, duplicates, inconsistent formatting, and data type mismatches.

## Files

- **Messy_Ecommerce_Data_Analysis.ipynb** - Main Jupyter notebook containing the complete analysis pipeline
- **messy_ecommerce_sales_data.csv** - Raw ecommerce sales dataset with data quality issues

## Project Structure

The analysis is organized into the following sections:

1. **Data Import & Exploration**
   - Load the dataset using Pandas
   - Display initial data samples
   - Overview of data shape and structure

2. **Data Assessment**
   - Total row and column count
   - Data types and info
   - Statistical summary (describe)

3. **Data Quality Analysis**
   - Missing value detection
   - Duplicate record identification and removal
   - Data completeness assessment

4. **Data Cleaning & Standardization**
   - Text column case normalization
   - Whitespace trimming (leading/trailing spaces)
   - Standardizing categorical values (e.g., payment methods)
   - Handling missing numeric values with mean imputation
   - Data type conversions for proper analysis

5. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Category and product insights
   - Customer and transaction patterns
   - Visualizations (charts and plots)

## Key Technologies

- **Python 3.x**
- **Pandas** - Data manipulation and cleaning
- **NumPy** - Numerical operations
- **Matplotlib** - Static visualizations
- **Seaborn** - Statistical data visualization
- **Jupyter Notebook** - Interactive development environment


## Data Cleaning Steps

The notebook performs the following cleaning operations:

- **Duplicates**: Removes exact duplicate records
- **Text Standardization**: Converts text columns to title case and removes leading/trailing whitespace
- **Categorical Normalization**: Standardizes values in categorical columns (e.g., payment methods)
- **Missing Values**: Imputes numeric missing values using mean values
- **Data Type Conversion**: Ensures columns have appropriate data types for analysis
- **NaN Handling**: Replaces string representations of NaN with proper null values

## Analysis Output

The notebook generates:
- Data quality metrics
- Missing value reports
- Duplicate count analysis
- Cleaned dataset overview
- Statistical summaries
- Visual representations (charts and plots)

## Notes

- The dataset contains common real-world data quality issues
- All transformations are performed on a copy to preserve the original data
- Mean imputation is used for missing numeric values; other approaches can be applied as needed
- Text columns include leading spaces that are handled during cleaning

