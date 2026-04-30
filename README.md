# Database Management Systems (DBMS) Lab Portfolio

This repository includes the full set of laboratory exercises for Database Management Systems (DBMS) practical classes. It showcases a range of SQL tasks, starting from basic table definitions to more advanced queries using joins, subqueries, and aggregate operations.

## 📖 Overview

The exercises are mainly built on the traditional Oracle `EMPLOYEE`, `DEPARTMENT`, and `SALGRADE` database structures. Each file (`Experiment-X.md`) contains:
- The **Objective** of the experiment.
- The exact **SQL Queries** used to address the given tasks.
- The resulting **Tabular Output** that shows the query results.

## 🗄️ Database Schema

The primary schema used across these experiments consists of the following tables:
1. **DEPARTMENT**: Contains department information (`DEPTNO`, `DNAME`, `LOC`).
2. **EMPLOYEE**: Holds employee data (`EMPNO`, `ENAME`, `JOB`, `MGR`, `HIREDATE`, `SAL`, `COMM`, `DEPTNO`) and is linked to `DEPARTMENT` via a foreign key.
3. **SALGRADE**: Defines salary grade levels (`GRADE`, `LOSAL`, `HISAL`) for categorizing employees.

## 🧪 Experiments Index

| Experiment | Focus Area | Description |
| :--- | :--- | :--- |
| **[Experiment 1](./Experiment-1.md)** | DDL & DML Basics | Creating tables with constraints (primary/foreign keys) and inserting records. |
| **[Experiment 2](./Experiment-2.md)** | Data Retrieval Basics | Simple `SELECT` statements, filtering with `WHERE`, and column aliases. |
| **[Experiment 3](./Experiment-3.md)** | Sorting & Conditions | Using `ORDER BY`, `IN`, `LIKE`, and comparison operators. |
| **[Experiment 4](./Experiment-4.md)** | Built-in Functions | Working with string, numeric, and date functions. |
| **[Experiment 5](./Experiment-5.md)** | Aggregate Operations | Using `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`, and grouping data. |
| **[Experiment 6](./Experiment-6.md)** | Group Filtering | Applying `HAVING` with grouped results. |
| **[Experiment 7](./Experiment-7.md)** | Joins | Using inner joins, outer joins, and self joins to combine tables. |
| **[Experiment 8](./Experiment-8.md)** | Set Operators | Applying `UNION`, `INTERSECT`, and `MINUS`. |
| **[Experiment 9](./Experiment-9.md)** | Subqueries Basics | Using single-row and multi-row subqueries. |
| **[Experiment 10](./Experiment-10.md)** | Advanced Subqueries | Nested queries with `ANY`, `ALL`, and hierarchical queries. |
| **[Experiment 11](./Experiment-11.md)** | Data Analysis | Identifying highest salaries, comparing averages, and conditional data operations. |
| **[Experiment 12](./Experiment-12.md)** | Complex Queries | Using correlated subqueries, `NOT IN`, and string-based conditions. |

## 💻 Environment
- **Language**: SQL
- **Dialect**: Oracle SQL (works with most relational databases)
- **Format**: Markdown Documentation

---
*Prepared as part of DBMS laboratory coursework.* 
