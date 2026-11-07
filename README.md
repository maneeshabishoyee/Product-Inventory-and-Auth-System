# 📦 Product Inventory and Authentication System

A Full Stack Product Inventory Management System developed using Java, Spring Boot, React.js and MySQL.

## 🚀 About The Project

The Product Inventory and Authentication System is a web-based application designed to manage products, user authentication and inventory operations.

The application provides secure user registration, login, email OTP verification and product management through REST APIs.


## ✨ Features

- 🔐 User registration and login
- 📧 Email OTP verification
- 🔑 JWT-based authentication
- 👥 Role-based access control
- 📦 Product CRUD operations
- 🔍 Product search and filtering
- 📊 Inventory management
- 🌐 REST API integration
- 📱 Responsive frontend

## 🛠️ Technology Stack

### Backend
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)



## 📂 Project Structure

```text
Product-Inventory-and-Auth-System/
│
├── PRODUCT_SERVICE/
│   ├── src/
│   ├── .mvn/
│   ├── pom.xml
│   ├── mvnw
│   ├── mvnw.cmd
│   └── README.md
│
├── product-service-frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   ├── package-lock.json
│   └── vite.config.js
│
├── .gitignore
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone Repository

```bash
git clone https://github.com/maneeshabishoyee/Product-Inventory-and-Auth-System.git
```

### 2. Backend Setup

Navigate to the backend folder:

```bash
cd PRODUCT_SERVICE
```

Configure your MySQL database and update the database credentials in the Spring Boot application configuration file.

Make sure your database and email configuration are correct.

Run the backend:

**Windows:**

```bash
mvnw.cmd spring-boot:run
```

**Or use Maven:**

```bash
mvn spring-boot:run
```

### 3. Frontend Setup

Open another terminal:

```bash
cd product-service-frontend
```

Install dependencies:

```bash
npm install
```

Start the frontend:

```bash
npm run dev
```

Open the local URL displayed in your terminal.

## 📖 API Documentation

Swagger UI is available through Springdoc OpenAPI.

After starting the backend, visit:

```text
http://localhost:8080/swagger-ui/index.html
```

## 🧪 Testing

Run backend tests:

```bash
mvn test
```

Run frontend lint:

```bash
npm run lint
```

Build frontend:

```bash
npm run build
```

## 🎯 Learning Outcomes

- Understanding Java and Spring Boot
- Building RESTful APIs
- Implementing JWT Authentication
- Working with Spring Security
- Database integration using MySQL and JPA
- Connecting React frontend with backend APIs
- Implementing CRUD operations
- Understanding full-stack application development

## 👩‍💻 Developer

**Maneesha Manaswini Bishoyee**

Java Full Stack Developer

**Technical Skills:** Java | Spring Boot | React.js | MySQL | Hibernate | REST APIs | JWT

GitHub: https://github.com/maneeshabishoyee

LinkedIn: Add your LinkedIn profile URL here.

---

⭐ If you find this project useful, feel free to explore the repository!
