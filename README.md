# SQL-Task-5
## This task is based on creating 4 buisness questions that will solve business problems.

## These questions were answered.

### What is the average yearly increment?

- SELECT AVG Yearly Increment from salary table as shown in the photo below

![AVG_YEARLY_INCREMENT](https://github.com/Chi2166/SQL-Task-5/assets/144334275/c67ad618-4560-4cbc-82f3-c3ffe51bb0d3)

 ### Return the first name, yearly increment city and education from employee salary and department.

- SELECT First Name, Yearly Increment, City FROM employees, JOIN Salary table, ON employee table and Salary table with employee ID column. JOIN Department ON Employee table and department table with Department ID. As shown in the photo below. 

![Double_Join](https://github.com/Chi2166/SQL-Task-5/assets/144334275/65793c08-29eb-4817-8150-5b7c17d3426e)

### Find employee with pincode and their average sales? 

- SELECT Pincode, AVG sales AS average sales, FROM Employee table then GROUP BY Pincode column. As shown in the photo below.
  
![Group_by](https://github.com/Chi2166/SQL-Task-5/assets/144334275/cc1de92b-eb7e-40a2-b280-15fe026932b6)

### Order department ID from descending order?

- SELECT Department ID FROM Employee, GROUP BY Department ID ORDER BY Department ID in DESC. As shown in the photo below

![OrderBY](https://github.com/Chi2166/SQL-Task-5/assets/144334275/04784369-900d-4e57-b598-8a1c8a432bff)

