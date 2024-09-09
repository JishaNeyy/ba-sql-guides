SELECT first_name, last_name
FROM employees
WHERE department_id IN (SELECT department_id FROM departments WHERE location = 'New York');


//This query retrieves employees working in departments located in New York.
