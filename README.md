# 💸 Expense Management System

A full-stack expense management and group expense tracking platform that allows users to manage personal expenses, create groups, split expenses, and handle subscriptions with secure authentication and role-based access control.

This project is designed to simulate a production-style finance management workflow, focusing on scalable backend architecture, secure authentication, permission-based access, and clean separation of business logic.

📂 Repositories

🔗 Frontend: [expense-react-client](https://github.com/Uttam222/expense-react-client)

🔗 Backend: [expense-server](https://github.com/Uttam222/expense-server)

✨ Key Features

👤 User Side

- Secure user authentication and authorization
- Login using email/password and Google authentication
- Create and manage expense groups
- Track and manage shared expenses
- Responsive dashboard for monitoring expenses
- Subscription management for premium plans
- Protected routes and personalized user experience

👥 Group & Expense Management

- Create multiple expense groups
- Add and manage group members
- Track shared expenses inside groups
- Organized expense handling with scalable group logic

🔐 Authentication & Security

- JWT-based authentication system
- Protected API endpoints using middleware
- Google OAuth login integration
- Password encryption using bcrypt
- Role-based access control (RBAC)

💳 Payments & Subscription System

- Razorpay integration for subscription payments
- Monthly and yearly subscription support
- Secure payment verification workflow

🧱 Tech Stack

Frontend

- React
- Redux Toolkit
- React Router
- Axios
- Bootstrap
- Vite

Backend

- Node.js
- Express.js
- MongoDB + Mongoose
- JWT Authentication
- Google OAuth
- Razorpay Integration

🏗 Project Architecture

This project is split into separate repositories for scalability and maintainability.

🔹 Main Repository (This Repo)

Acts as the project overview and documentation hub while linking the frontend and backend repositories.

🔹 Frontend Repository

📁 expense-react-client

Handles UI rendering, protected routes, dashboard management, subscriptions, and API communication.

🔹 Backend Repository

📁 expense-server

Implements authentication, RBAC, payment handling, APIs, middleware, and database operations.

🔐 Security & Access Control

- JWT-secured authentication system
- Backend middleware-based authorization
- Role and permission management system
- Protected frontend routes

📌 Application Flow (High Level)

1. User registers or logs in
2. JWT token is generated after authentication
3. User creates or joins expense groups
4. Expenses are managed and tracked
5. Subscription plans are activated using Razorpay

🚀 Why This Project Matters

This project goes beyond CRUD:

- Demonstrates real-world authentication and RBAC implementation
- Shows scalable backend architecture
- Includes payment gateway integration
- Structured like a production-ready finance platform

🧑‍💻 Author

Built by Uttam  
Focused on backend architecture, scalable systems, and real-world application development.

📖 About

Production-style full-stack expense management system with React, Node.js, MongoDB, JWT authentication, RBAC, and Razorpay integration.
