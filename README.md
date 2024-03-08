# Assessment 1: Dataset Preparation Report

## Introduction

This report addresses data quality issues at Revolution Consulting, a fictional IT consulting company, with the primary goal of preparing the data for subsequent analysis. This analysis specifically focuses on identifying employees at risk of leaving the organization, marking the first step in a data science project aimed at mitigating employee attrition.

In this report, I tackle various data quality problems including missing fields, incorrect data types, spelling errors, and outliers to ensure the dataset is clean and reliable for analysis. This falls under the data preparation and data exploration phase of the data science pipeline.

## Data Preparation Overview

### Process

#### 1. Loading the Data
- Loaded from a provided CSV file, specifying the 0th column as an index column.
- Displayed the first five rows to confirm correct loading.

#### 2. Data Curation
Detailed steps taken to prepare the dataset for analysis, including:

##### 2.1 EmployeeID Indexing
- Replaced index column with new random numbers for improved data handling.

##### 2.2 Age Column Handling
- Scanned for missing values, outliers, and typing errors; converted to integer type.

##### 2.3 Resigned Column Standardization
- Standardized values to 'Yes' and 'No', addressed missing values, and converted to binary.

##### 2.4 BusinessTravel Column Standardization
- Standardized by converting to uppercase and simplifying categories.

##### 2.5 BusinessUnit Column Correction
- Corrected misplaced values and standardized terms for consistency.

##### 2.6 EducationLevel Column Handling
- Handled missing values and converted float values to ordinal categories.

##### 2.7 Gender Column Standardization
- Standardized values, corrected spelling mistakes, and converted to categorical type.

##### 2.8 JobSatisfaction Column Handling
- Identified missing values, replaced with mode value, and converted to ordinal categories.

##### 2.9 MaritalStatus Column Standardization
- Standardized values and converted to a categorical data type.

##### 2.10 MonthlyIncome Column Handling
- Addressed missing values with the median value and converted to an integer type.

##### 2.11 Handling Other Columns
- Addressed missing values, outliers, and data types for various other columns as needed.

### Issues Discovered
Summary of discovered issues and their solutions, including data type corrections, handling of missing values, and standardization of values across columns.

## Data Exploration

### Overview
Exploration of selected features from the dataset to understand distributions and potential relationships. This includes visualizations like bar charts, box plots, histograms, and scatter plots for different variables.

### Process and Observations
Detailed process and observations from the exploration, such as:
- BusinessTravel distribution and its implications for workforce planning.
- - JobSatisfaction levels and their distribution across Monthly Income.
- The relationship between EducationLevel, MonthlyIncome, JobSatisfaction, WorkLifeBalance, Age, and YearsAtCompany.

### Plots
Discussion on the significance of observed patterns and how they could inform HR policies, compensation strategies, and employee retention efforts.

## Conclusion
In conclusion, this report has successfully addressed data quality issues at Revolution Consulting, paving the way for further analysis to identify employees at risk of leaving the organization. The data preparation phase involved standardizing data types, handling missing values, outliers, typing errors, inconsistent variables, and converting variables into appropriate formats for analysis. These steps ensured a clean, reliable dataset, setting the stage for effective data science tasks.

### Key observations:
- EducationLevel and MonthlyIncome: higher education levels tend to be associated with higher monthly income. Recognizing this relationship can assist in compensation and career development strategies.
- JobSatisfaction and WorkLifeBalance: improved work-life balance correlates with higher Job Satisfaction, emphasizing the importance of balancing employee satisfaction and work-life.
- Age and YearsAtCompany: older employees tend to have more experience at the company, offering insights into employee retention and career progression.
These observations will contribute to addressing attrition issues and aligning with the company's objectives.
