# SQL for Data Analysis - SQL Plus

## 📁 Overview

This repository contains the solution for **Task 3** of the Data Analyst Internship, focusing on writing SQL queries to extract, analyze, and manipulate data from a relational database. This task showcases proficiency in essential SQL operations and query optimization techniques.

---

## 📝 Task Description

The objective is to write SQL queries to perform data analysis using the following SQL concepts:

- ✅ **SELECT, WHERE, ORDER BY, GROUP BY** – for filtering, sorting, and grouping data  
- ✅ **JOINS (INNER, LEFT, RIGHT)** – to combine data from multiple tables  
- ✅ **Subqueries** – for complex nested filtering  
- ✅ **Aggregate Functions (SUM, AVG)** – to compute summary statistics  
- ✅ **Views** – to create reusable query results  
- ✅ **Indexes** – to optimize query performance  

The dataset consists of two standard tables:

- **EMP** – Employee data  
- **DEPT** – Department data  

---

## 📂 Files Included

### `task4.sql`  
Contains all SQL queries and corresponding outputs. The tasks covered:

1. **SELECT with WHERE and ORDER BY**  
   - Filter employees with salary > 2000  
   - Sort by hire date  

2. **GROUP BY with AVG**  
   - Calculate average salary per department  

3. **INNER JOIN**  
   - Combine employee and department data  
   - Display employee name, salary, department name, and location  

4. **LEFT JOIN**  
   - List all employees with their department details (even if missing)

5. **RIGHT JOIN**  
   - Show department-wise employee data (even if department has no employee)

6. **Subquery**  
   - Find employees who work in 'DALLAS'

7. **Aggregate Functions**  
   - Use `SUM` and `AVG` to show total and average salaries per department  

8. **View Creation**  
   - Create a view for employees with salary > 3000  

9. **Querying the View**  
   - Retrieve data from the created view, sorted by salary  

10. **Index Creation**  
    - Create indexes on `DEPTNO` and `SAL` columns to optimize performance  

---

## 🛠 Tools Used

- **Database System**: Compatible with MySQL, PostgreSQL, or SQLite  
- **Tables Used**:  
  - `EMP(EMPNO, ENAME, JOB, MGR, HIREDATE, SAL, COMM, DEPTNO)`  
  - `DEPT(DEPTNO, DNAME, LOC)`  
- **SQL Environment**: Queries executed using `SPOOL` to capture outputs  
- **Formatting**: Commands like `SET PAGESIZE` and `SET LINESIZE` used for better readability  

---

## ▶️ Setup and Execution

1. **Database Setup**  
   Ensure your SQL environment has the standard **EMP** and **DEPT** schema.  

2. **Run Queries**  
   Load and execute `task4.sql` in your SQL editor or terminal.  

3. **View Output**  
   Output is embedded directly in the file after each query (text-based format).  

---

## 📝 Notes

- The standard **EMP** and **DEPT** dataset was used, as allowed by the task instructions.  
- All query requirements from the Hints/Mini Guide were fulfilled.  
- Outputs are text-based (spooled), satisfying the requirement for embedded screenshots.  

---

## ✅ Submission

This repository is organized for GitHub submission:

- `task4.sql` includes all SQL queries and outputs.  
- `README.md` (this file) provides a clear explanation of the task, execution, and repository contents.  

---

## 📌 License

This project is for educational/internship evaluation purposes.

---

