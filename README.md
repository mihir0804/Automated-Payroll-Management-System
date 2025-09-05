# Employee Payroll System SQL Project

## Overview
The **Employee Payroll System SQL Project** is a database design and implementation project for managing employee payroll operations.  
It covers employees, attendance, salaries, payroll, and reporting, providing a complete schema to handle HR and payroll requirements in an organization.

---

## Database Schema
The project implements the following core tables:
- **Employees** – Stores employee details such as name, department, position, hire date, and base salary.  
- **Attendance** – Records daily attendance status (Present, Absent, Leave).  
- **Salaries** – Contains monthly salary details including base salary, bonus, deductions, month, and year.  
- **Payroll** – Stores calculated total salary and payment date for employees.  

---

## Features
- **Database creation** with proper constraints (Primary Key, Foreign Key).  
- **Data insertion** with realistic sample data for employees, attendance, salaries, and payroll.  
- **Queries** to demonstrate:
  - Attendance tracking and summaries  
  - Salary calculation (base + bonus – deductions)  
  - Payroll generation and pay slips  
  - Listing employees by department  
  - Aggregated reports (yearly salary, total deductions, highest salary, etc.)  
- **Data updates** (e.g., updating employee salary).  
- **Reports** for HR and payroll management.  

---

## Sample Queries
Examples include:
- Calculate total salary for an employee for a given month.  
- Generate monthly pay slips with salary breakdown.  
- List employees by department.  
- Attendance summary with present, absent, and leave days.  
- Employees with salary above a threshold.  
- Yearly salary report for all employees.  

---

## How to Use
1. Clone this repository.  
2. Open the `.sql` script in your MySQL environment.  
3. Run the script step by step to create the database and populate it.  
4. Execute the provided queries to analyze payroll, salary, and attendance data.  

---

## Technologies
- **Database**: MySQL  
- **Language**: SQL  

---

## Learning Outcomes
This project helps in understanding:
- Payroll and HR database design.  
- Attendance and salary management using SQL.  
- Querying techniques for payroll analytics.  
- Real-world applications of joins, aggregations, and reporting queries.  

---

## License
This project is licensed under the **Apache 2.0 License**.  
