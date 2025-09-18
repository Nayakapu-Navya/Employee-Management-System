📊 SQL-Employee-Management-System
🔹 Project Overview
This project focuses on building a complete SQL-based Employee and Payroll Management System. It involves designing a relational database, importing real-world data from Excel files, ensuring data integrity through constraints, and generating actionable business insights using SQL queries.

🔹 Data Import
Imported raw datasets from Excel files covering:
Employee details
Job departments
Salaries and bonuses
Leave records
Payroll summaries
Educational qualifications
Cleaned and transformed the data to match a relational database schema.
Loaded the datasets into MySQL tables using import tools and scripts.
🔹 Database Design
Created normalized tables for the following entities:

JobDepartment: Job roles, salary ranges, department names
SalaryBonus: Salary, annual pay, and bonuses
Employee: Personal info, job references, and login credentials
Qualification: Employee qualifications and job requirements
Leaves: Leave records and reasons
Payroll: Monthly payroll records, total salary, and deductions
🔑 Keys & Constraints:
Primary Keys and Foreign Keys defined for all major relationships
ON DELETE SET NULL and Cascading Updates/Deletes used to maintain integrity
Unique Constraints (e.g., on emails) enforced to avoid duplicates
🔹 SQL Queries & Business Insights
📍 Employee Insights
Counted total and unique employees
Identified departments with the highest workforce
Calculated average salary per department
Listed top 5 highest-paid employees
Computed total salary expenditure for the company
📍 Job Role & Department Analysis
Counted job roles per department
Analyzed salary ranges by department
Identified highest-paying job roles
Summed salary allocations per department
📍 Qualification & Skills Analysis
Counted employees with at least one qualification
Identified roles requiring the most qualifications
Ranked employees by number of qualifications
📍 Leave & Absence Patterns
Analyzed leaves taken per year
Found average leave days by department
Listed employees with most leaves
Correlated leave days with payroll amounts
📍 Payroll & Compensation
Calculated total monthly payroll
Found average bonus per department
Identified departments with highest total bonuses
Compared gross vs net pay after deductions
📍 Employee Growth & Promotions
Analyzed yearly promotions based on bonuses
Tracked employee growth patterns over time
🔹 Key Features & Outcomes
✅ End-to-End Pipeline: Excel → SQL Database → Querying → Insight Generation
✅ Data Integrity: Strong relationships, constraints, and keys
✅ Business Insights: Workforce, compensation, leaves, qualifications
✅ Scalability: Database schema can expand to accommodate more data

🔹 Tools & Technologies Used
SQL (MySQL) – For database design and querying
Excel – As the primary data source
*MySQL Workbench *-For importing data, running queries, and managing schema
🔹 Final Result
This project successfully simulated a real-world *HR & Payroll Management System, with structured data storage, integrity enforcement, and insightful analytics. It demonstrates how *SQL can be used not just for data storage, but also to support strategic decision-making, payroll optimization, and workforce planning.
