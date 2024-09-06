# HR Analytics Dashboard

This repository provides insights from the **HR Analytics** dataset. The dataset includes employee information such as their roles, performance, and satisfaction levels, along with factors contributing to employee attrition.

## Dataset Overview

The dataset consists of 41 columns, capturing various aspects of employee data:

- **Attrition**: Whether the employee has left the company.
- **Business Travel**: Frequency of business travel (e.g., Travel Rarely, Travel Frequently).
- **Age Group**: Age categories for employees (e.g., 25 - 34, 35 - 44).
- **Attrition Label**: Indicates whether the employee is a Current Employee or Ex-Employee.
- **Department**: The department to which the employee belongs (e.g., Sales, R&D).
- **Education Field**: The area of the employee's education (e.g., Life Sciences, Medical).
- **Job Role**: The specific job role held by the employee (e.g., Sales Executive, Research Scientist).
- **Performance Rating**: Rating scale reflecting the employee’s performance.
- **Work-Life Balance**: Work-life balance rating (from 1 to 4).

## Key Insights

1. **Attrition Analysis**:
   - Examines attrition status to identify the factors behind employees leaving the organization.
   - Insight: Employees who travel frequently may experience higher attrition rates.

2. **Performance & Satisfaction**:
   - Employee satisfaction levels and performance ratings, covering areas such as:
     - Relationship Satisfaction
     - Work-Life Balance
     - Job Satisfaction
   - These factors help understand employee engagement and retention.

3. **Years at the Company**:
   - Tracks how long employees have been with the company and their current manager.
   - Insight: Employees with longer tenure tend to have higher job satisfaction and performance ratings.

4. **Business Travel**:
   - Analyzes the frequency of business travel and its impact on job satisfaction and attrition.

## Data Columns Overview

| Column Name                | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `Attrition`                | Whether the employee left the company (Yes/No)                               |
| `Business Travel`          | Frequency of travel (e.g., Rarely, Frequently)                               |
| `CF_age band`              | Age group of the employee                                                    |
| `CF_attrition label`       | Attrition status (Current/Ex-Employee)                                       |
| `Department`               | Employee’s department (e.g., Sales, R&D)                                     |
| `Education Field`          | Field of education                                                          |
| `Job Role`                 | Specific role held (e.g., Sales Executive, Research Scientist)               |
| `Performance Rating`       | Employee's performance rating                                                |
| `Work Life Balance`        | Rating for work-life balance                                                 |
| `Years At Company`         | Number of years at the company                                               |
| `Years In Current Role`    | Duration in the current role                                                 |
| `Years With Curr Manager`  | Time spent with the current manager                                          |

## Visualizations

This dataset can be visualized through Power BI dashboards to provide insights into:

- **Attrition Trends**: Identifying the key factors contributing to employee turnover.
- **Performance Metrics**: Understanding the relationships between work-life balance, satisfaction, and performance.
- **Employee Demographics**: Analyzing the impact of demographics such as age, gender, and education on outcomes.

## Conclusion

The analysis of this HR dataset enables companies to uncover patterns that influence employee satisfaction, retention, and performance. With the help of visual tools like Power BI, actionable insights can be derived for HR management.

---

### Files Included:

- `HR Data.xlsx`: The original dataset containing employee information.
- `HR_Analyst_Dashboard.pbix`: Power BI dashboard file for visual insights.
