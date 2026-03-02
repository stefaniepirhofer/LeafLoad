# Food Delivery Web Application

## Description

This project is a full-stack food delivery web application developed as part of a university course.  
It demonstrates a modern client-server architecture using Angular for the frontend and NestJS for the backend, including authentication, restaurant management, and interactive UI functionality.

---

## Architecture

The application follows a structured full-stack architecture:

- **Frontend:** Angular (Single Page Application)
- **Backend:** NestJS (REST API)
- **Database:** PostgreSQL
- **Authentication:** JWT-based authentication
- **Containerization:** Docker support

The frontend communicates with the backend via RESTful API endpoints.  
Authentication is handled using JSON Web Tokens (JWT).

---

## Features

- User registration and login (JWT authentication)
- Restaurant creation and management
- Drag-and-drop functionality in the UI
- Seeded test users and restaurants
- Full client-server integration

---

## Repository Structure

root/
  frontend/ # Angular application
  backend/ # NestJS API
  docker-compose.yml
  README.md


The project is maintained in a single repository with separate folders for frontend and backend.

---

## Installation

Make sure Docker and Docker Compose are installed.

```bash
docker-compose up --build
```

Backend
```bash
cd backend
npm install
npm start
```

Frontend
```bash
cd frontend
npm install
npm start
```

**Disclaimer**
This application was developed for academic purposes and is not production-ready.
