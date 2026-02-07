#  AWS EC2 Website Hosting with NGINX, Application Load Balancer & Auto Scaling

## 📌 Project Overview
This project demonstrates a **production-ready cloud architecture** for hosting a website on AWS.  
The website is deployed on **EC2 instances** using **NGINX** as the web server, fronted by an **Application Load Balancer (ALB)** for traffic distribution, and backed by an **Auto Scaling Group (ASG)** to ensure high availability, fault tolerance, and scalability based on demand.

This setup reflects **real-world cloud infrastructure practices** used in production environments.

## 🏗️ Architecture Overview
- Users access the application through an **Application Load Balancer**
- ALB distributes traffic across multiple **EC2 instances**
- **NGINX** serves the website content
- **Auto Scaling Group** automatically scales EC2 instances based on load
- Ensures **high availability, reliability, and performance**

📷 *Refer to the architecture diagram in the `architecture/` folder.*

## 🔧 Tech Stack & AWS Services Used
- **Amazon EC2** – Compute
- **NGINX** – Web server
- **Application Load Balancer (ALB)** – Traffic distribution
- **Auto Scaling Group (ASG)** – Automatic scaling & high availability
- **Amazon VPC** – Networking
- **Security Groups** – Access control
- **CloudWatch** – Monitoring & metrics

## ⚙️ Key Features
- Load-balanced web traffic
- Automatic scaling based on demand
- Fault-tolerant architecture
- Improved performance and reliability
- Production-style cloud deployment

## 🛠️ Setup Summary
1. Created a VPC with public subnets and internet access
2. Launched EC2 instances and installed NGINX
3. Configured an Application Load Balancer
4. Created a Target Group with health checks
5. Attached EC2 instances via an Auto Scaling Group
6. Tested load balancing and scaling behavior

## 📈 Auto Scaling & Testing
- CPU-based scaling policies were configured
- Load was generated to trigger scaling events
- New EC2 instances were launched automatically
- Traffic was distributed without downtime

## 🧠 Skills Demonstrated
- AWS Cloud Architecture
- EC2, ALB & Auto Scaling
- Linux server management
- NGINX configuration
- High Availability & Scalability concepts
- Troubleshooting cloud infrastructure
- DevOps fundamentals

## 🎯 Use Case
This architecture is suitable for:
- Hosting scalable websites
- Cloud-native web applications
- Production-ready infrastructure deployments
- Learning and demonstrating AWS & DevOps concepts

---

