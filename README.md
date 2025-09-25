# 📝 Todo App (Spring Boot + React)

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Java](https://img.shields.io/badge/Java-17-blue.svg)](https://www.oracle.com/java/)
[![React](https://img.shields.io/badge/React-18-blue.svg)](https://reactjs.org/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2-green.svg)](https://spring.io/projects/spring-boot)

A modern **Todo Application** built using **Spring Boot** (backend) and **React** (frontend) to help users manage tasks efficiently. It includes **CRUD operations**, **REST APIs**, and a **responsive React interface**.

---

## 🌟 Features

- Add, update, delete, and view tasks
- Mark tasks as complete or pending
- Persistent storage using **MySQL**
- RESTful API design
- Responsive frontend built with **React.js**
- Error handling and input validation
- Future-ready for JWT authentication and user management

---

## 🛠 Tech Stack

| Layer        | Technology                  |
|--------------|----------------------------|
| Frontend     | React.js, HTML, CSS, Axios |
| Backend      | Spring Boot, Java 17       |
| Database     | MySQL                      |
| Build Tools  | Maven, npm                 |
| API Testing  | Postman                    |

---

## 🔧 Installation & Setup

### Backend (Spring Boot)
1. Clone the repository:  
   ``bash
   git clone https://github.com/NAGARJUN0910/todo-springboot-react.git
   cd todo-springboot-react/backend

2.  Configure MySQL database in application.properties:
    spring.datasource.url=jdbc:mysql://localhost:3306/tododb
    spring.datasource.username=root
    spring.datasource.password=yourpassword
    spring.jpa.hibernate.ddl-auto=update

3. Build and run the Spring Boot app:

4. Backend will run at: http://localhost:8080
 Frontend (React)
1.Navigate to the frontend folder:
       cd ../frontend
2.Install dependencies:
       npm install
3.Start the React development server:
       npm start
4.Frontend will run at: http://localhost:3000

| Method | Endpoint          | Description          |
| ------ | ----------------- | -------------------- |
| GET    | `/api/todos`      | Fetch all todos      |
| GET    | `/api/todos/{id}` | Fetch todo by ID     |
| POST   | `/api/todos`      | Create new todo      |
| PUT    | `/api/todos/{id}` | Update existing todo |
| DELETE | `/api/todos/{id}` | Delete todo by ID    |

✅ Future Improvements
-User authentication & authorization (JWT)
-Task categories & priorities
-Dark mode support
-Deployment on cloud platforms (AWS / Heroku / Vercel)
-Unit and integration testing

📧 Author

Nagarjun B N
Email: nagarjun0910@gmail.ocm.com
GitHub: https://github.com/NAGARJUN0910
Build something amazing today! 🚀

   
