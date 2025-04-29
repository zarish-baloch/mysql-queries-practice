#  MySQL Queries Practice

A collection of basic MySQL queries I’ve used and practiced during my job and learning.

---

##  Sample Queries

```sql
-- Create a table
CREATE TABLE employees (
  id INT PRIMARY KEY,
  name VARCHAR(50),
  department VARCHAR(50)
);

-- Insert data
INSERT INTO employees VALUES (1, 'Zarish', 'IT');

-- Select all data
SELECT * FROM employees;

-- Find by department
SELECT * FROM employees WHERE department = 'IT';
