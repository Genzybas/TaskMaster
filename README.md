# **TaskMaster - A Task Management System**

TaskMaster is a full-stack task management web application designed to help users efficiently organize, prioritize, and track their tasks. This README outlines the key features, tech stack, setup instructions, and live demo links for the project.

---

## **Overview**

TaskMaster enables users to:
- Create, update, and delete tasks.
- Organize tasks by priority and deadlines.
- Search and filter tasks for better task tracking.

The project ensures scalability, security, and optimized performance for a smooth user experience.

---

## **Tech Stack**

- **Backend**: Node.js, Express.js  
- **Database**: MongoDB  
- **Frontend**: HTML, CSS, JavaScript  
- **Testing**: Jest, Supertest  
- **Deployment**: Fly.io (Backend), Vercel (Frontend)  

---

## **Features**

### **1. User Authentication**
- Secure user registration and login using JWT.
- Password hashing with bcrypt for enhanced security.

### **2. Task Management**
- Add tasks with the following attributes:
  - Title
  - Description
  - Priority (Low, Medium, High)
  - Deadline
- Update and delete tasks seamlessly.

### **3. Task Filtering and Searching**
- Filter tasks by priority or due date.
- Search tasks using keywords in the title or description.

### **4. User Interface**
- Fully responsive design.
- AJAX and Fetch API for asynchronous task management.

### **5. Security Features**
- Input validation using Joi.
- Protection against XSS and SQL Injection attacks.

---

## **Database Design**

### **User Schema**
```json
{
  "id": "string",
  "name": "string",
  "email": "string",
  "password": "hashed_string"
}

Testing
Tools: Jest, Supertest
Key Tests:
User authentication routes.
CRUD operations for tasks.
Input validation and error handling.
Test Results:

20+ test cases covering core functionalities and edge cases.
Deployment
Backend: Deployed on Fly.io
Backend API 
Frontend: Deployed on Vercel
Frontend App

### View [Demo](https://.com)

## Become a contributor

Feel free to open [Pull requests](https://docs.github.com/about-pull-requests)

<p align="center">
	Thanks for reading!
</p>

