# 🚀 DevSecOps CI/CD Pipeline for .NET Monitoring App

## 📌 Overview

This project demonstrates a **DevSecOps pipeline** using a .NET web application with Docker, Kubernetes, Jenkins, and security tools.

---

## 🛠️ Technologies Used

* Docker
* Kubernetes
* Jenkins
* Trivy
* OWASP Dependency Check
* .NET

---

## ⚙️ Features

* Real-time CPU & Memory Monitoring
* Docker-based deployment
* CI/CD pipeline integration
* Security vulnerability scanning
* Kubernetes support

---

## ▶️ Run the Project

### Start Application

```
docker run -d -p 5000:5000 ghcr.io/benc-uk/dotnet-demoapp:latest
```

### Open in Browser

```
http://localhost:5000
```

### Monitoring Page

```
http://localhost:5000/Monitoring
```

---

## 🔐 Security Scan

```
trivy image ghcr.io/benc-uk/dotnet-demoapp:latest
```

---

## 👨‍💻 Author

Rijit Ghosh
https://github.com/RijitGhosh

---

## ⭐ Conclusion

This project shows a complete DevSecOps workflow including CI/CD, containerization, orchestration, and security integration.
