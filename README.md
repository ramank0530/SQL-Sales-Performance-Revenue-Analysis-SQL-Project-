📊 SQL Sales Performance & Revenue Analysis (SQL Project)
🔹 Objective
This project analyzes sales data to identify employee and department performance using SQL.
The goal is to extract meaningful business insights such as top performers, revenue trends, and growth patterns. This analysis helps businesses identify high-performing employees, detect declining departments early, and make data-driven decisions for performance improvement.

🔹 Dataset Description
The project uses three tables:

departments
Contains department details.

employees
Contains employee information including department and manager.

orders
Contains transaction-level data with order amount and date.

🔹 Key Analysis Performed
Top 3 employees per department by revenue
Monthly revenue per department
Running total revenue per employee
Revenue contribution (%) per employee
Managers whose subordinates outperform them
Employees with month-over-month growth
Departments with negative growth
Top 20% employees per department by revenue
Departments with 3 consecutive months of revenue decline
Rolling 3-month average revenue
🔹 SQL Concepts Used
Joins
Aggregations (SUM, COUNT, AVG)
Window Functions (LAG, ROW_NUMBER)
Common Table Expressions (CTEs)
Conditional Logic (CASE)
Streak detection using window functions
🔹 Key Insights
Employee Bob has improved month over month
There are no orders from Departments 'IT Support' and 'Human Resources'
Revenue is often concentrated among a small group of employees
Employee Charlie contributes ~62% of total revenue in the 'Enterprise Sales' department, indicating heavy dependency on a single performer
Department 'SMB Sales' and 'Marketing' shows negative growth
Revenue trends help identify declining departments early
🔹 Tools Used
MySQL
SQL
🔹 How to Run
Run dataset.sql to create tables and insert data
Run queries.sql to perform analysis
🔹 Project Structure
SQL-Sales-Performance-Analysis/ │ ├── dataset.sql -- Tables + Insert Data ├── queries.sql -- All analysis queries ├── README.md -- Project documentation


📊 Dashboard
Power BI dashboard built to visualize revenue trends and performance.

🔹 Tools Used
Power BI
Key Insights:
Enterprise Sales contributes ~90% of revenue
Revenue peaked in March 2023 (~180K)
SMB & Marketing contribute minimal share
Dashboard Preview:
2026-04-03 (3)
🔹 Author
Raman Kumar 
