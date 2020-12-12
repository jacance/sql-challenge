Employee Database: A Mystery in Two Parts

Fictional corporation Pewlett Hackard requires research on its employees from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

Goal is to design tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data.

This project involved using available information to create a table schema for each of the six CSV files (specifying data types, primary keys, foreign keys, and other constraints).

Each CSV file was then imported into the corresponding SQL table.


Part I: Data Analysis

The complete database is queried to list the following:

- Details of each employee: employee number, last name, first name, sex, and salary.

- First name, last name, and hire date for employees who were hired in 1986.

- The manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

- First name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

- All employees in the Sales department, including their employee number, last name, first name, and department name.

- All employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

- The frequency count of employee last names, i.e., how many employees share each last name (in descending order).



Part II: Data Visualization

Steps taken to visualize the data for Pewlett Hackard management:

- Import the SQL database into Pandas.

- Create a histogram to visualize the most common salary ranges for employees.

- Create a bar chart of average salary by title.

