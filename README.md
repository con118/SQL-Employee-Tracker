# MySQL-employee-tracker
> This is a command line application that allows a user to manage information on employees within a company. The application connects to a database housed in MySQL that contains three tables with information on departments, roles, and employees within the company. This Content Management System allows a user to add, view, and modify information about employees of a company.

## User Story
As a business owner
I want to be able to view and manage the departments, roles, and employees in my company
So that I can organize and plan my business

## General Info
The database was initialized in MySQL Workbench after the schema files were set up (schema files included in repository). Data for employees was then seeded into the database after initialization. Upon running the program via the command line interface, a user can select to view all departments, view all roles, view all employees, add a department, add a role, add an employee, update an employee's current role, update an employee's current manager, remove an employee, remove a department, remove a role, and get the total salary for a specific department. After executing any of the add, update, or remove functions, the database is updated automatically.

## Sources
Application enabled using the following sources:

* [NPM Inquirer](https://github.com/SBoudrias/Inquirer.js/)
* [NPM MySQL](https://www.npmjs.com/package/mysql)
* [NPM console.table](https://www.npmjs.com/package/console.table)

## Deliverables: 10%

Your GitHub repository containing your application code.

### Walkthrough Video: 27%

A walkthrough video that demonstrates the functionality of the employee tracker must be submitted, and a link to the video should be included in your README file.

The walkthrough video must show all of the technical acceptance criteria being met.

The walkthrough video must demonstrate how a user would invoke the application from the command line.

The walkthrough video must demonstrate a functional menu with the options outlined in the acceptance criteria.

## Technical Acceptance Criteria: 40%

Satisfies all of the preceding acceptance criteria plus the following:

Uses the Inquirer packageLinks to an external site..

Uses the MySQL2 packageLinks to an external site. to connect to a MySQL database.

Follows the table schema outlined in the homework instructions.

## Repository Quality: 13%

Repository has a unique name.

Repository follows best practices for file structure and naming conventions.

Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

Repository contains multiple descriptive commit messages.

Repository contains a high-quality README with description and a link to a walkthrough video.

## Application Quality 10%

The application user experience is intuitive and easy to navigate.
Bonus
Fulfilling any of the following can add up to 20 points to your grade. Note that the highest grade you can achieve is still 100:

Application allows users to update employee managers (2 points).

Application allows users to view employees by manager (2 points).

Application allows users to view employees by department (2 points).

Application allows users to delete departments, roles, and employees (2 points for each).

Application allows users to view the total utilized budget of a department—in other words, the combined salaries of all employees in that department (8 points).