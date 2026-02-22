# 🏨 Hotel Management System (HMS)

A secure and scalable **Hotel Management System** built using **Spring Boot 3**, **Java 17**, **Spring Security**, **JWT Authentication**, **Spring Data JPA**, and **MySQL**.

This application provides RESTful APIs for managing hotel operations including user authentication, hotel management, booking management, and role-based access control.

---

## 🚀 Tech Stack

- Java 17  
- Spring Boot 3.4.2  
- Spring Data JPA (Hibernate)  
- Spring Security  
- JWT (java-jwt)  
- MySQL  
- ModelMapper  
- Spring Validation  
- Swagger (OpenAPI)  
- Maven  

---

## 🔐 Security Features

- JWT-based authentication  
- Role-based authorization (Admin/User)  
- Password encryption using BCrypt  
- Stateless session management  
- Protected REST endpoints  

---

## 📂 Project Architecture

The project follows a layered architecture:

Controller → Service → Repository → Database  

- Controller Layer – Handles HTTP requests and responses  
- Service Layer – Contains business logic  
- Repository Layer – Database interaction using JPA  
- Security Layer – JWT filter and authentication configuration  
- DTO Layer – Data transfer between layers  
- Entity Layer – Database models  

---

## 📌 Features

- User Registration  
- User Login with JWT Token  
- Hotel CRUD Operations  
- Booking Management  
- Role-Based Access Control  
- Input Validation  
- API Documentation with Swagger  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone https://github.com/Manjeetkr1217/Hotel-Management-System.git  
cd Hotel-Management-System  

---

### 2️⃣ Configure Database

Update application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/hms_db  
spring.datasource.username=your_username  
spring.datasource.password=your_password  

spring.jpa.hibernate.ddl-auto=update  
spring.jpa.show-sql=true  
spring.jpa.properties.hibernate.format_sql=true  

---

### 3️⃣ Build the Project

mvn clean install  

---

### 4️⃣ Run the Application

mvn spring-boot:run  

Application will start at:

http://localhost:8080  

---

## 📖 API Documentation

Swagger UI is available at:

http://localhost:8080/swagger-ui.html  

---

## 🧠 Design Highlights

- Layered architecture for clean separation of concerns  
- DTO pattern to avoid exposing entities directly  
- Stateless authentication using JWT  
- Input validation using Spring Validation  
- Clean RESTful API design  

---

## 🛠 Future Enhancements

- Docker containerization  
- Pagination & Sorting  
- Global exception handling improvement  
- Unit & Integration test coverage  
- CI/CD pipeline integration  

---

## 👨‍💻 Author

Manjeet Kumar  
Java Backend Developer  
Spring Boot | Microservices | REST APIs | Security  

---

⭐ If you like this project, feel free to star the repository!
