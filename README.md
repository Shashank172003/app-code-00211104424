# 📦 Application Code – `00211104424`

This repository contains a simple **Node.js Express** application, fully Dockerized and deployed to an **AWS EC2 instance** using **GitHub Actions** CI/CD pipeline.

---

## 🎯 Objective

- Develop a Node.js app served on port **5000**
- Dockerize the application
- Push image to **DockerHub**
- Deploy the app to an EC2 instance via **GitHub Actions**
- App should be accessible on port **4424** (last 4 digits of roll number)

---

## 🛠️ Tech Stack

- Node.js (Express)
- Docker
- GitHub Actions
- AWS EC2 (via SSH)
- DockerHub

---

## 📁 Project Structure

app-code-00211104424/
├── app/
│   └── index.js            # Main Express app
├── Dockerfile              # Docker image definition
├── .github/
│   └── workflows/
│       └── ci-cd.yml       # CI/CD GitHub Actions workflow
└── README.md


