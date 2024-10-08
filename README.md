# Task Manager App

A simple task management application built with React and FastAPI.

## Project Understanding

This project consists of a React frontend and a FastAPI backend, performing CRUD operaion. The frontend fetches data from the backend API to display a list of tasks, allowing users to create, read, update, and delete tasks.

### Frontend (React)

- **app.js:** The main React component file responsible for fetching tasks from the FastAPI backend using the `axios` library. It then displays the tasks in a user-friendly list format.

### Backend (FastAPI)

- **main.py:** The FastAPI backend file defining routes for various task operations, such as creating, reading, updating, and deleting tasks. The tasks are stored in an in-memory database (`tasks_db`). The backend is configured to allow Cross-Origin Resource Sharing (CORS) from `http://localhost:3000` to enable communication with the React frontend.

