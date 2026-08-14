#  Independence Day Celebration Website

A modern and responsive **Independence Day Celebration Website** built using HTML, CSS, and JavaScript and deployed using a complete **DevOps CI/CD pipeline**.

The project demonstrates containerization, security scanning, automated image management, and continuous deployment to AWS EC2.

---

## 🚀 Project Overview

This project was created to demonstrate a real-world DevOps workflow where application code is automatically built, scanned, containerized, pushed to Docker Hub, and deployed to an AWS EC2 instance whenever changes are pushed to the `main` branch.

### CI/CD Workflow

Developer
↓
GitHub
↓
GitHub Actions
↓
Docker Build
↓
Trivy Security Scan
↓
Docker Hub
↓
SSH Deployment
↓
AWS EC2
↓
Docker Container
↓
Nginx
↓
Live Website

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure |
| CSS3 | Styling and animations |
| JavaScript | Interactive effects |
| Git | Version control |
| GitHub | Source code management |
| GitHub Actions | CI/CD automation |
| Docker | Application containerization |
| Docker Hub | Docker image registry |
| Trivy | Container vulnerability scanning |
| AWS EC2 | Cloud deployment |
| Ubuntu Linux | Server operating system |
| Nginx | Web server |

---

## ✨ Website Features

- 🇮🇳 Indian Independence Day theme
- 🇮🇳 Indian national flag
- 🔵 Full Ashoka Chakra
- 🎨 Indian tricolor design
- ✨ Animated visual effects
- 📱 Responsive design
- 💻 Mobile and desktop support
- 🎉 Independence Day celebration effects

---

## 🔄 CI/CD Pipeline

The project uses GitHub Actions to automate the complete deployment process.

### 1. Source Code

Developers push code to the `main` branch.

```bash
git add .
git commit -m "Update website"
git push origin main
