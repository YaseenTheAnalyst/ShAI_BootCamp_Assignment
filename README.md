# Project Title: Salary Data Exploration

## Introduction
This project involves exploring a salary dataset, aiming to gain insights into salary distributions, departmental assignments, and correlations between different pay components.

## Dataset Overview
The dataset, sourced from 'Salaries.csv,' contains information on salaries, including details such as BasePay, OvertimePay, Benefits, and TotalPay. The exploration involves understanding its structure, handling missing values, and cleaning redundant information.

## Data Cleaning and Preprocessing
The initial steps involve examining column names, dimensions, and identifying and handling missing or negative values. Rows with negative 'TotalPay' and 'BasePay' are removed, and missing values in the 'Benefits' column are imputed with zeros.

## Job Title to Department Assignment
To enhance analysis, job titles are categorized into departments based on common keywords. This involves assigning a default department and then specifying departments using predefined categories.

## Exploratory Data Analysis
The project explores the distribution of key salary components (BasePay, OvertimePay, Benefits, TotalPay) using histograms. Additionally, it visualizes the distribution of job titles across different departments through bar charts and pie charts.

## Departmental Salary Analysis
The analysis extends to department-level insights, showcasing the distribution of departments and calculating summary statistics (max, min, mean, median) for 'BasePay' and 'TotalPay.' The average 'BasePay' for each department is visualized using a horizontal bar chart.

## Correlation Analysis
The correlation matrix of numerical columns is calculated and visualized through a heatmap, providing insights into relationships between different pay components.

## Key Insights
- Job Title Variations: The dataset highlights variations in job titles, emphasizing the need for predefined categories during data collection for better consistency.
- Departments with Highest Average Salary: Certain departments exhibit the highest average salary, offering valuable insights for further analysis and decision-making.
- TotalPay Mode and Zero Values: Analysis reveals a significant number of entries with a 'TotalPay' value of 0, prompting further investigation to understand and address this phenomenon.
- Redundant Column: Redundant columns are identified, suggesting potential removal or consolidation for simplicity.

**This project provides a comprehensive exploration of salary data, offering valuable insights for further analysis and decision-making.**
