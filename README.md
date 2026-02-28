# 🚀 TaskFlow – Dockerized CI/CD Application

TaskFlow is a simple Node.js REST API containerized using Docker and integrated with a CI/CD pipeline using GitHub Actions.

## 🛠 Tech Stack
- Node.js
- Express
- Docker
- GitHub Actions (CI/CD)

## 🐳 Docker Setup

Build image:
docker build -t taskflow .

Run container:
docker run -p 5002:5000 taskflow

Visit:
http://localhost:5002

## 🔁 CI/CD Pipeline

On every push to main branch:
- Docker image builds automatically
- Image pushed to DockerHub

## 📌 Author
Swati Parihar