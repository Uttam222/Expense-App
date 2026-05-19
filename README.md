#  💸Expense-App

A full-stack expense management and group expense tracking platform that allows users to manage personal expenses, create groups, split expenses, and handle subscriptions with secure authentication and role-based access control.

This project is designed to simulate a production-style finance management workflow, focusing on scalable backend architecture, secure authentication, permission-based access, and clean separation of business logic.

📂 Repositories

🔗 Frontend: expense-react-client
🔗 Backend: expense-server

✨ Key Features
👤 User Side
Secure user authentication and authorization
Login using email/password and Google authentication
Create and manage expense groups
Track and manage shared expenses
Responsive dashboard for monitoring expenses
Subscription management for premium plans
Protected routes and personalized user experience
👥 Group & Expense Management
Create multiple expense groups
Add and manage group members
Track shared expenses inside groups
Organized expense handling with scalable group logic
Clean and modular group management system
🔐 Authentication & Security
JWT-based authentication system
Protected API endpoints using middleware
Google OAuth login integration
Password encryption using bcrypt
Role-based access control (RBAC)
Permission-based route protection
💳 Payments & Subscription System
Razorpay integration for subscription payments
Monthly and yearly subscription support
Secure payment verification workflow
Webhook handling for payment events
Subscription management dashboard
🧠 Smart Architecture
Clean separation between frontend and backend
Scalable folder structure and modular architecture
Reusable middleware and utility functions
Centralized API handling and authorization flow
Production-oriented backend structure
🧱 Tech Stack
Frontend
React
React Router
Redux Toolkit
Axios
Bootstrap & React Bootstrap
Vite
Backend
Node.js
Express.js
MongoDB + Mongoose
JWT Authentication
Google OAuth
Razorpay Integration
Nodemailer
Database
MongoDB
Collections for Users, Groups, Roles, Permissions, and Payments
🏗 Project Architecture

This project is divided into separate repositories for better scalability and maintainability.

🔹 Main Repository

Acts as the project overview and documentation hub while connecting the frontend and backend repositories.

🔹 Frontend Repository

📁 expense-react-client

Handles UI rendering, protected routes, dashboard management, group management, subscriptions, and API communication.

🔹 Backend Repository

📁 expense-server

Implements authentication, RBAC, payment handling, subscription logic, APIs, middleware, and database operations.

🔐 Security & Access Control
JWT-secured authentication system
Backend middleware-based authorization
Role and permission management system
Protected frontend routes
Encrypted password storage using bcrypt
Secure payment verification using Razorpay webhooks
📌 Application Flow (High Level)
User registers or logs in
JWT token is generated after authentication
User creates or joins expense groups
Expenses are managed and tracked within groups
Subscription plans can be activated using Razorpay
Permissions and protected routes are enforced automatically
🚀 Why This Project Matters

This project goes beyond a basic CRUD application:

Demonstrates real-world authentication and RBAC implementation
Shows scalable backend architecture and middleware usage
Includes payment gateway integration with subscription handling
Focuses on clean code organization and modular design
Structured like a production-ready finance platform
🧑‍💻 Author

Built by Uttam
Focused on backend architecture, scalable systems, authentication, and real-world application development.

📖 About

Production-style full-stack expense management system with React, Node.js, MongoDB, JWT authentication, RBAC, and Razorpay integration.
