# Hospital-management-system1
Booking appointment
-- Insert a new row of data
INSERT INTO employees (first_name, last_name, email, hire_date, salary)
VALUES ('Alice', 'Smith', 'alice.smith@example.com', '2026-01-15', 75000.00);

-- Update an existing record safely using a WHERE clause
UPDATE employees 
SET salary = 82000.00 
WHERE employee_id = 1;

-- Delete a specific record from the table
DELETE FROM employees 
WHERE employee_id = 1;
