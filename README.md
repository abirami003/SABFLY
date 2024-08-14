# Employee Data Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results/findings)
- [Recommendations](#recommendations)

### Project Overview

This data analysis project aims to provide insights into the factors influencing employee status and satisfaction within the organization. By analyzing trends across departments, salary, bonuses, country, gender, and age, we seek to identify patterns, make data-driven recommendations, and enhance the strategic decision-making of HR to improve employee retention

### Data Sources

Employee Data: The primary dataset used for this analysis is the "Employee Sample Data .xlsx" file, containing detailed information about each employee and their status

### Tools

- Excel - Database Manageemnt[Download Here](https://microsoft.com)
- Power Query Editor - Data Cleaning and Analysis
- Power BI Desktop - Creating Reports [Download Here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

### Data Cleaning/Preparation

In the initial data preparation, I performed the following tasks
1. Data Loading and Inspection
2. Handling missing values
3. Data cleaning and formatting

### Data Analysis

Some interesting code/feature worked with:

```dax
TOTAL EMPLOYEES = COUNT('Employee Details'[EMPLOYEES])
```
```dax
TOTAL ANNUAL SALARY = SUM('Salary Details'[ANNUAL SALARY])
```

### Results/Findings

The analysis results are summarized as follows:
- The IT department has more employees than other departments in the company
- Most of the Employees are from United States
- There are more females employees than males employees in the company

 ### Recommendations

- Address high turnover departments with targeted strategies
- Improve engagement for groups with higher turnover
- Regularly update predictive models

🙂


