# pascolan_backend

## Links
  
  - [API url](https://damp-chamber-13772.herokuapp.com/)

## API endpoints

  - Create Employee - POST /api/v1/employee
    Request body example:
      {
        "emp_id": 1239,
        "name": "Test user 3",
        "salary": 40000,
        "type": "senior"
      }

  - Get All Employees - GET /api/v1/employee
  - Get Employees with Highest Salary - GET /api/v1/employee/salary/max
  - Get Average Salary of Employees with type 'Senior' - GET /api/v1/employee/average/0
