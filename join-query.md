SELECT employees.first_name, departments.department_name
FROM employees
JOIN departments
ON employees.department_id = departments.department_id;



//This query retrieves employee names along with their department names.
