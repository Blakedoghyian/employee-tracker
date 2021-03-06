# Employee-Tracker

## ACCEPTANCE CRITERIA

# GIVEN a command-line application that accepts user input
* WHEN I start the application
* THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
* WHEN I choose to view all departments
* THEN I am presented with a formatted table showing department names and department ids
* WHEN I choose to view all roles
* THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
* WHEN I choose to view all employees
* THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
* WHEN I choose to add a department
* THEN I am prompted to enter the name of the department and that department is added to the database
* WHEN I choose to add a role
* THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
* WHEN I choose to add an employee
* THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
* WHEN I choose to update an employee role
* THEN I am prompted to select an employee to update and their new role and this information is updated in the database

# Getting Started
* open terminal
* run 'npm install' to install dependencies 
* open mysql shell by running 'mysql -u root -p' and enter credentials
* run 'source schema.sql' file from terminal
* after, run 'source seeds.sql' from mysql shell then type 'exit'
* run 'node server.js' to begin user prompts

## Repository 
* https://github.com/Blakedoghyian/employee-tracker

## Walkthrough video
* https://watch.screencastify.com/v/hoyqwnkqeEhHoZh0a350

## Questions 

* Please use this email to reach me directly with any questions or concerns:
* <a href="mailto:xblakedx@gmail.com">xblakedx@gmail.com</a>

## Screenshot

![Screenshot (41)](https://user-images.githubusercontent.com/91994720/151749889-b67c5e13-8aea-4dde-a48a-367d263c8619.png)
