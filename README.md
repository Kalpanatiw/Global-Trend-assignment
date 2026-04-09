# Task Manager Application

A simple full stack Task Manager with frontend and backend.

## Tech Stack
- Frontend: Plain JavaScript, HTML, CSS
- Backend: Node.js, Express.js
- Storage: In-memory

## Features
- Create, view, update, delete tasks
- Mark tasks as completed
- Edit task titles
- Filter by completed/incomplete status
- Loading and error states

## Setup

### Prerequisites
- Node.js installed

### Installation
```bash
cd "Global Trend"
npm install
```

### Run
```bash
npm start
```

Server runs at http://localhost:3000

Open `index.html` in browser or serve it via a local server.

## API Endpoints
- GET /tasks - Get all tasks
- POST /tasks - Create task
- PATCH /tasks/:id - Update task
- DELETE /tasks/:id - Delete task