# Employee Management Backend

A Spring Boot based Employee Management Backend application that provides RESTful APIs to manage employee records efficiently. The project follows a layered architecture (Controller → Service → Repository) and uses MySQL as the database.

---

## Features

- Add Employee
- Update Employee Details
- Delete Employee
- Get Employee by ID
- Get All Employees
- RESTful APIs
- Layered Architecture
- MySQL Database Integration
- Exception Handling

---

## Tech Stack

- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- REST APIs
- Postman

---

## Project Structure

```
src
├── controller
├── service
├── repository
├── entity
├── dto
├── exception
└── config
```

---

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | /employees | Get all employees |
| GET | /employees/{id} | Get employee by ID |
| POST | /employees | Add new employee |
| PUT | /employees/{id} | Update employee |
| DELETE | /employees/{id} | Delete employee |

---

## Database

- MySQL
- Spring Data JPA
- Hibernate ORM

---

## Tools Used

- IntelliJ IDEA
- Postman
- Git
- GitHub
- Maven

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/nikkygupta933-byte/employee-management-backend.git
```

2. Open the project in IntelliJ IDEA.

3. Configure MySQL database in `application.properties`.

4. Run the Spring Boot application.

5. Test APIs using Postman.

---

## Future Improvements

- Spring Security
- JWT Authentication
- Swagger API Documentation
- Docker Deployment
- Unit Testing

---

## Author

**Nikki Gupta**

B.Tech Computer Engineering  
Aligarh Muslim University

LinkedIn:
https://www.linkedin.com/in/nikki-gupta

GitHub:
https://github.com/nikkygupta933-byte
