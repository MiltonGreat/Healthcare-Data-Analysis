# Healthcare-Data-Analysis

## Overview

This project analyzes healthcare data to uncover trends, patterns, and insights that can help stakeholders (e.g., hospitals, insurance providers, policymakers) make informed decisions. The dataset includes information about patient demographics, medical conditions, admission and discharge dates, billing amounts, and test results. The project is divided into two main phases: data cleaning and data analysis.

### Project Goals

The primary goals of this project are:

- **Understand Patient Demographics**: Analyze the distribution of patients by age, gender, and other factors.
- **Explore Medical Conditions**: Identify the most common medical conditions and their characteristics (e.g., billing amounts, length of stay).
- **Analyze Healthcare Costs**: Investigate how billing amounts vary by medical condition, insurance provider, and other factors.
- **Evaluate Hospital Performance**: Examine trends in admissions, length of stay, and test results to assess hospital efficiency and patient outcomes.
- **Visualize Trends**: Use data visualizations to communicate insights effectively.

### Dataset

The dataset contains the following columns:

- **Name**: Patient name.
- **Age**: Patient age at the time of admission.
- **Gender**: Patient gender (Male or Female).
- **Blood Type**: Patient blood type (e.g., A+, O-).
- **Medical Condition**: Primary medical condition or diagnosis (e.g., Diabetes, Hypertension).
- **Date of Admission**: Date of admission to the healthcare facility.
- **Doctor**: Name of the doctor responsible for the patient's care.
- **Hospital**: Healthcare facility or hospital where the patient was admitted.
- **Insurance Provider**: Patient's insurance provider (e.g., Aetna, Blue Cross).
- **Billing Amount**: Amount billed for healthcare services.
- **Room Number**: Room number where the patient was accommodated.
- **Admission Type**: Type of admission (Emergency, Elective, or Urgent).
- **Discharge Date**: Date of discharge from the healthcare facility.
- **Medication**: Medication prescribed or administered during admission.
- **Test Results**: Results of medical tests (Normal, Abnormal, or Inconclusive).

### Methodology

The project is divided into two main phases:

1. **Data Cleaning**

- **Standardized Text Columns**: Ensured consistency in categorical data (e.g., Gender, Blood Type, Medical Condition).
- **Handled Negative Billing Amounts**: Replaced negative billing amounts with the median value.
- **Removed Duplicates**: Eliminated duplicate rows to ensure data integrity.
- **Validated Categorical Columns**: Confirmed that categorical variables contained only valid categories.
- **Converted Date Columns**: Converted Date of Admission and Discharge Date to datetime format.
- **Checked for Inconsistent Data**: Identified and handled invalid discharge dates and unrealistic ages.

2. **Data Analysis**

- **Understanding Distributions**: Visualized the distribution of key variables (e.g., Age, Billing Amount, Length of Stay).
- **Exploring Relationships**: Analyzed relationships between variables (e.g., Billing Amount vs. Length of Stay, Test Results by Medical Condition).
- **Analyzing Patterns Over Time**: Examined trends in admissions by month or season.
- **Exploring Categorical Relationships**: Investigated how categorical variables (e.g., Gender, Insurance Provider) relate to other variables.
- **Correlation Analysis**: Calculated correlations between numerical variables to identify strong relationships.

### Key Insights

The analysis revealed several important insights:

- **Patient Demographics**: The patient population is mostly middle-aged, with a median age of 52 years.
- **Billing Amounts**: Billing amounts vary significantly, with an average of 25,594.52andarangefrom25,594.52andarangefrom9.24 to $52,764.28.
- **Length of Stay**: The median length of stay is approximately 16 days, with significant variability across medical conditions and admission types.
- **Admission Trends**: Admissions are evenly distributed over time, with no strong seasonal patterns observed.
- **Test Results**: Test results vary by medical condition and gender, with some conditions (e.g., Cancer) having a higher proportion of abnormal results.

### Source

https://www.kaggle.com/datasets/prasad22/healthcare-dataset/data
