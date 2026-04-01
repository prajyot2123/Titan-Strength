# AI-Based Fitness Tracker (Titan Strength)

A full-stack AI-powered fitness tracking web application built with MongoDB, Express.js, React, and Node.js.  
It helps users log workouts, track progress, and interact with an integrated chatbot for fitness support.

## 🚀 Project Overview

This project provides a modern fitness management platform where users can:

- Sign up and log in securely
- Track cardio and resistance workouts
- View exercise history and progress
- Use an AI chatbot for fitness-related assistance
- Manage fitness data in a clean and responsive interface

## ✨ Key Features

- Secure user authentication using JWT
- Cardio workout creation, retrieval, and deletion
- Resistance workout creation, retrieval, and deletion
- Workout history management
- AI chatbot integration for guidance/support
- Responsive frontend built with React
- RESTful backend APIs with Express and MongoDB

## 🛠️ Tech Stack

Frontend:
- React
- CSS
- Axios

Backend:
- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- Bcrypt

## 📁 Project Structure

- client: React frontend
- server: Node + Express backend
- routes/controllers/models: API logic and database schemas
- utils: Authentication and helper utilities

## ⚙️ Installation and Setup

1. Clone the repository

~~~bash
git clone https://github.com/prajyot2123/Titan-Strength.git
~~~

2. Install dependencies for root, client, and server

~~~bash
cd client
npm install
cd ../server
npm install
~~~

3. Configure environment variables in server

Create a .env file in the server folder and add:

~~~env
MONGODB_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-secret-key>
~~~

4. Run backend server

~~~bash
cd server
npm start
~~~

5. Run frontend client

~~~bash
cd client
npm start
~~~

The app will run on:
- Frontend: http://localhost:3000
- Backend: http://localhost:3001 (or configured port)

## 🔐 Authentication

- JWT-based authentication is used for protected APIs.
- Passwords are securely hashed using bcrypt before storing in MongoDB.

## 👩‍💻 Author

Your Name  
GitHub: https://github.com/prajyot2123  
LinkedIn: https://www.linkedin.com/in/prajyot-deshpande-667b11250
