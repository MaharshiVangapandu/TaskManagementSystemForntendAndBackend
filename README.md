Task Management System

Description

This is a simple Task Management System built using React for the frontend and Spring Boot for the backend. The application allows users to create, update, delete, and view tasks with a simple and interactive UI.

Features

Frontend (React)

Add tasks with title, description, and status (Pending/Completed).

Display a list of tasks with options to edit or delete.

API calls to the backend to fetch, create, update, and delete tasks.

Uses React Hooks and functional components.

Uses Axios for API requests.

Styled using Tailwind CSS.

Backend (Spring Boot)

REST API using Spring Boot.

Endpoints:

POST /tasks → Create a new task

GET /tasks → Get all tasks

GET /tasks/{id} → Get task by ID

PUT /tasks/{id} → Update task details

DELETE /tasks/{id} → Delete a task

Uses Spring Boot with Spring Data JPA to interact with MySQL/PostgreSQL.

Implements basic exception handling and validation.
