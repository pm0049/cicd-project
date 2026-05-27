# Automated End-to-End CI/CD Pipeline on AWS

## Project Overview

This project demonstrates an automated End-to-End CI/CD (Continuous Integration and Continuous Deployment) pipeline built using AWS, Jenkins, Docker, GitHub, and Node.js.

The goal of this project is to automate the software development lifecycle including:
- Source code integration
- Automated build process
- Docker containerization
- Automated deployment on AWS EC2

This project simulates a real-world DevOps workflow used in modern software industries.

---

# Architecture

Developer → GitHub Repository → Jenkins CI/CD Pipeline → Docker Build → AWS EC2 Deployment

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| AWS EC2 | Cloud server hosting |
| Jenkins | CI/CD automation tool |
| Docker | Containerization |
| GitHub | Source code management |
| Node.js | Backend application |
| Git | Version control |
| Amazon Linux 2023 | Operating System |

---

# Features

- Automated CI/CD pipeline setup
- Dockerized Node.js application
- GitHub integration with Jenkins
- Automatic build and deployment process
- Cloud deployment on AWS EC2
- Continuous Integration workflow
- Continuous Deployment workflow

---

# Project Workflow

1. Developer pushes code to GitHub repository.
2. Jenkins pulls the latest source code from GitHub.
3. Jenkins builds the Docker image automatically.
4. Existing Docker container stops automatically.
5. New Docker container gets deployed automatically.
6. Updated application becomes live on AWS EC2.

---

# Folder Structure

```bash
cicd-project/
│
├── app.js
├── package.json
├── Dockerfile
├── Jenkinsfile
└── README.md
