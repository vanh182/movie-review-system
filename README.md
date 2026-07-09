# 🎬 Movie Review System

> A full-stack movie review application built with React, Node.js, Express.js, and MongoDB, allowing users to search movies and manage reviews through a RESTful API.

![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-Framework-black?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?logo=mongodb)
![REST API](https://img.shields.io/badge/API-REST-blue)

---

# 📖 Overview

Movie Review System is a full-stack web application that enables users to browse movies, search by different criteria, and manage movie reviews. The application is built with **React** for the frontend and **Node.js**, **Express.js**, and **MongoDB** for the backend, following a RESTful architecture.

---

# ✨ Features

* 🎬 Browse movie information
* 🔍 Search movies by title
* ⭐ Filter movies by rating
* 💬 View reviews for each movie
* ➕ Add new reviews
* ✏ Edit existing reviews
* ❌ Delete reviews
* 🌐 RESTful API integration

---

# 🛠 Tech Stack

| Category | Technologies |
| -------- | ------------ |
| Language | JavaScript (ES6) |
| Frontend | React |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| API | RESTful API |

---

# 🏗 Architecture

```text
React Frontend
       │
       │ REST API
       ▼
 Node.js + Express
       │
       ▼
   MongoDB Database
```

The application follows a client-server architecture where the React frontend communicates with the Express.js backend through REST APIs. Movie and review data are stored and managed in MongoDB.

---

# 📂 Project Structure

```text
movie-review-system
├── backend/
│   ├── api/
│   ├── dao/
│   ├── controller/
│   ├── routes/
│   └── server.js
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── services/
│   │   ├── pages/
│   │   └── App.js
│   └── package.json
│
└── README.md
```

---

# 📸 Screenshots

### 🔍 Movie Search

![Movie Search](https://github.com/vanh182/Movie_reviews/assets/118065256/aac0dd39-1058-4784-a393-2c2261470eea)

### 💬 Movie Reviews

![Movie Reviews](https://github.com/vanh182/Movie_reviews/assets/118065256/b0fb8e37-f4b4-40fe-9966-26b062f078b6)

### ✍ Review Management

![Review CRUD](https://github.com/vanh182/Movie_reviews/assets/118065256/0f42625a-4f7c-447d-b93c-fd765cc4712c)

---

# 🚀 How to Run

## Prerequisites

* Node.js
* npm or Yarn
* MongoDB

## Clone the repository

```bash
git clone https://github.com/your-username/movie-review-system.git
cd movie-review-system
```

## Install dependencies

### Backend

```bash
cd backend
npm install
```

### Frontend

```bash
cd ../frontend
npm install
```

## Configure Environment Variables

Create a `.env` file inside the backend directory.

Example:

```env
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

## Run the backend

```bash
cd backend
npm start
```

## Run the frontend

```bash
cd frontend
npm start
```

The application will be available at:

```text
Frontend: http://localhost:3000
Backend : http://localhost:5000
```

---

# 🚀 Future Improvements

* 👤 User authentication
* ❤️ Favorite movies
* 🎭 Filter movies by genre
* 📄 Movie details page
* 👍 Like and dislike reviews
* 📱 Responsive mobile interface
* 🐳 Docker deployment
* 🧪 Unit and integration testing

---

# 📄 License

This project was developed for educational purposes.

Feel free to use, modify, and distribute this project for learning and personal development.

