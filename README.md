# University Database SQL Project

## Description

This project contains SQL queries for managing and analyzing a university database using MySQL.

The database includes students, departments, instructors, courses, and enrollments. The project demonstrates database creation, table relationships, data manipulation, filtering, aggregation, joins, subqueries, date functions, window functions, and conditional statements.

## Database

**Database Name:** `UniversityDB`

## Tables

* `Departments`
* `Students`
* `Instructors`
* `Courses`
* `Enrollments`

## SQL Concepts Covered

### Database & Table Creation

* Created the `UniversityDB` database.
* Created tables for departments, students, instructors, courses, and enrollments.
* Used `PRIMARY KEY` constraints.
* Used `FOREIGN KEY` relationships between tables.

### Data Manipulation

* Inserted records into tables using `INSERT INTO`.
* Updated student information using `UPDATE`.
* Deleted student records using `DELETE`.

### Queries Solved

1. Displayed all student records.
<img width="617" height="202" alt="ss 01" src="https://github.com/user-attachments/assets/00bbb995-c398-4edd-b7b8-f0378de33a67" />
2. Updated the email address of a student.
3. Deleted a student record.
<img width="170" height="112" alt="ss 03" src="https://github.com/user-attachments/assets/4b8a34c8-0f0c-4b74-9b1f-7467dcfa8206" />
4. Retrieved students enrolled after 2022.
5. Retrieved Mathematics department courses.
<img width="170" height="112" alt="ss 03" src="https://github.com/user-attachments/assets/d4a0eba9-6030-49a7-9831-7328de01ae98" />
6. Found courses having more than 5 students.
7. Found students enrolled in both specified courses.
<img width="265" height="210" alt="ss 08" src="https://github.com/user-attachments/assets/31ce44ee-ec34-49e0-9729-217a90438fe7" />
8. Found students enrolled in either of the specified courses.
9. Calculated the average number of course credits.
-<img width="162" height="47" alt="ss 06" src="https://github.com/user-attachments/assets/93b405e5-419a-4ccf-8763-114eab924859" />
10. Found the maximum salary of Computer Science instructors.
<img width="157" height="55" alt="ss 07" src="https://github.com/user-attachments/assets/8161ee9f-268d-4a4a-8570-a919b9acdb79" />
11. Counted students in each department.
12. Used `INNER JOIN` to display students and their courses.
13. Used `LEFT JOIN` to display students and their courses.
14. Used a subquery to find students enrolled in courses with more than 10 enrollments.
15. Extracted the enrollment year using `YEAR()`.
16. Concatenated instructor first and last names using `CONCAT()`.
17. Calculated a running total using a window function.
18. Classified students as `Senior` or `Junior` using `CASE` and date functions.

## SQL Functions and Features Used

* `COUNT()`
* `AVG()`
* `MAX()`
* `CONCAT()`
* `YEAR()`
* `DATE_SUB()`
* `CURDATE()`
* `CASE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `LIMIT`
* `DISTINCT`
* `INNER JOIN`
* `LEFT JOIN`
* Subqueries
* Window functions
* Primary keys
* Foreign keys

## Technologies Used

* MySQL
* SQL

## Project Structure

```text
University Database SQL Project
│
├── Departments
├── Students
├── Instructors
├── Courses
└── Enrollments
```

## Key Learning Outcomes

* Understanding relational database design.
* Creating tables with primary and foreign keys.
* Performing CRUD operations.
* Filtering and grouping data.
* Using aggregate functions.
* Working with multiple tables using joins.
* Writing subqueries.
* Using date and string functions.
* Applying conditional logic with `CASE`.
* Using window functions for analytical queries.
