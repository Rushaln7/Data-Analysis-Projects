# Data Cleaning and Exploratory Data Analysis (EDA) on Employee Layoffs Dataset Using MySQL

## Overview

This project involves data cleaning and exploratory data analysis (EDA) on a dataset related to Employee Layoffs 2023. The dataset is in CSV format and the analysis was performed using SQL. The goal of this project is to preprocess the data to ensure it is clean and ready for further analysis.

## Steps involved in Data Cleaning

### 1. Remove Duplicates
- **Description**: Duplicate rows in the dataset were identified and removed to ensure that each entry is unique. This step is crucial for maintaining the integrity of the data.

### 2. Standardize the Data
- **Description**: The data was standardized to ensure consistency across all columns. This includes converting text to a uniform case, formatting dates, and standardizing numerical values.

### 3. Handle Null or Blank Values
- **Description**: Null or blank values in the dataset were addressed. This step involved either imputing missing values or removing rows/columns with excessive missing data.

### 4. Remove Unnecessary Columns or Rows
- **Description**: Columns and rows that were not relevant to the analysis were removed to streamline the dataset. This step helps in reducing the complexity of the dataset and focusing on the most important information.

## Tools Used

- MySQL
  
## Dataset

- **File Name**: Employee Layoffs 2023
- **Description**: This dataset contains information on employee layoffs from all around the world that occurred till 2023. It includes various attributes such as Company name, Location, Industry, Total Laid off, percentage_laid_off, date, stage, country, funds_raised_millions.

- **File Name**: Employee Layoffs Data Cleaned
- **Description**: This dataset contains the cleaned up information of the dataset.

- **File Name**: EDA on Layoffs.csv
- **Description**: This dataset show the company which had made the highest number of layoffs till 2023.
