# Employee App
A simple Employee Management backend application built using **Flask**, **SQLAlchemy**, and **MySQL**.
This project provides REST-style APIs to manage employee data, including:
- Add a new employee
- Get employee details
- Search employee records
- Update employee data
- Delete employee data
- Get salary details of an employee

## Tech Stack
- Python
- Flask
- SQLAlchemy
- MySQL
- PyMySQL
## Project Structure
```bash
employee-app/
│── controller.py       # Flask API routes
│── model.py            # SQLAlchemy models
│── mysql_client.py     # Database queries and MySQL connection logic
│── .vscode/            # VS Code settings
│── __pycache__/        # Python cache files

Features
Insert employee record into database
Fetch employee by ID
Fetch paginated employee list
Search employees by name
Fetch salary details of an employee
Update employee details
Delete employee record
