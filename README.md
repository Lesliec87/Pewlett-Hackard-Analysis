# Pewlett-Hackard-Analysis
In this analysis we worked with Bobby, an HR Analyst that was tasked to perform employee research for Pewlett Hackard. Pewlett Hackard was looking into many employees that will be retiring soon, they are looking into offering retirement packages to those who meet certain criteria and also which positions will need to be filled in the near future. 

We assisted Bobby build an employee database with SQL by applying data modeling, engineering and analysis skills. We aquired the employee data from CSV files since the company was only working with Excel and VBA, now they have updated their methods to use SQL

We also worked on two assigments to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

## Results:   

### Employee Database performed [Employee_Database_challenge](https://github.com/Lesliec87/Pewlett-Hackard-Analysis/blob/main/Queries/Employee_Database_challenge.sql)

- We found that their is a very high amount of retiring employees by titles: 
  - 25,916 Senior Engineers
  - 24,926 Senior Staff
  - 9,285 Enrineers
  - 7,636 Staff
  - 3603 Technique Leaders 
  - 1090 Assistant 
  - 2 Managers
- The total eligible for mentorship eligibility are 1,549 employees 

![Retiring Titles](https://github.com/Lesliec87/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.png)


## Summary: 

1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?
  - There will be a total of 72458 roles to be filled.
   
  - To find the count for the roles I used the "COUNT()" function on the "emp_no" column in "unique_titles" table:

### Retiring Count
![Retiring Count](https://github.com/Lesliec87/Pewlett-Hackard-Analysis/blob/main/Data/retirement%20count.png)

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
  - There are not enough qualified employees to mentor since the amount of retirement roles are extrememly high compared to eligible mentors: 
 
  - To find the count for the employees eligible to mentor I used the "COUNT()" function on the "emp_no" column in "mentorship_eligibility" table: 

### Mentorship Count
![Mentorship Count](https://github.com/Lesliec87/Pewlett-Hackard-Analysis/blob/main/Data/mentorship%20count.png)

