# Authentication-System

🔐 Authentication System (Node.js + JWT)

A secure and scalable authentication system built using Node.js, Express, MongoDB, bcrypt.js, and JWT.
This project provides user registration, login, and token-based authentication, ideal for internal platforms or job portals.

🚀 Features
✅ User Authentication

Register new users (interns/admins)

Secure login with JWT tokens

Password hashing using bcrypt.js

✅ Security

Protected routes using JWT middleware

Token validation on every request

Sanitized inputs and secure error handling

✅ API Endpoints
Method	Endpoint	Description
POST	/api/auth/register	Register a new user
POST	/api/auth/login	Authenticate user & return token
GET	/api/auth/me	Fetch logged-in user (requires token)
🛠 Tech Stack

Node.js + Express – Backend server

MongoDB + Mongoose – Database & schema modeling

bcrypt.js – Secure password hashing

JSON Web Token (JWT) – Authentication & route protection

Postman – Testing APIs

📦 Installation
git clone https://github.com/yourusername/authentication-system.git
cd authentication-system
npm install


Create a .env file:

PORT=5000
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key


Run the server:

npm start

📌 Outcome

This project delivers a secure, reliable, and production-ready authentication system that can be easily integrated into job portals, dashboards, or any internal applications.