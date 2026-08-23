# 4. `SQL/01-Basics.md`

```markdown
# SQL Basics — Day 1

## Sample Table

Employee

| id | name | department | salary |
|---|---|---|---|
| 1 | Ravi | IT | 50000 |
| 2 | Arun | HR | 40000 |
| 3 | Priya | IT | 60000 |
| 4 | Kiran | Sales | 45000 |

---

## 1. SELECT

Display all columns:

```sql
SELECT * FROM Employee;

Display selected columns:

SELECT name, salary
FROM Employee;
2. WHERE

Filters rows.

SELECT *
FROM Employee
WHERE salary > 45000;
Operators
= Equal
> Greater than
< Less than
>= Greater/equal
<= Less/equal
<> Not equal
3. AND

Both conditions must be true.

SELECT *
FROM Employee
WHERE department = 'IT'
AND salary > 50000;
4. OR

At least one condition must be true.

SELECT *
FROM Employee
WHERE department = 'IT'
OR department = 'HR';
5. ORDER BY

Ascending:

SELECT *
FROM Employee
ORDER BY salary ASC;

Descending:

SELECT *
FROM Employee
ORDER BY salary DESC;
Aggregate Functions
COUNT
SELECT COUNT(*)
FROM Employee;

Counts rows.

SUM
SELECT SUM(salary)
FROM Employee;

Calculates total.

AVG
SELECT AVG(salary)
FROM Employee;

Calculates average.
MAX
SELECT MAX(salary)
FROM Employee;

Finds highest value.

MIN
SELECT MIN(salary)
FROM Employee;

Finds lowest value.

GROUP BY

Used to create groups.

SELECT department, AVG(salary)
FROM Employee
GROUP BY department;

This finds the average salary for each department.

WHERE vs HAVING
WHERE

Filters rows.

WHERE salary > 40000
HAVING

Filters groups.

HAVING AVG(salary) > 40000
Remember

WHERE → Rows

HAVING → Groups

WHERE → Before GROUP BY

HAVING → After GROUP BY

Placement Focus

Must know:

SELECT
WHERE
AND / OR
ORDER BY
COUNT
SUM
AVG
MAX
MIN
GROUP BY
WHERE vs HAVING