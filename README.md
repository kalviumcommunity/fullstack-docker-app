# fullstack-docker-app

# Mini Project - 1

This is a mini project setup for a **React + Express + PostgreSQL** application, prepared for containerization with Docker.

## Folder Structure

fullstack-docker-app/
├── backend/
│ ├── app.js
│ └── package.json
├── frontend/
│ ├── package.json
│ └── src/
│ └── App.js
├── db-data/ # For database volume
├── docker-compose.yml # Empty for now
├── .env # Empty for future use
└── README.md



# Mini Project - 2

updated the backend and frontend folder by adding dockerfile and committed the changes.

Containerizing a Full Stack App with Docker Compose
📌 Overview
This project is part of Learning Sprint #2 - Introduction to Containerisation with Docker.
In Mini Project-2, we successfully containerized the backend and database services using Docker Compose, ensuring both are running together with persistent data.

🛠 Tech Stack
Backend: Node.js / Express

Database: PostgreSQL

Containerisation: Docker, Docker Compose

# Mini Project - 3

Mini Project 3 - Fullstack Docker App Setup
Overview
This project demonstrates:

Persistent database storage using Docker volumes with PostgreSQL

Docker container orchestration with docker-compose

Debugging and inspecting running containers via Docker commands

Application stability verified after container stop/start cycles

Project Structure

fullstack-docker-app/
│
├── backend/
│   ├── Dockerfile
│   ├── package.json 
│   └── index.js
│
├── frontend/
│   ├── Dockerfile
│   ├── package.json
│   └── src/
│
├── docker-compose.yml
├── .env
├── README.md
└── db-data/ (Docker volume for Postgres data)