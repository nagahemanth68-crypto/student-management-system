# Student Management System

A web-based Student Management System developed using Java, Spring Boot, MySQL, HTML, CSS, and JavaScript.

This project allows users to manage student records through a simple and responsive dashboard.

## Features

- Add new student records
- View all students
- Update student details
- Delete student records
- Search students by name or email
- Filter students by course
- Dashboard statistics
- Form validation
- Duplicate email validation
- Responsive user interface

## Technologies Used

**Backend**
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- REST API

**Database**
- MySQL

**Frontend**
- HTML
- CSS
- JavaScript

**Tools**
- Visual Studio Code
- Maven
- Git
- GitHub

## Project Structure

```text
student-management-system/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/student/student_management/
│   │   │       ├── StudentManagementApplication.java
│   │   │       ├── controller/
│   │   │       ├── entity/
│   │   │       └── repository/
│   │   └── resources/
│   │       └── static/
│   │           └── index.html
├── pom.xml
├── mvnw
├── mvnw.cmd
└── .gitignore
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/nagahemanth68-crypto/student-management-system.git
```

### 2. Open the project

Open the cloned project folder in Visual Studio Code.

### 3. Configure MySQL

Create a MySQL database:

```sql
CREATE DATABASE student_management;
```

Configure your local database connection in:

`src/main/resources/application.properties`

Use your own MySQL username and password.

**Do not upload your actual database password to GitHub.**

### 4. Run the application

Open the terminal in the project directory and execute:

```powershell
.\mvnw.cmd spring-boot:run
```

### 5. Open the application

Visit:

http://localhost:8080

## REST API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/students` | Get all students |
| POST | `/api/students` | Add a student |
| GET | `/api/students/{id}` | Get student by ID |
| PUT | `/api/students/{id}` | Update student |
| DELETE | `/api/students/{id}` | Delete student |

## Student Details

Each student record contains:

- ID
- Name
- Email
- Course
- Age

## Future Improvements

- Deploy the application on AWS
- Add user authentication
- Improve database security
- Add cloud database integration

## Author

**Naga Hemanth**

GitHub: [nagahemanth68-crypto](https://github.com/nagahemanth68-crypto)

---

This project was developed as a learning project to practice Java, Spring Boot, MySQL, REST APIs, and web development.
