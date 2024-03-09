# HR Employee Attrition Analysis

This repository contains code and analysis for exploring employee attrition in an HR dataset. The goal is to understand the factors contributing to employee turnover and provide insights for organizations to improve retention strategies.

## Overview

The dataset contains information on various aspects of employees, such as demographics, job roles, satisfaction levels, and tenure. The primary focus is to analyze the relationship between these factors and employee attrition.

## Data Preprocessing

- **Handling Missing Values:** NaN values were either imputed or removed from the dataset to ensure data integrity.
- **Removing Redundant Columns:** Columns such as 'EmployeeCount', 'StandardHours', and 'Over18' were identified and dropped as they contained redundant information.
- **Encoding Categorical Variables:** Categorical variables were encoded using label encoding to convert them into numerical format for model training.
- **Scaling Numerical Features:** Numerical features were scaled using StandardScaler to ensure uniformity in their ranges.
- **Feature Engineering:** New features were created, such as 'YearsWithoutPromotion', by combining existing ones to extract more meaningful insights.

## Exploratory Data Analysis (EDA)

- **Visualizing Attrition Distribution:** A count plot was used to visualize the distribution of attrition in the dataset.
- **Correlation Analysis:** Heatmaps were generated to visualize the correlation between numerical features, helping identify potential relationships.
- **Boxplots and Violin Plots:** These plots were used to visualize the relationship between attrition and various factors like age, total working years, and number of companies worked.
- **Bar Plots:** Bar plots were utilized to analyze the distribution of categorical variables like gender, marital status, and education field.

## Model Building

- **Machine Learning Models:** Various machine learning models, such as logistic regression, decision trees, and random forests, were trained to predict employee attrition.
- **Model Evaluation:** Model performance was evaluated using metrics like accuracy, precision, recall, and F1-score to assess their effectiveness in predicting attrition.
- **Feature Importance:** Feature importance was analyzed to identify the key factors contributing to employee attrition.

## Insights and Recommendations

- **Identified Patterns:** Through analysis, certain patterns and trends were identified, such as the impact of overtime and job satisfaction on attrition rates.
- **Recommendations:** Based on the findings, recommendations were provided to organizations for improving retention strategies, such as addressing work-life balance issues and offering career advancement opportunities.

## Repository Structure

- **data/:** Contains the HR dataset used for analysis.
- **notebooks/:** Jupyter notebooks with code for data preprocessing, EDA, and model building.
- **visualizations/:** Visualizations generated during the analysis process.
- **README.md:** Overview of the project and instructions for running the code.

## Contributors
-Avinash Behera
