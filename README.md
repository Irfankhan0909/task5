# 🚀 Task - Kubernetes Setup on AWS EC2

## 📌 Overview
This task demonstrates how to set up **Docker**, **kubectl**, and **Minikube** on an AWS EC2 instance.

---

## 🛠 Tools & Technologies Used
- AWS EC2 (Ubuntu)
- Docker
- Kubernetes CLI (kubectl)
- Minikube

---

## ⚙️ Steps Performed
1. **Launched an AWS EC2 Instance**
   - Ubuntu 22.04 LTS  
   - Configured inbound security group to allow **SSH (22)** and **HTTP/HTTPS (80, 443)**, and **custom ports** if needed.

2. **Installed Docker**
   ```bash
   sudo apt update
   sudo apt install -y docker.io
   sudo systemctl enable docker
   sudo systemctl start docker
   docker --version
