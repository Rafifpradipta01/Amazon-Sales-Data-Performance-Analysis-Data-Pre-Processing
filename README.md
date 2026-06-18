# Amazon Sales Data Pre-Processing for Further Analysis

Performed end-to-end data pre-processing on Amazon sales data using Python to improve data quality, prepare features, and transform the dataset for further analysis and machine learning applications.

## Project Overview

This project focuses on preparing Amazon sales transaction data through data cleaning, data quality assessment, feature engineering, transformation, and categorical encoding.

Using Python and data preprocessing techniques, the project aims to produce a structured and analysis-ready dataset while identifying potential data quality issues and key transaction patterns.

## Business Questions

1. Are there any data quality issues that could affect analysis results?
2. How are sales transactions distributed across products and categories?
3. Are there outliers that require further investigation?
4. What preprocessing techniques are needed to prepare the dataset for future analysis and modeling?

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook
- GitHub

## Dataset Information

- Dataset: Amazon Sales 2025
- Source: Kaggle
- Total Records: 250
- Total Features: 11

### Dataset Features

- Order ID
- Date
- Product
- Category
- Price
- Quantity
- Total Sales
- Customer Name
- Customer Location
- Payment Method
- Status

## Data Preparation

The following preprocessing steps were performed:

### Data Quality Assessment

- Data type validation
- Missing value checking
- Duplicate checking
- Data consistency validation
- Outlier detection using IQR

### Data Cleaning

- Date column conversion from Object to DateTime
- Duplicate validation
- Missing value validation
- Text standardization for categorical columns
- Outlier flagging

### Data Manipulation

- Feature engineering (Sales Category)
- Data transformation:
  - Square Root Transformation
  - Log Transformation
  - Box-Cox Transformation
- Categorical encoding:
  - One Hot Encoding
  - Binary Encoding
  - Label Encoding
  - Frequency Encoding

## Key Findings

- No missing values or duplicate records were identified in the dataset.
- The Date column required conversion from Object to DateTime format before further analysis.
- Outliers were detected in the Total Sales column, but were retained because they represented valid high-value transactions.
- The dataset remained non-normally distributed even after applying Square Root, Log, and Box-Cox transformations.
- High-value transactions contributed significantly to overall sales performance.
- Electronics generated the largest contribution to total sales (53.29%) and increased to 63.14% among completed transactions.
- Only 35.20% of transactions were completed, while 64.80% remained non-completed.

## Business Recommendations

- Focus sales analysis on completed transactions to improve revenue measurement accuracy.
- Investigate the high proportion of non-completed transactions to identify potential operational issues.
- Monitor high-value transactions due to their significant contribution to total revenue.
- Retain outlier transactions when they represent legitimate business activity.
- Continue implementing data quality validation procedures before conducting advanced analytics.

## Project Workflow

1. Data Import
2. Data Exploration
3. Data Quality Assessment
4. Data Cleaning
5. Outlier Detection
6. Feature Engineering
7. Data Transformation
8. Categorical Encoding
9. Insight Generation

## Repository Structure

```text
amazon-sales-data-pre-processing
│
├── data/
├── notebook/
├── report/
└── README.md
```

## Author

Rafif Pradipta Bagaskara

Data Analyst Portfolio Project
