# aws-webapp-alb-https
🚀 AWS 2-Tier Web Application Deployment

📌 Overview

Deployed a secure and scalable web application on AWS using Route 53, Application Load Balancer, HTTPS, and EC2.

---

🌐 Live Demo

👉 https://sdancloud.com

---

🏗️ Architecture

User → Route 53 → ALB (HTTPS) → Target Group → EC2

---

🔧 Services Used

- Route 53 (DNS)
- AWS Certificate Manager (SSL)
- Application Load Balancer
- EC2 (Web Server)
- Auto Scaling (optional)

---

🔐 Features

- HTTPS enabled using SSL certificate
- HTTP to HTTPS redirection
- Load balancing across multiple instances
- Custom domain integration

---

⚙️ Steps Performed

1. Configured domain using Route 53
2. Requested SSL certificate via ACM
3. Created Application Load Balancer
4. Configured target group with EC2 instances
5. Added HTTP (80) and HTTPS (443) listeners
6. Implemented redirect rule from HTTP to HTTPS
7. Created A record (Alias) pointing domain to ALB

---

🧠 Learning

- DNS and Route 53 integration
- SSL and HTTPS configuration
- Load balancing concepts
- Real-world AWS architecture

---

🎯 Outcome

Successfully deployed a production-like web application with secure HTTPS access and scalable architecture.
