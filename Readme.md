# 📝 Task Manager – MERN Stack Project

**Task Manager** is a simple and efficient task management application built with the MERN stack (MongoDB, Express.js, React, Node.js). It is designed to help teams manage and complete their tasks easily. This project is especially useful for small teams or companies that want to have a lightweight in-house task management tool.

To make things even easier, the project includes **Docker support**, allowing you to run or preview it quickly without manual configuration.

---

## 🚀 Overview

This application supports two main roles:

- **Admin (Team Leader)**: Creates, assigns, and manages tasks, and monitors the progress of team members.
- **User (Team Member)**: Views assigned tasks and updates their progress until completion.

With a full MERN stack architecture and Docker integration, running and testing the app is smooth and hassle-free.

---

## 🔧 Features

### 🔐 Authentication
- Secure login/logout system
- Role-based route protection

### 👑 Admin Features
- **Dashboard**:
  - View global task stats: Pending, In-Progress, Completed
  - View total tasks per team member
- **Task Management**:
  - Create / Edit / Delete tasks
  - Assign tasks to users
  - View all tasks in the system
- **Team Overview**:
  - View list of users
  - See how many tasks are assigned to each user

### 🙋‍♂️ User Features
- **Personal Dashboard**:
  - View stats for your own tasks (Pending, In-Progress, Completed)
- **Task Actions**:
  - View list of your assigned tasks
  - Update task progress

---

## 📦 Tech Stack

- **Frontend**: React (Vite) + Tailwind CSS 4.1
- **Backend**: Node.js v22.15.0, Express.js
- **Database**: MongoDB
- **Containerization**: Docker
- **Package Manager**: npm

---

## ✅ Prerequisites

Make sure you have the following installed before running the project:

- [Node.js v22.15.0+](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/) (or MongoDB Atlas)
- [Docker & Docker Compose](https://www.docker.com/)

---

## 🐳 Run with Docker

To run the app using Docker:

```bash
docker-compose up --build

```

## 📂 Project Structure

```sh
└── sd-taskmanager/
    ├── backend     # Backend (Express)
    ├── frontend    # Frontend (Vite + React)
    ├   └── Task-Manager
    └── docker-compose.yml
```
