# Flowise Local AI Lab

![Docker](https://img.shields.io/badge/Docker-Containerized-blue)
![Flowise](https://img.shields.io/badge/AI-Flowise-purple)
![WSL2](https://img.shields.io/badge/Environment-WSL2-green)

A local environment to build AI agents using **Flowise + Docker + WSL2**.

This project provides a simple setup for running Flowise locally using Docker Compose, allowing developers to build and test AI agents without relying on cloud infrastructure.

---

## Features

- Run Flowise locally
- Containerized with Docker
- Easy setup using Docker Compose
- No cloud dependency

---

## Requirements

- Docker Desktop
- WSL2 (Windows Subsystem for Linux)

---

## Setup

Clone the repository

```bash
git clone https://github.com/your-username/flowise-local-ai-lab.git
```

Move into the project folder

```bash
cd flowise-local-ai-lab
```

Start Flowise

```bash
docker compose up -d
```

Open Flowise in your browser

```
http://localhost:3000
```

---

## Screenshots

### Flowise Dashboard

![Flowise Dashboard](screenshots/flowise-dashboard.png)

### Flowise Agent Builder

![Flowise Agent Builder](screenshots/flowise-agent-builder.png)

### Flowise Container Running

![Flowise Container Running](screenshots/flowise-container-running.png)

### Docker Container View

![Docker Container](screenshots/docker-container-view.png)

### Docker Logs

![Docker Logs](screenshots/docker-logs.png)

---

## Stop the service

```bash
docker compose down
```
