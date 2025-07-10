# 📚 Book Store Management System

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![MySQL](https://img.shields.io/badge/MySQL-00758F?style=for-the-badge&logo=mysql&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-F76935?style=for-the-badge&logo=postman&logoColor=white)

A full-stack **Book Store Management System** built using **Spring Boot** for the backend and **React.js** for the frontend. Designed with a microservices architecture and role-based access (User/Admin), the system allows users to browse and purchase books and admins to manage inventory and track orders.

---

## 🛠️ Tech Stack

### 🔙 Backend
- Java 11
- Spring Boot
- Spring Security (Authentication & Authorization)
- Spring Cloud Gateway
- Eureka (Service Discovery)
- RESTful APIs (Tested using Postman and Swagger)
- MySQL (Database)
- Maven (Dependency Management)

### 🌐 Frontend
- React.js
- Axios (API Calls)
- HTML5, CSS3, JavaScript

---

## ✨ Features

### 👥 User Module
- View books by **category**, **author**, and **price range**
- View book details
- Add books to cart
- Checkout and place orders

### 🔐 Admin Module
- Add/update/delete books, authors, categories
- Manage stock
- Track order statuses
- View revenue statistics

---

## 📷 Screenshots *(Optional)*

> Add screenshots here to showcase UI and features  
> (e.g., user book listing, admin dashboard, order summary, etc.)

---

## 🚀 Getting Started

### 📦 Prerequisites
- Java 11+
- Node.js and npm
- MySQL
- Maven

### ⚙️ Backend Setup
```bash
cd backend
mvn clean install
mvn spring-boot:run

🌐 Frontend Setup
cd frontend
npm install
npm start

🧪 API Testing
Use Postman or Swagger UI to test endpoints

Swagger available at: http://localhost:8080/swagger-ui.html

📂 Project Structure
📁 backend
 ┣ 📁 controller
 ┣ 📁 service
 ┣ 📁 repository
 ┣ 📁 entity
 ┣ 📁 config
 ┣ 📁 exception
 ┗ 📜 application.properties

📁 frontend
 ┣ 📁 components
 ┣ 📁 pages
 ┣ 📁 services (Axios calls)
 ┗ 📜 App.js

🧠 Concepts Applied
Microservices architecture

RESTful API design

Feign Client (for service-to-service communication)

Role-Based Access Control (RBAC)

Exception handling (Global)

Axios for client-server communication

Secure login using Spring Security

📜 License
This project is for educational/demo purposes.

🙋‍♂️ About Me
Preetham Dundigalla
Programmer Analyst Trainee @ Cognizant
AWS Certified Solutions Architect | NASA Space Apps 2024 Global Nominee
LinkedIn | Email


⭐ If you like this project, give it a star!
---

Let me know if you'd like this split into **separate READMEs** for backend and frontend folders—or if you'd like me to **auto-generate it for your GitHub repo** based on a link!

