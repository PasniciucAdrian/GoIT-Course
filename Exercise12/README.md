# Exercise12 – SQL Queries and Database Manipulation

This folder contains the solution for Homework 12 of the GoIT Manual QA course. The task involved writing and executing a series of SQL queries to retrieve, insert, and delete data from a relational database, while also interpreting the results.

---

## 🎯 Objectives

- Practice SQL basics including `SELECT`, `WHERE`, `ORDER BY`, `LIKE`, `JOIN`, `INSERT`, `DELETE`, and aggregation
- Extract specific information using conditions and filters
- Insert and remove records to simulate real database operations
- Analyze query results using screenshots and structured summaries

---

## 📂 Files Included

- `Requirements Homework 12.pdf` – official assignment instructions
- `Printscreen explanations.pdf` – contains all screenshots and individual query explanations

---

## 🧪 Queries Overview

| # | Description | SQL Highlights |
|--:|-------------|----------------|
| 1 | Employees sorted by hire date (descending) | `ORDER BY hire_date DESC` |
| 2 | Employees born after 1960 | `WHERE birth_date > '1959-12-31'` |
| 3 | Last names starting with “Ma” | `WHERE last_name LIKE 'Ma%'` |
| 4 | Employees in Kyiv, Dnipro, Lviv | `WHERE city IN (...)` |
| 5 | Count engineers | `SELECT COUNT(*) AS total_engineers` |
| 6 | Cities with more than 10 employees | `GROUP BY city` + `HAVING COUNT > 10` |
| 7 | Join employees with titles | `JOIN` on `employee_no` |
| 8 | Employees with salary between 50k–60k | `BETWEEN 50000 AND 60000` |
| 9 | Insert new employee | `INSERT INTO employees (...) VALUES (...)` |
| 10 | Delete the new employee | `DELETE FROM employees WHERE employee_no = ...` |

---

## ✅ Insert & Delete Test

- A fictional employee named **Adrian Pasniciuc** was inserted using an `INSERT` query.
- His presence was verified at the bottom of the `employees` table.
- He was then successfully deleted using a `DELETE` query.
- Final verification confirmed that the record was removed.

---

## 🧠 Key Learnings

- Use of conditional selection and pattern matching
- Aggregation and grouping in queries
- Joining multiple tables to retrieve compound data
- Full cycle: inserting → verifying → deleting data
- Real-time SQL interaction using a sample database

---

## 📌 Status

All queries were successfully executed, interpreted, and documented with screenshots and written explanations in the attached PDF.

