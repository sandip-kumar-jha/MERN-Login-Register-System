# MERN Login Register System :-

A simple MERN Stack Authentication project that allows users to register and log in using MongoDB Atlas as the database.

## Features

- User Registration
- User Login
- MongoDB Atlas Database
- React Router Navigation
- Axios API Requests
- Express REST API
- Responsive UI using Bootstrap
- Home Page Redirect after Successful Login

## Tech Stack

### Frontend
- React.js
- Vite
- Bootstrap
- Axios
- React Router DOM

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- CORS

## Project Structure

```
Login Register/
│
├── client/
│   ├── src/
│   │   ├── Signup.jsx
│   │   ├── Login.jsx
│   │   ├── Home.jsx
│   │   ├── App.jsx
│   │   └── main.jsx
│   │
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── models/
│   │   └── Employee.js
│   │
│   ├── index.js
│   └── package.json
│
└── README.md
```

## Installation

### Clone Repository

```bash
https://github.com/sandip-kumar-jha/MERN-Login-Register-System
```

### Frontend

```bash
cd client
npm install
npm run dev
```

### Backend

```bash
cd server
npm install
node index.js
```

## API Endpoints

### Register User

```
POST /register
```

Request Body

```json
{
  "name": "Sandip",
  "email": "sandip@gmail.com",
  "password": "123456"
}
```

---

### Login User

```
POST /login
```

Request Body

```json
{
  "email": "sandip@gmail.com",
  "password": "123456"
}
```

## Database

MongoDB Atlas is used to store user information.

Collection:

```
employees
```

Document Example

```json
{
  "_id": "...",
  "name": "Sandip",
  "email": "sandip@gmail.com",
  "password": "123456"
}
```

## Screens

- Register Page
- Login Page
- Home Page

## Future Improvements

- Password Hashing using bcrypt
- JWT Authentication
- Protected Routes
- Logout Functionality
- Form Validation
- Error Handling
- User Dashboard

## Author

Sandip Kumar jha


IIT Patna

GitHub: https://github.com/your-username
