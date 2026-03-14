# 🚀 Dockerized Real-Time Chat Frontend

A modern **React + Vite application fully containerized using Docker**.
This project demonstrates how to package a frontend application into a **portable Docker container** for consistent development and deployment.

---

## 📌 Tech Stack

* **React 18**
* **Vite**
* **TypeScript**
* **Tailwind CSS**
* **Docker**
* **Docker Compose**

---

## 📂 Project Structure

```
real1-chat/
│
├── Dockerfile
├── docker-compose.yml
├── package.json
├── vite.config.ts
├── src/
│   ├── components
│   ├── pages
│   └── main.tsx
└── public/
```

---

## ⚙️ Features

* Containerized React application
* Fast development server using **Vite**
* Docker Compose orchestration
* Easy environment setup
* Production-ready container build
* Consistent environment across machines

---

## 🐳 Running with Docker

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/docker-realtime-chat.git
cd docker-realtime-chat
```

---

### 2️⃣ Build and start the container

```
docker compose up --build
```

Docker will:

1. Pull the Node.js image
2. Install project dependencies
3. Build the React application
4. Start the development server inside the container

---

### 3️⃣ Open the application

```
http://localhost:5173
```

---

## 🧱 Docker Architecture

```
Browser
   ↓
localhost:5173
   ↓
Docker Container
   ↓
Vite Dev Server
   ↓
React Application
```

---

## 📦 Docker Commands

Build container

```
docker compose build
```

Run container

```
docker compose up
```

Stop container

```
docker compose down
```

---

## 🎯 Purpose of this Project

This project demonstrates:

* Dockerizing frontend applications
* Container-based development workflow
* Simplifying environment setup for teams
* Preparing applications for **DevOps pipelines and cloud deployment**

---

## 🔮 Future Improvements

* Nginx production build
* CI/CD with GitHub Actions
* Docker Hub image publishing
* Kubernetes deployment
* Monitoring with Prometheus & Grafana

---

## 👨‍💻 Author

**Saurav Kumar**

B.Tech Computer Science | Full Stack Developer | DevOps Enthusiast

---

⭐ If you like this project, consider giving it a **star on GitHub**.
