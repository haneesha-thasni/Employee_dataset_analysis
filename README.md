# Employee_dataset_analysis
![image](https://github.com/user-attachments/assets/92c26b0e-b638-469e-b90f-610291d7cfd4)

## Introduction:
This presentation explores an employee dataset to understand workforce trends, including demographics, job roles, and attrition. By analyzing this data, we aim to gain insights into factors influencing employee satisfaction and turnover. This will help HR departments make informed decisions to enhance employee retention and improve workplace satisfaction.

## Objective:
* Understand employee demographics and job characteristics.
* Analyze trends in attrition and employee satisfaction.
* Identify key factors impacting employee retention.
* Provide insights to support HR decision-making.

## Data Description Employee

• EmployeeID: Unique identifier for each employee.

• FirstName: The first name of the employee.

• LastName: The last name of the employee.

• Gender: The gender of the employee.

• Age: The age of the employee.

• BusinessTravel: The frequency of business travel for the employee.

• Department: The department in which the employee works.

• DistanceFromHome (KM): The distance between the employee's home and workplace in kilometers.

• State: The state in which the employee resides.

• Ethnicity: The ethnicity of the employee.

• MaritalStatus: The marital status of the employee.

• Salary: The annual salary of the employee.

• StockOptionLevel: The level of stock options granted to the employee.

• OverTime: Whether the employee works overtime (Yes/No).

• HireDate: The date the employee was hired.

• Attrition: Whether the employee has left the company (Yes/No).

• YearsAtCompany: The number of years the employee has been with the company.

• YearsInMostRecentRole: The number of years the employee has been in their most recent role.

• YearsSinceLastPromotion: The number of years since the employee's last promotion.

• YearsWithCurrManager: The number of years the employee has worked with their current manager.

## Information of the dataset

* Columns= 23
* Rows= 1470
* Cleaned data- no null values
* Data types
     - integer = 9
     - object = 14
* No duplicate values

## Questions :

 1) Which employees over the age of 35 have been promoted within the last 5 years, and what are their current job roles?
 2) filter the rows in a DataFrame to display only the employees in the Technology department who have a salary greater than 70,000?
 3) filter the rows in a DataFrame to display employees who are either in the Human Resources or Sales department and are older than 40?
 4) filter the employee dataset to select only the employees name and YearsAtCompany who are over 30 years old, work in the Sales department, and have a salary greater than 80,000?
 5) select employees who work in the 'Human Resources' department, are younger than 35, and travel frequently for business?
 6) select the first 11 rows of the DataFrame and all columns starting from 'EmployeeName' to the end?
 7) acessing all rows and columns from the EmployeeName to Department
 8) extract the names, states, marital status, distance from home, departments, and job roles of employees who are older than 45 and work overtime?
 9) select rows 100 to 500 and the columns from 'EmployeeName' to 'Education' in the DataFrame?
 10) filter the records of employees who have left the company and have spent 5 or more years with their current manager
 11) retrieve the first 101 rows and the first 10 columns from the DataFrame
 12) extract the data from specific columns (2nd, 6th, 10th, 11th, 12th, and 17th) for all rows in the DataFrame
 13) select all rows of the DataFrame but only display columns starting from the second column(EmployeeName) to the end?
 14) sort the DataFrame in ascending order based on the 'Salary' column
 15) sort a DataFrame to display the 'EmployeeName,' 'Department,' 'YearsAtCompany,' and 'YearsSinceLastPromotion' columns, sorting by 'YearsAtCompany' in descending order and 'YearsSinceLastPromotion' in ascending order?
 16) filter the DataFrame to show only the records of employees who work in the 'Technology' department.
 17) filter the DataFrame to display only the records of employees who identify as 'Black or African American.
 18) filter the DataFrame to show only the employees who are classified as 'Frequent Travellers' in the 'BusinessTravel' category
 19) filter the DataFrame to exclude employees from the states 'CA' and 'NY'.
 20) filter the DataFrame to exclude employees from the 'HR' and 'Sales' departments.
 21) filter the DataFrame to include only records where the 'HireMonth_Name' is either 'January', 'March', or 'April'.

## Requirements:
* Python 3.x
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## Analysis and Visualizations
Key visualizations include:
* Age Distribution: Distribution of employee ages.
* Gender Distribution by Department: Gender diversity across departments.
* Attrition by Business Travel Frequency: Attrition rates based on travel frequency.
* Salary vs. Years at Company: Relationship between salary and tenure.
* Distribution of years at the company by marital status.
* Stock option level vs. attrition.
* Distance from home vs. attrition.

## Suggestions:
1.Flexible Work Arrangements: To reduce attrition, especially among employees with high business travel frequency.

2.Diversity Initiatives: Establish programs for departments with low gender diversity to encourage inclusive hiring.

3.Retention Programs: Focus on employees with less tenure, as they may benefit from mentorship or development programs.

4.Salary Adjustments: Use insights from salary distributions to ensure competitive compensation across roles and tenures.

## Conclusion
* The analysis of the employee dataset reveals key trends and potential areas for improvement in the organization’s HR policies.
* Recommendations focus on improving retention, promoting diversity, and creating a supportive work environment for employees.
* Future analysis could include predictive modeling to anticipate attrition and identify high-risk employees for early intervention.
