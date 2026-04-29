<h1>Hi, I'm Gunel! <br/><a href="https://github.com/gunelmusayeva1">SQL & PL/SQL Developer | Data Analyst </a>
  
<h2> Projects:</h2> Oracle HR Analytics

Oracle SQL · Window Functions · Joins · Subqueries · Date Functions

About This Project
In this project, I wrote 19 SQL queries using Oracle's HR Schema database.
The queries solve real-life business problems — such as salary analysis, department statistics, employee rankings, and date calculations.
Database: Oracle HR Schema
Tables used: employees, departments, locations, countries, regions, jobs

 Queries
#	Problem	Techniques Used
1	 Find the date when each employee gets their first salary	ADD_MONTHS, LAST_DAY, TO_CHAR
2	 Find cities with no employees	Multi-table LEFT JOIN, IS NULL
3	 Rank employees by hire date within each country	DENSE_RANK, PARTITION BY
4	 Find employees who earn more than their manager	Self JOIN
5	 Count the number of countries in each region	GROUP BY, COUNT
6	 Rank employees by salary within each job	ROW_NUMBER, ORDER BY
7	 Find which number hire each employee was in their year	ROW_NUMBER, EXTRACT, PARTITION BY
8	 Sum of salaries 2 rows before and 3 rows after each employee	LAG, LEAD
9	 Find the earliest hire date in each employee's country	MIN OVER, PARTITION BY
10	Find the department with the most employees	GROUP BY, FETCH FIRST
11	List all possible game pairs for a chess tournament (different departments only)	CROSS JOIN
12	Find the second highest salary	Nested Subquery, MAX
13	Find employees who are not managers	NOT IN, Subquery
14	Find the department with the lowest average salary	AVG, FETCH FIRST, Nested Subquery
15	Find the employee in the middle of the salary ranking (median)	ROW_NUMBER, ROUND, Subquery
16	Find the first hired employee in each department	ROW_NUMBER, PARTITION BY
17	Find departments where average salary is less than half of the max salary	Window AVG, Window MAX
18	List employees from the 3 smallest departments	Nested Subquery, FETCH FIRST
19	Find the average number of hires per month for each year	EXTRACT, GROUP BY, Nested AVG

 Tools & Techniques
•	Oracle SQL Developer
•	Window Functions: ROW_NUMBER, DENSE_RANK, LAG, LEAD, MIN OVER
•	Join types: INNER JOIN, LEFT JOIN, SELF JOIN, CROSS JOIN
•	Subqueries and CTEs (WITH)
•	Date functions: ADD_MONTHS, LAST_DAY, TO_CHAR, EXTRACT

  

