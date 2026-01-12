# DevOps Todo App

A simple **Todo Web Application** with a complete **DevOps pipeline**.  
This project demonstrates **CI/CD**, **Docker containerization**, **infrastructure as code**, and **monitoring**, all in one open-source project.

---

## 🚀 Features

- Full-stack Todo app:
  - Backend: Node.js + Express + MongoDB
  - Frontend: React
- Containerized using Docker
- CI/CD pipeline with GitHub Actions
- Infrastructure as code using Docker Compose (optionally Terraform)
- Monitoring using Prometheus + Grafana
- Automated testing for backend and frontend

---

## 🛠 Tech Stack

| Layer        | Technology                          |
|-------------|------------------------------------|
| Backend      | Node.js, Express, MongoDB           |
| Frontend     | React                               |
| Container    | Docker, Docker Compose              |
| CI/CD        | GitHub Actions                      |
| Infrastructure | Docker Compose, (optional: Terraform) |
| Monitoring   | Prometheus, Grafana, Loki           |
| Testing      | Jest, React Testing Library         |

---

## 📦 Project Structure
```
.
├── app.js
├── backend
│   └── frontend
│       └── Docjerfile
├── ci-cd
│   └── github-actions.yaml
├── Dockerfile
├── infra
│   └── docker-compose.yaml
└── package.json

4 directories, 6 files
```

---

## ⚡ Prerequisites

- [Docker](https://www.docker.com/get-started)  
- [Docker Compose](https://docs.docker.com/compose/install/)  
- Node.js (optional for local dev)

---

## 🏗 Setup & Run Locally

1. Clone the repository:

```bash
git clone https://github.com/ByteEngr/To_do.git
cd To_do/infra

