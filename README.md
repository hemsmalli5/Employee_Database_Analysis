# Employee_Database_Analysis

#Challenge Approach
 
Relational Employee Data Base tables (departments, employees, dept_manager, dept_emp, titles, and salaries) provide sufficient information required to perform the analysis. 
1. As a step 1, create all the above mentione tables into the data base and import data accordingly.
2. Join the tables accordingly to gather final output of how many employees will be retiring, their titles, and the employees' eligible for metorship program
	2a.Find Retirement info table to hold all retirement eligibility
	2b. Join 'departments' and 'dept_manager' tables
	2c. Create 'current_emp' tables from the 'retirmenet_info' and merged departments by performing left joint 
	2d. Get the employees count by department number, employee list with salary and gender, list of sales and developments
3. Perform inner join for 'current_emp' & 'titles' to create 'ret_title' table with the number of job titles retiening
4. With advance ROW_NUMBER function, create 'unique_title' table that provides employees' recent job titles.
5. Count the employee titles and create 'retiring_titles' 
6. From 'emplyees', 'dept_emp', and 'titles', filter the employees eligible for potential mentorship programs.

# Technical Analysis:
1. Number of Retiring Employees by Title are 54721
2. Number of Unique Titles retiring are 33118
	13651	Senior Engineer
	12872	Senior Staff
	2711	Engineer
	2022	Staff
	1609	Technique Leader
	251	Assistant Engineer
	2	Manager
3. Number of Employees eligibile for mentorship are 2382
