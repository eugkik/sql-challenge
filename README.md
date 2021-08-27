# sql-challenge

The ERD was created using quickdatabasediagrams.com and exported as employee_schema.sql.

The database tables are created using employee_schema.sql.

The resource CSV files are imported into the database tables.

The employee_queries.sql file contains the queries for the following:

1. List the following details of each employee: employee number, last name, first name, sex, and salary.

2. List first name, last name, and hire date for employees who were hired in 1986.

3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. List the department of each employee with the following information: employee number, last name, first name, and department name.

5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. List all employees in the Sales department, including their employee number, last name, first name, and department name.

7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

The EmployeeNotebook.ipynb Jupyter Notebook uses a username and password*  to connect to the SQL database and plots a histogram of the most common salary ranges for employees and a bar chart of the average salary by title.

*NOTE: A config.py file with the database password is required for the Jupyter Notebook

4-1. Mystery Solved...