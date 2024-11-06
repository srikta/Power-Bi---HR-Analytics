HR Analytics Dashboard
This project is an interactive HR Analytics Dashboard created in Power BI to provide insights into employee attrition patterns. By analyzing demographics, job satisfaction, salary, and tenure, the dashboard helps HR managers make data-driven decisions to improve retention and workforce engagement.

Overview
The dashboard leverages a dataset of 1,480 employee records with 38 attributes, including key metrics like attrition, monthly income, job satisfaction, and years at the company. It features the following KPIs and visualizations:

KPIs
Employee Count: Total employees in the dataset.
Attrition Count: Number of employees who left.
Attrition Rate: Percentage of employee turnover.
Average Age: Mean age of employees.
Average Salary: Mean monthly income.
Average Tenure: Mean years at the company.
Visualizations
Attrition by Education: Turnover across education fields.
Attrition by Age: Rates by age range.
Job Satisfaction of Employees Who Left: Satisfaction ratings of leavers.
Attrition by Salary: Turnover by salary range, with higher rates in lower brackets.
Attrition by Years at Company: Turnover trends by tenure.
Attrition by Job Role: Roles with highest turnover, such as Laboratory Technician and Sales Executive.
Attrition by Gender: A pie chart comparing male and female attrition.
Technical Details
Data Cleaning: Removed duplicates, handled null values, and corrected spelling errors.
Column Transformations: Created a Count Attrition column to encode attrition as 1 (Yes) and 0 (No) for analysis. An Attrition Ratio measure was also added to calculate turnover rates.
Project Insights
This dashboard highlights key attrition factors like job roles, salary levels, age groups, and tenure. Insights help inform retention strategies and improve workforce engagement.

Setup
Clone the repository:
bash
Copy code
git clone https://github.com/srikta/Power-Bi---HR-Analytics.git
Open HR_Analytics_Dashboard.pbix in Power BI Desktop to explore.