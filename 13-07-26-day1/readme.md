
# Student Data Analysis Using SQL

## Project Overview

This project demonstrates SQL-based data analysis on a **Students** dataset. It covers data exploration, data cleaning, filtering, sorting, aggregation, transformations, window functions, subqueries, and analytical SQL queries commonly used in real-world data analysis.

The project is designed to strengthen SQL skills through practical examples using student academic records.

---

## Objectives

- Explore and understand the dataset
- Clean missing data
- Filter and sort records
- Perform data transformations
- Generate grades and results
- Analyze department-wise performance
- Use aggregation and GROUP BY
- Apply window functions
- Perform data normalization using Min-Max Scaling

---

## 🛠️ Technologies Used

- SQL
- MySQL (Compatible with most SQL databases)

---

##Dataset

The project uses a table named **Students** with the following columns:

| Column | Description |
|---------|-------------|
| student_id | Unique Student ID |
| student_name | Student Name |
| department | Department Name |
| city | Student City |
| marks | Marks out of 200 |
| attendance | Attendance Percentage |

---

# SQL Operations Performed

## 1. Data Exploration

- Display first 5 records
- Count total rows
- Count total columns

---

## 2. Data Cleaning

- Identify missing values
- Replace missing marks with average marks

---

## 3. Filtering & Sorting

- Students scoring above 160
- Students from CS department
- Attendance above 85% and marks above 150
- Sort students by marks
- Display Top 3 performers

---

## 4. Column Transformations

- Calculate percentage
- Generate grades (A, B, C, Fail)
- Add bonus marks
- Generate Pass/Fail result
- Convert student names to uppercase

---

## 5. Group By & Aggregations

- Average marks by department
- Highest marks by city
- Student count by department
- Department with highest average marks
- Pivot table (Department vs City)

---

## 6. Advanced SQL

- Student Ranking using RANK()
- Students scoring above overall average
- Min-Max Scaling
- Attendance Categorization

---

# SQL Concepts Covered

- SELECT
- WHERE
- ORDER BY
- LIMIT
- GROUP BY
- Aggregate Functions
- CASE Statement
- UPDATE
- Subqueries
- Window Functions
- RANK()
- MIN()
- MAX()
- AVG()
- COUNT()
- Conditional Aggregation

---

# Learning Outcomes

After completing this project, you will understand how to:

- Explore datasets using SQL
- Clean missing data
- Perform data transformations
- Analyze datasets using aggregate functions
- Use CASE statements for categorization
- Apply ranking using Window Functions
- Build Pivot Tables in SQL
- Normalize data using Min-Max Scaling
- Write analytical SQL queries

---

# Sample Queries Included

✔ Display first five records

✔ Find missing values

✔ Replace NULL values

✔ Calculate percentage

✔ Assign grades

✔ Add bonus marks

✔ Generate pass/fail results

✔ Department-wise analysis

✔ Student ranking

✔ Above-average students

✔ Attendance categorization

✔ Min-Max scaling

---

# Project Structure

```
Student-Data-Analysis-SQL/
│
├── Student_SQL_Queries.sql
├── README.md
└── Students_Dataset.csv (Optional)
```

---

# Future Improvements

- Add joins with multiple tables
- Create SQL Views
- Stored Procedures
- Triggers
- Index Optimization
- Dashboard integration using Power BI or Tableau

---
