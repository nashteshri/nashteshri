Assignment: Employee Management and Analytics System
Objective:
Build a simple Employee Management and Analytics System to manage employees, track
their activities, and generate reports using advanced TypeScript concepts.
1. Employee Management
1. Define an Employee Model:
o Create an Employee structure with properties like ID, name, email, role, and
status (active/inactive).
o Ensure roles include predefined options like Manager, Developer, and
Intern.
2. Utility Types:
o Use TypeScript's utility types:
▪ Allow updates to employee records with specific fields.
▪ Generate employee summaries using only essential fields (e.g., name
and role).
▪ Store employees in a structured map format (e.g., group employees by
role).
3. Tasks:
o Add a list of employees.
o Update specific fields for an existing employee.
o Create and display a summary of employees.
2. Activity Tracking
1. Activity Logger:
o Implement a feature to log activities for employees.
o Restrict certain activities to specific roles (e.g., only managers can approve
reports).
2. Type Guards:
o Write type guards to:
▪ Validate an employee's role (e.g., check if an employee is a Manager).
▪ Ensure activities can only be logged by active employees.
3. Tasks:
o Log activities for different employees.
o Attempt to log activities for inactive employees and observe the error
handling.
3. Analytics Dashboard
1. Analyze Data:
o Create a function to:
▪ Count total employees.
▪ Calculate active employees.
▪ Display the distribution of roles.
2. Handle Unknown Data:
o Simulate receiving external data.
o Validate and process this data to ensure it matches the expected employee
format.
o Handle invalid data scenarios with meaningful error messages.
3. Tasks:
o Pass valid and invalid employee lists to analyze the data.
o Display analytics results and handle errors gracefully.
4. Error Handling and Debugging
1. Error Handling:
o Simulate common errors like:
▪ Updating a non-existent employee.
▪ Logging activities for an invalid employee.
2. Debugging:
o Use debugging tools like grouped console logs and tables to inspect data.
o Create meaningful logs for each step.
3. Tasks:
o Simulate error scenarios and document how they are handled.
o Display employee data and analytics results in a structured format for
