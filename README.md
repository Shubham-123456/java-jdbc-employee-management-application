# Employee Management System

A console-based **Employee Management System** developed using **Core Java, JDBC, and MySQL**. This project demonstrates CRUD operations, database connectivity, object-oriented programming principles, and the DAO (Data Access Object) design pattern.

This project was built as part of my Java Backend Development learning journey to strengthen my understanding of JDBC and relational database integration.

---

## Features

- Add a new employee
- View all employees
- Search employee by Employee ID
- Update employee details
- Delete employee records
- Input validation
  - Name validation
  - Salary validation
  - Date validation (`yyyy-MM-dd`)
- Exception handling
- Menu-driven console interface

---

## Technologies Used

- Java (Core Java)
- JDBC
- MySQL
- Eclipse IDE
- SQL

---

## Concepts Implemented

- Object-Oriented Programming (OOP)
- JDBC API
- DAO (Data Access Object) Design Pattern
- PreparedStatement
- ResultSet
- Exception Handling
- Java Collections (ArrayList)
- Data Validation
- MySQL CRUD Operations

---

## Project Structure

```
Employee-Management-System
│
├── src
│   ├── dao
│   │     └── EmployeeDAO.java
│   │
│   ├── model
│   │     └── Employee.java
│   │
│   ├── util
│   │     └── DBConnection.java
│   │
│   └── main
│         └── EmployeeManagementApp.java
│
├── sql
│     └── employee_management.sql
│
└── README.md
```

---

## Database Schema

| Column | Data Type |
|---------|-----------|
| emp_id | INT (Primary Key) |
| first_name | VARCHAR(50) |
| last_name | VARCHAR(50) |
| department | VARCHAR(50) |
| reporting_manager | VARCHAR(50) |
| salary | DECIMAL(10,2) |
| joining_date | DATE |

---

## Application Flow

```
User
   │
   ▼
EmployeeManagementApp
   │
   ▼
EmployeeDAO
   │
   ▼
DBConnection
   │
   ▼
MySQL Database
```

---

## Screenshots

### Main Menu

<img width="360" height="177" alt="image" src="https://github.com/user-attachments/assets/8691f9b0-291f-41bc-bcb8-aa1bef25aeba" />

### Add Employee

<img width="402" height="204" alt="image" src="https://github.com/user-attachments/assets/4f26b317-82af-41e6-b3bf-ea1dd53fa9fb" />

### View Employees

<img width="1128" height="332" alt="image" src="https://github.com/user-attachments/assets/1082cc14-0c55-4276-b320-1eb37a07850e" />

### Update Employee

<img width="294" height="256" alt="image" src="https://github.com/user-attachments/assets/b9eb8286-2d8e-4c7c-9d8c-cfc1071cbacf" />
<img width="1127" height="331" alt="image" src="https://github.com/user-attachments/assets/a1601bef-3314-4fd9-9fee-454f594ac8c6" />

### Delete Employee

<img width="298" height="82" alt="image" src="https://github.com/user-attachments/assets/5e0f3693-0613-460e-aef7-9ae84aac2886" />
<img width="1125" height="310" alt="image" src="https://github.com/user-attachments/assets/89905af2-1269-4faa-bf65-b4b18b7b7ac3" />

---

## Sample Console Output

```
***** Employee Management System *****

1. Add Employee
2. View All Employees
3. Search Employee
4. Update Employee
5. Delete Employee
6. Exit
Enter your choice:
```

---

## Future Enhancements

- Login Authentication
- Search by Department
- Pagination
- Sorting
- Transaction Management
- Logging (Log4j/SLF4J)
- Maven Build
- Unit Testing (JUnit)
- Spring Boot REST API
- Spring Data JPA
- Hibernate

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Java Database Connectivity (JDBC)
- Writing SQL CRUD queries
- Designing applications using the DAO pattern
- Database interaction using PreparedStatement
- Exception handling
- Input validation
- Building a layered Java application

---

## Author

**Shubham Chakraborty**

Aspiring Java Backend Developer

LinkedIn: https://www.linkedin.com/in/shubham-chakraborty-642027226/

---

If you found this project useful, feel free to ⭐ the repository.
