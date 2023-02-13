# Pewlett-Hackard-Analysis
## **Overview of Project**

The purpose of the project is to perform an analysis of employee data for Pewlett Hackard to gain more information on the number and title of employees nearning retirment and employees eligible for mentorship
based on their date of birth. A few steps were done to clean up data and work with only employees that are currently employed. Employees who already retired were excluded from the dataset.


## Results

- The data was performed based on several tables in an ER PostgreSQL database. The query used joins from departments, titles, employees, managers and salaries. See ERD diagram below.
	![alt text](https://github.com/mabulhassan/Pewlett-Hackard-Analysis/blob/main/Resources/ER_Diagram.png "Employee DB")
		   

### Retirement titles 

- The analysis performed on the data indicates there is a large number of engineers and senior employees nearing the age of retirement.
(48.6% of employees nearing retirement hold engineer title and 46.4% hold senior titles.(See pie chart and table below) 
	
	![alt text](https://github.com/mabulhassan/Pewlett-Hackard-Analysis/blob/main/Resources/EmployeeTitle.png "Unique Titles")
	![alt text](https://github.com/mabulhassan/Pewlett-Hackard-Analysis/blob/main/Resources/employee_retirement.png "Unique Titles table count")

### Mentorship Eligibility

- An analysis was performed based on employee seniority to determine their mentorship eligibility. Below table and chart shows that 46.4% of senior staff is eligible.

	![alt text](https://github.com/mabulhassan/Pewlett-Hackard-Analysis/blob/main/Resources/EmployeeEligibility.png "Mentorship Eligibility")
	
        ![alt text](https://github.com/mabulhassan/Pewlett-Hackard-Analysis/blob/main/Resources/mentorship_eligibility.png "Mentorship Eligibility table")
	
## Summary

- In Pewlett Hackard, the analysis of employee data shows that there is a large number of qualified and senior employees that are nearing retiriment age. The company needs to pay attention to 
the hiring of new employees and focus on training and mentorship.

## Resources

**Data Sources:** departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv

**Software:** PostgreSQL 11, pgAdmin 4, Python matpotlib 
