# Employee Database

![Alt text](images/sql.png?raw=true "Title")

## Background

Designed tables to hold employee data contained in six CSV files. Once the CSVs were imported into an SQL database, the database was queried to answer questions about employee data.


## Data Engineering

![Alt text](EmployeeSQL/ERD_employee_database.png?raw=true "Title2")

- Inspect information to design Entity Relational Diagram and create a table schema for each of the six CSV files.

- Specify data types, primary keys, foreign keys, and other constraints.

- Import each CSV file into corresponding SQL table.


## Data Analysis

The complete database was queried to list the following:

- Details of each employee: employee number, last name, first name, sex, and salary.

- First name, last name, and hire date for employees who were hired in 1986.

- The manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

- First name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

- All employees in the Sales department, including their employee number, last name, first name, and department name.

- All employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

- The frequency count of employee last names, i.e., how many employees share each last name (in descending order).


## Data Visualization

Steps taken to visualize the employee salary information:

- Import the SQL database into Pandas.

- Create a histogram to visualize the most common salary ranges for employees.

- Create a bar chart of average salary by title.


## Technologies

- Postgres

- ERD diagram created via https://app.quickdatabasediagrams.com/

- Pandas

- SQLAlchemy

- Matplotlib

- Jupyter Notebook
