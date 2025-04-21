# 🐳 Dockerized Web Stack

This project sets up a multi-container web application using **Docker Compose**. It includes **WordPress** as the frontend CMS and **MySQL** as the backend database.

## 🔧 What It Does

- Sets up a fully functional WordPress website
- Runs MySQL as the backend database
- Uses Docker volumes for data persistence
- Connects containers over a Docker network

## 🧰 Stack

- WordPress
- MySQL
- Docker
- Docker Compose

## 📂 Project Structure

```
dockerized-web-stack/
├── docker-compose.yml
└── README.md
```

## 🚀 Usage

### 1. Start the stack

```bash
docker-compose up -d
```

### 2. Access WordPress

Open your browser and go to: [http://localhost:8000](http://localhost:8000)

### 3. Shutdown

```bash
docker-compose down
```

---

> Ideal for learning how to connect services in containers using Docker Compose.
