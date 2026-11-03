# 📦 Product Inventory and Authentication System

A Full Stack Product Inventory Management System developed using Java, Spring Boot, React.js and MySQL.

## 🚀 About The Project

The Product Inventory and Authentication System is a web-based application designed to manage products, user authentication and inventory operations.

The application provides secure user registration, login, email OTP verification and product management through REST APIs.

## ✨ Features

### 🔐 User Authentication
- User Registration
- User Login
- Email OTP Verification
- JWT Authentication
- Spring Security
- Secure Password Handling

### 📦 Product Management
- Add New Products
- View Product Details
- Update Product Information
- Delete Products
- Search Products
- Category-based Product Management
- Pagination
- Price Range Filtering

### 📊 Inventory Management
- Increase Product Stock
- Decrease Product Stock
- Manage Product Availability
- Product Status Management

### 💻 Frontend
- Responsive User Interface
- React Components
- Login and Registration Pages
- Product Management Interface
- API Integration using Axios
- Toast Notifications

## 🛠️ Technologies Used

**Backend**
- Java 17
- Spring Boot
- Spring MVC
- Spring Data JPA
- Spring Security
- Hibernate
- JWT
- Lombok
- Maven

**Frontend**
- React.js
- JavaScript
- Vite
- Tailwind CSS
- Axios
- React Router
- React Toastify

**Database**
- MySQL

**Tools**
- IntelliJ IDEA
- Visual Studio Code
- Postman
- Swagger UI
- Git and GitHub

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