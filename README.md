# Job Portal

## 📌 Project Overview
A Job Portal application developed using Spring Boot that allows companies to manage job postings and enables users to explore job opportunities. The project follows a layered architecture using Controller, Service, Repository, and Entity classes.

## ✨ Features
- Company Management
- Job Management
- Contact Form API
- MySQL Database Integration
- RESTful APIs
- DTO-based Request & Response Handling
- Global Exception Handling
- Audit Support
- Docker Compose Configuration
- layered Architecture
- User Authentication (JWT)
- Company Login
- Job Seeker Registration
- Resume Upload
- Apply for Jobs
- Search & Filter Jobs
- Email Notifications
- Admin Dashboard
- Pagination & Sorting
- Swagger API Documentation

## 🛠️ Tech Stack
- Java
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Docker
- Git & GitHub

## 📂 Project Structure
src/
├── main/
│   ├── java/
│   ├── resources/
│   └── ...
└── test/

## ⚙️ Prerequisites
- Java 17+
- Maven
- MySQL
- Git

## 🚀 Installation
1. Clone the repository.
2. Configure the MySQL database.
3. Update `application.properties`.
4. Run the application using Maven.

## 📡 API Endpoints
### Company APIs
- GET /companies
- POST /companies
- PUT /companies/{id}
- DELETE /companies/{id}

### Contact APIs
- POST /contact

## 🗄️ Database
The project uses MySQL with SQL scripts available under:
- jobportal-schema.sql
- jobportal-data.sql

## 🐳 Docker
Run using:
docker compose up

## 👨‍💻 Author
Vivesh Konathala
