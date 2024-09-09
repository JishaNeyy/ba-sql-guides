SELECT employee_id, first_name, salary,
       ROW_NUMBER() OVER (ORDER BY salary DESC) AS salary_rank
FROM employees;



//This query ranks employees based on their salary.
