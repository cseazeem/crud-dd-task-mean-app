# DevOps Internship Assignment - MEAN Stack App

## ✅ Summary

This project demonstrates cloud-based deployment and CI/CD automation for a simple MEAN stack application. Here's what has been completed:

### 1. 🛠 Cloud VM Setup
- Provisioned an Ubuntu EC2 instance on AWS
- Installed Docker, Node.js, npm, and other required tools

### 2. 📦 App & Dependencies
- Cloned the MEAN stack CRUD app (`crud-dd-task-mean-app`)
- Installed Node.js dependencies using `npm install`

### 3. 🐳 Containerization
- Dockerized the frontend and backend
- Created Dockerfiles and optionally a `docker-compose.yml` to run both services together

### 4. ⚙️ GitHub Actions CI/CD
- Created a GitHub Actions workflow to:
  - Build the Docker image
  - Push it to Amazon ECR
  - Deploy to ECS automatically on every push to `main` branch

### 5. ☁️ Deployment
- Successfully deployed containerized services to AWS (via ECS or EC2)
- App is accessible via the public IP or load balancer

---

## 🔐 Secrets Used in GitHub Actions

- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`

---

## 📎 Additional Files

- `.github/workflows/deploy.yml` – CI/CD Pipeline
- `.aws/task-def.json` – ECS Task Definition (if using ECS)
- `Dockerfile` – For containerizing the app
- `docker-compose.yml` – For local multi-container setup (optional)



## 📸 Screenshots

![Screenshot 10](screenshots/Screenshot%20(10).png)

![Screenshot 14](screenshots/Screenshot%20(14).png)

![Screenshot 15](screenshots/Screenshot%20(15).png)

![Screenshot 19](screenshots/Screenshot%20(19).png)

![Screenshot 20](screenshots/Screenshot%20(20).png)
