GROUP 34 - PDAL 2
====================================

HR Management System README
Introduction
This HR Management System is a software application prototype given as an assignment designed to facilitate human resource management tasks within an organization. 
This system allows HR professionals to perform various operations, such as adding and managing employees, recording attendance, calculating total working hours, generating payslips, and more.

Project Structure
The HR Management System consists of several Python files, each with its specific role in the system.


Files:
=======
Director.py: This file contains the Director class, which represents employees with the role of a Director. Directors receive an annual bonus in addition to their base annual salary.

Employee.py: The Employee class is the core of the HR Management System. It represents employees and stores their information, such as ID, name, role, and more. The class provides functions for calculating monthly salaries, allowances, and bonuses.

Manager.py: Similar to Director.py, this file contains the Manager class, which represents employees with the role of a Manager. Managers have department information and receive allowances based on the number of direct reports and a management rate.

Intern.py: The Intern class is designed for employees with the role of Intern. Interns have specific attributes related to their educational background, such as the university, program, and internship duration.

HRManager.py: This is a critical file in the system. It contains the HRManager class responsible for managing and handling various HR-related tasks. The class can add, update, and remove employees, record attendance, generate payslips, and perform other HR operations.

README.md: This file contains the documentation you are currently reading.


How to Use
============
1) Follow the steps below to use the HR Management System:

2) Clone the project repository to your local machine.

3) Ensure you have Python installed on your system. The system uses Python for all its functionality.

4) Run the main.py script to launch the HR Management System.

5) Use the interactive menu to perform various operations, such as adding employees, updating information, recording attendance, calculating working hours, and generating payslips.

6) The system provides options to view employee information, view salary summaries, and save salary records to JSON files.

7) To exit the system, select the "Exit" option from the menu.


Menu Options
=========================
The system offers a menu with the following options:

1. Add Employee: Add new employees to the system, specifying their role and related attributes.

2. Update Employee: Update employee information, including role-specific details.

3. Remove Employee: Remove employees from the system.

4. Record Attendance: Record attendance by entering in-time and out-time for employees.

5. Display Employee Attendance: View attendance records for a specific employee.

6. Calculate Total Working Hours: Calculate the total working hours for a given employee within a specified date range.

7. View Employees: Display a list of all employees.

8. View Salary Summary: View a summary of employee salaries, including base annual salary, bonuses, and deductions.

9. Generate Payslip: Generate a payslip for a specific employee and store it in a text file named "EMPLOYEE_ID.txt."

10. Save Salary Records to JSON: Save salary records to JSON files for future reference.

11. Exit: Exit the HR Management System


Using Text Files
==================
To generate and save payslips as text files for each employee ID, you can add a function in your code that creates these text files within the employees/ directory. 
Ensure that the filenames match the employee IDs, making it easy to locate payslips for specific employees.

Using JSON Files
==================
To save salary details as JSON files for each employee ID, implement a function in your code to create and save these JSON files within the salary_records/ directory. 
Each JSON file should store comprehensive salary information for a specific employee.

Employee List JSON

Notes
======
Ensure you have the required Python packages installed, including dateutil and json.
The system supports employees with roles of Director, Manager, and Intern.
Manager and Director roles include allowances and bonuses.
The Intern role includes university, program, and internship duration attributes.



