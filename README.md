# 📚 Online Examination System

A backend-based **Online Examination System** developed using **Java, Spring Boot, Spring Data JPA, Hibernate, and MySQL**. The application provides RESTful APIs to manage users, subjects, exams, questions, and results using a layered architecture.

---

## 🚀 Features

- User Management (CRUD)
- Subject Management
- Exam Management
- Question Management
- Result Management
- RESTful APIs
- Spring Data JPA & Hibernate Integration
- MySQL Database
- Layered Architecture (Controller → Service → Repository)
- JSON Request & Response
- Maven Project Structure

---

## 🛠️ Technologies Used

- Java 21
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven
- REST APIs
- Eclipse IDE
- Bruno / Postman

---

## 📁 Project Structure

```
src
 └── main
      ├── java
      │     └── com.exam
      │          ├── controller
      │          ├── entity
      │          ├── repository
      │          ├── service
      │          ├── serviceimpl
      │          ├── config
      │          └── OnlineExamSystemApplication
      │
      └── resources
            └── application.properties
```

---

## 🏗️ Architecture

```
Client
   │
   ▼
Controller
   │
   ▼
Service
   │
   ▼
Repository
   │
   ▼
MySQL Database
```

---

## 📂 Modules

### User Module
- Add User
- View Users
- Update User
- Delete User

### Subject Module
- Add Subject
- View Subjects
- Update Subject
- Delete Subject

### Exam Module
- Create Exam
- View Exams
- Update Exam
- Delete Exam

### Question Module
- Add Questions
- View Questions
- Update Questions
- Delete Questions

### Result Module
- Store Results
- View Results
- Update Results
- Delete Results

---

## ⚙️ Database

Database Name

```
online_exam_db
```

Tables

- user
- subject
- exam
- question
- result

---

## 📌 REST API Endpoints

### User APIs

| Method | Endpoint |
|---------|----------|
| POST | /users |
| GET | /users |
| GET | /users/{id} |
| PUT | /users/{id} |
| DELETE | /users/{id} |

### Subject APIs

| Method | Endpoint |
|---------|----------|
| POST | /subjects |
| GET | /subjects |
| GET | /subjects/{id} |
| PUT | /subjects/{id} |
| DELETE | /subjects/{id} |

### Exam APIs

| Method | Endpoint |
|---------|----------|
| POST | /exams |
| GET | /exams |
| GET | /exams/{id} |
| PUT | /exams/{id} |
| DELETE | /exams/{id} |

### Question APIs

| Method | Endpoint |
|---------|----------|
| POST | /questions |
| GET | /questions |
| GET | /questions/{id} |
| PUT | /questions/{id} |
| DELETE | /questions/{id} |

### Result APIs

| Method | Endpoint |
|---------|----------|
| POST | /results |
| GET | /results |
| GET | /results/{id} |
| PUT | /results/{id} |
| DELETE | /results/{id} |

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/Venkatesh7981/online-exam-system.git
```

2. Open the project in Eclipse or IntelliJ IDEA.

3. Create a MySQL database.

```sql
CREATE DATABASE online_exam_db;
```

4. Update `application.properties`.

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/online_exam_db
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

5. Run

```
OnlineExamSystemApplication.java
```

6. Test APIs using Bruno or Postman.

---

## 📖 Future Enhancements

- Spring Security
- JWT Authentication
- Role-Based Authorization
- Validation
- Global Exception Handling
- Swagger/OpenAPI Documentation
- Docker Deployment

---

## 👨‍💻 Author

**Kuruva Venkatesh**

- GitHub: https://github.com/Venkatesh7981
- LinkedIn: https://linkedin.com/in/venkatesh7981

---

## ⭐ If you found this project useful

Please consider giving it a ⭐ on GitHub.
