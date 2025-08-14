## Write an SQL query to find the projects with the highest budget-per-employee ratio using the two related tables projects and employees.

### Projects Table

| ProjectID | ProjectName   | Budget    |
|-----------|---------------|-----------|
| 1         | Project Alpha | 100000.00 |
| 2         | Project Beta  | 50000.00  |
| 3         | Project Gamma | 150000.00 |

### Employees Table

| EmployeeID | ProjectID | EmployeeName |
|------------|-----------|--------------|
| 1          | 1         | Alice        |
| 2          | 1         | Bob          |
| 3          | 2         | Charlie      |
| 4          | 2         | David        |
| 5          | 3         | Eve          |
| 6          | 3         | Frank        |
| 7          | 3         | Grace        |

#### Expected Output

| ProjectID | Budget    | no_of_employees | cost_per_employee |
|-----------|-----------|-----------------|-------------------|
| 1         | 100000.00 | 2               | 50000.000000      |
| 3         | 150000.00 | 3               | 50000.000000      |
