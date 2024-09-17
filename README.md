# pwc_virtual_internship_hr
## Purpose and Goals of the Report
The primary goal of this report is to provide detailed insights into the organization’s HR metrics. These include the analysis of hiring trends, job level promotions, average time spent at different job levels, turnover performance, and employee distribution. The report also examines performance ratings segmented by gender, job level, and employee status (leaver vs. non-leaver).

## Key Datasets and Fields Used in the Analysis
### hr_manager table:
##### Employee ID: Unique identifier for each employee.
##### Gender: Employee’s gender (male/female).
##### Age Group: Age classification of employees.
##### Job Level: Current job level within the organization.
##### Fy20 Leaver: Indicator of whether the employee left during fiscal year 2020.
##### Department: The department where the employee works.
##### Promotion Date: The date of the employee's last promotion (if applicable).
##### Average Time in Job: The average time spent by the employee in their current job level.
# Types of Visualizations or Reports Included

## Total Employees by Gender:

#### 100% Stacked Bar Chart: This visualization shows the percentage of male and female hires across various job levels.
Breakdown of Job Level Promotions by Gender: Analyzes how promotions are distributed between male and female employees at each job level.
## Job Duration Overview:

#### Visualizations showcasing the average time spent in each job level, segmented by gender.
## Turnover Performance Analysis:

#### Line charts comparing the performance ratings of leavers versus non-leavers, categorized by gender.
## Employee Distribution:

#### Bar charts showing the distribution of employees by age group and department.
## Performance by Gender:
#### Comparative charts visualizing performance ratings (from 1 to 4) for both male and female employees across job levels.

## Data Sources:

#### Extracted from the HR management system,data set from pwc virtual internship

##  Data Transformations:

#### Data was cleaned to remove duplicates and handle missing values.
Calculated columns for metrics such as Average Time in Job and Turnover Ratings were added.
DAX measures were used to compute percentage breakdowns of employees by job level and performance ratings by gender.
