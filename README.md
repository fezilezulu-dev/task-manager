# Task Manager Application

A full-stack Task Manager web application built using React (frontend), Node.js & Express (backend), and MongoDB (database).

The application helps users manage daily tasks efficiently while also using weather data to improve planning and decision-making.

Project Status: Under active development

---

## Features

### User System
- User registration and login
- Secure authentication using JWT
- User profile management (name, email, location)

### Task Management
- Create, update, and delete tasks
- Add task title, date, time, priority, and notes
- Mark tasks as completed
- Separate views for active and completed tasks

### Weather-Based Planning
The weather feature helps users plan their tasks ahead of time by showing forecast conditions based on their location.

This allows users to make better scheduling decisions depending on upcoming weather conditions.

- Real-time weather data using OpenWeather API
- Weekly weather forecast based on user location
- Weather-based planning suggestions (rain, heat, clear conditions)
- Helps users decide when to complete outdoor or time-sensitive tasks

### UI Features
- Clean and responsive dashboard
- Priority indicators (Low, Medium, High with colors)
- Completed tasks shown with strikethrough styling

---

## Tech Stack

- Frontend: React, Axios, CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT
- API Integration: OpenWeather API

---

## Project Structure

### Backend
- models/ → User and Task schemas
- routes/ → Authentication, task, and weather routes
- server.js → Backend entry point

### Frontend
- pages/TaskPage.js → Main dashboard
- pages/Login.js → Login screen
- pages/Register.js → Signup screen
- pages/Profile.js → User profile management
- components/ → Reusable UI components

---

## Installation and Setup

### Clone Repository
```bash
git clone https://github.com/your-username/task-manager.git
cd task-manager
Backend Setup
cd backend
npm install

Create .env file:

MONGO_URI=mongodb://127.0.0.1:27017/taskmanager
JWT_SECRET=your_secret_key

Start backend:

npm start

Backend runs at:

http://localhost:5000
Frontend Setup
cd frontend
npm install
npm run dev

Frontend runs at:

http://localhost:3000
Database Example
Task Document
{
  "title": "Study React",
  "date": "2026-05-20",
  "time": "15:00",
  "priority": "High",
  "notes": "Finish hooks topic",
  "completed": false
}
User Document
{
  "name": "John Doe",
  "email": "john@example.com",
  "location": "Durban"
}
Project Highlights
Full-stack MERN-style architecture
Real-world task management system
Weather-based planning integration
Clean separation of frontend and backend
Beginner-friendly but scalable structure
Project Status

##Under Construction

This project is still being actively developed. Planned improvements include:

Task editing improvements
Notifications and reminders
Calendar view integration
UI/UX improvements
Mobile responsiveness
