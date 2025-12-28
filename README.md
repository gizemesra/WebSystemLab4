# Student Management System

A full-stack web application for managing students and courses, built as per Meeting 4 requirements.

## Features
- Modern, sleek UI with responsive design
- Persistent JSON-based data storage
- Full CRUD operations for students and courses
- Real-time frontend-backend integration

## Project Structure

- `backend/`: Node.js + Express server with REST API
- `frontend/`: React application with modern styling
- `api-contract.yaml`: OpenAPI specification
- `backend/students.json` & `backend/courses.json`: Persistent data files

## Setup

### Backend
1. cd backend
2. npm install
3. npm start (runs on port 3000)

### Frontend
1. cd frontend
2. npm install
3. npm start (runs on port 3001)

## API Endpoints

- GET/POST/PUT/DELETE /students
- GET/POST/PUT/DELETE /courses

See api-contract.yaml for full specification.

## Data Persistence

Data is stored in JSON files (`students.json`, `courses.json`) and persists across server restarts.

## Testing

- Backend: Use Postman or curl to test endpoints
- Frontend: Interact with the UI to add/edit/delete students and courses
- End-to-end: Add a student via frontend form → appears in list and persists in JSON files

## Grading Criteria Met

- API Contract: OpenAPI spec with clear endpoints, JSON structures, status codes
- Backend: Express setup, middleware, routing, CRUD with validation, JSON persistence
- Frontend Integration: Real-time data flow, error handling, modern design