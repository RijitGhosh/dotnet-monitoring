# 🚀 DevSecOps CI/CD Pipeline for .NET Monitoring App

## 📌 Overview

This project demonstrates a complete **DevSecOps pipeline** using a .NET web application.
It integrates **CI/CD, containerization, orchestration, and security scanning**.

---

## 🛠️ Technologies Used

* 🐳 Docker – Containerization
* ☸️ Kubernetes – Container orchestration
* 🔧 Jenkins – CI/CD pipeline automation
* 🔐 Trivy – Vulnerability scanning
* 🛡️ OWASP Dependency Check – Security analysis
* 💻 .NET – Web application

---

## ⚙️ Features

* 📊 Real-time CPU & Memory Monitoring
* 🚀 Docker-based deployment
* 🔄 CI/CD pipeline integration using Jenkins
* 🔐 Security vulnerability scanning (DevSecOps)
* ☸️ Kubernetes deployment support

---

## ▶️ Run the Project

### Start Application

docker run -d -p 5000:5000 ghcr.io/benc-uk/dotnet-demoapp:latest

### Open in Browser

http://localhost:5000

### Monitoring Dashboard

http://localhost:5000/Monitoring

---

## 🔐 Security Scan

trivy image ghcr.io/benc-uk/dotnet-demoapp:latest

---

## ☸️ Kubernetes Deployment

kubectl apply -f deployment.yaml

---

## 🔄 CI/CD Pipeline

The Jenkins pipeline automates:

* Code checkout from GitHub
* Build and testing
* Security scanning (Trivy, OWASP, SonarQube)
* Docker image build and push
* Deployment

---

## 👨‍💻 Author

**Rijit Ghosh**
https://github.com/RijitGhosh

---

## ⭐ Conclusion

This project demonstrates a real-world **DevSecOps lifecycle**, combining development, security, and operations into a single automated workflow.
