# Jobify – Job Management Backend API

Jobify is a backend application built with **Node.js, Express, and MongoDB** that provides secure APIs for job tracking, authentication, and user management.  
It follows modern backend practices including JWT authentication, centralized error handling, middleware-based design, and role-based access.


## Features

- **Authentication & Authorization**
  - Register new users and log in securely
  - JWT authentication with cookies
  - Role-based access (admin/user)

- **Job Management**
  - Create, update, delete, and fetch jobs
  - Jobs are isolated per user – each user sees only their own jobs

- **User Management**
  - Update user profile details
  - View current user info
  - Admin capabilities for managing users

- **Error Handling & Security**
  - Centralized error handler 
  - 404 handler for unknown routes
  - Secure cookie handling with 
  - Environment variables with 

- **Developer Tools**
  - `morgan` for request logging
  - `express-async-errors` for clean async error handling
  - `mongoose` for MongoDB integration


## Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB & Mongoose**
- **JWT Authentication**
- `cookie-parser`, `dotenv`, `morgan`, `express-async-errors`




