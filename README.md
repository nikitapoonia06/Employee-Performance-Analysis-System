# Employee Performance Analysis System

## Project Overview

This project analyzes employee performance data to identify high-performing employees, evaluate departmental performance, and understand factors influencing employee productivity. The analysis includes data cleaning, exploratory data analysis (EDA), statistical summaries, correlation analysis, and data visualization to support HR decision-making.

## Business Problem

Human Resources (HR) departments need data-driven insights to:

- Identify top performers for recognition and promotion
- Monitor departmental performance
- Understand factors affecting employee performance
- Improve workforce productivity and retention
- Support performance-based decision-making

## Dataset

The dataset contains **1000 employee records** with the following attributes:

- Employee ID
- Name
- Age
- Gender
- Department
- Salary
- Joining Date
- Performance Score
- Experience
- Status
- Location
- Session

## Tools & Technologies

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Workflow

### 1. Data Loading & Exploration

- Loaded employee dataset
- Displayed sample records
- Examined dataset structure
- Checked data types
- Identified missing values
- Generated descriptive statistics

### 2. Data Cleaning

- Identified missing values in the Performance Score column
- Replaced missing values using median imputation
- Checked for duplicate records
- Converted Joining Date to datetime format

### 3. Performance Analysis

#### Average Performance by Department

Compared average employee performance across departments.

#### Top 10 Performers

Identified employees with the highest performance scores.

#### Performance Distribution

Analyzed overall employee performance levels.

#### Salary vs Performance

Examined the relationship between salary and performance.

#### Experience vs Performance

Studied whether employee experience impacts performance.

### 4. Data Visualization

- Performance Distribution Histogram
- Department-wise Performance Bar Chart
- Salary vs Performance Scatter Plot
- Performance by Experience Line Chart

## Key Findings

- The dataset contains **1000 employee records**.
- IT recorded the highest average performance score (**2.99**).
- Sales and HR showed similar performance levels.
- The average employee performance score was **2.96/5**.
- Salary and performance showed almost no correlation (**0.0017**).
- Experience and performance also showed no meaningful correlation (**-0.007**).
- Top-performing employees achieved a performance score of **5** and were distributed across multiple departments.

## Recommendations

- Recognize and reward high-performing employees.
- Monitor departmental performance regularly.
- Evaluate employees based on performance metrics rather than salary or experience alone.
- Improve performance data collection processes to reduce missing values.
- Implement periodic performance reviews and targeted training programs.

## Conclusion

The analysis revealed relatively consistent performance levels across departments. No significant relationship was found between employee performance, salary, or experience. The findings highlight the importance of performance-based evaluation and continuous monitoring to support effective HR decision-making.

## Project Structure

```text
Employee_Performance_Analysis/
¦
+-- Employee_Performance_Analysis.ipynb
+-- employee_data.csv
+-- README.md
+-- images
```

## How to Run

1. Clone the repository

```bash
git clone <repository-url>
```

2. Navigate to the project folder

```bash
cd Employee_Performance_Analysis
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Open:

```text
Employee_Performance_Analysis.ipynb
```

5. Run all cells sequentially.

## Author

Nikita Poonia
