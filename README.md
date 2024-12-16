# Employee Data Analysis Project

## Project Overview
This project involves analyzing a dataset from ABC Company consisting of 458 rows and 9 columns. The goal is to generate a comprehensive report detailing insights about the employees across various teams. The project covers data preprocessing, detailed analysis, and graphical representation of findings.

## Dataset Description
The dataset includes the following columns:
- **Name:** Employee's name
- **Team:** The team to which the employee belongs
- **Number:** Employee's jersey or unique identifier number
- **Position:** Job role or position in the company
- **Age:** Employee's age
- **Height:** Employee's height (initial data corrected during preprocessing)
- **Weight:** Employee's weight
- **College:** The college from which the employee graduated (optional in analysis)
- **Salary:** Employee's salary

## Project Steps

### 1. Preprocessing
- Corrected inconsistencies in the **Height** column by replacing values with random numbers between 150 and 180.
- Addressed missing values in the **Salary** column by imputing the mean value.
- Removed any duplicate records to ensure data integrity.

### 2. Analysis Tasks
- **Team Distribution:** Calculated the number and percentage of employees in each team.
- **Position Analysis:** Segregated employees based on their positions and analyzed demand for specific roles.
- **Age Group Trends:** Identified predominant age groups among employees.
- **Salary Insights:** Determined which team and position incurred the highest salary expenditures.
- **Age and Salary Correlation:** Analyzed the relationship between age and salary using correlation and regression.

### 3. Visualizations
- Bar charts, pie charts, heatmaps and grouped bar plots were created to present key insights effectively.
- Scatter plots were used to visualize correlations between age and salary.

## Key Insights
- **Balanced Workforce:** Teams are evenly distributed, with certain teams slightly overrepresented.
- **Critical Roles:** SG and PF are the most common positions, reflecting their strategic importance.
- **Young Workforce:** The majority of employees fall in the 26-35 age group, followed by 18-25.
- **Salary Trends:** C and PG command the highest salaries, emphasizing their pivotal roles.
- **Performance Pay Balance:** While age correlates slightly with salary, exceptional young talent often earns competitive pay.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/AneetaAbhm/Employee_Data_Analysis.git
   cd Employee-Data-Analysis
2. Open the Jupyter Notebook file Employee-Analysis.ipynb for detailed code and analysis.

3. Ensure you have the following Python libraries installed:
   pandas,
   numpy,
   matplotlib,
   seaborn.
   
## Files in the Repository

    Dataset: myexcel.csv
    Jupyter Notebook: Employee-Analysis.ipynb
    README: Project overview and instructions.
## Conclusion

This project demonstrates the application of data preprocessing, analysis, and visualization techniques to derive actionable insights. The findings can assist in workforce planning, salary optimization, and identifying talent trends.
