# ☁️ osTicket — Phase 2: AWS Production Deployment

This phase transforms the osTicket project from a local server into a **cloud-hosted, production-ready environment** using AWS infrastructure and automation tools.

---

## 🧱 Overview
The goal of Phase 2 is to migrate osTicket to the AWS cloud and enhance scalability, reliability, and security using real-world cloud practices.  
It demonstrates how to deploy and manage an enterprise-grade ticketing platform with automated provisioning and monitoring.

---

## 🧩 Technologies Used
- **AWS Services:** EC2, RDS (MySQL), S3, Route 53, ACM, CloudWatch  
- **Compute Stack:** Windows Server 2025, IIS, PHP, osTicket  
- **Automation Tools:** Terraform, PowerShell  
- **Database:** Amazon RDS (MySQL 8.0)  

---

## ⚙️ Implementation Summary
1. **Infrastructure Setup (AWS):**
   - Created VPC, subnets, Internet Gateway, and routing.
   - Provisioned EC2 instance (Windows Server 2025 Base AMI).
   - Created RDS (MySQL) in a private subnet.
   - Configured S3 bucket for osTicket file storage.

2. **DNS & Security:**
   - Registered custom domain in Route 53.
   - Used AWS Certificate Manager (ACM) for SSL certificate.
   - Applied least-privilege IAM roles for EC2 and RDS access.

3. **Application Deployment:**
   - Installed IIS, PHP, and osTicket on EC2.
   - Updated osTicket configuration to connect to RDS.
   - Secured web access using HTTPS via ACM.

4. **Automation & Monitoring:**
   - Built Terraform scripts for infrastructure provisioning.
   - Automated server setup using PowerShell.
   - Enabled CloudWatch dashboards and alarms.

---

## 📂 Folder Contents
Phase2/
├── automation/
│ ├── terraform/ → Infrastructure as Code files
│ └── powershell/ → Server setup & configuration scripts
├── docs/ → Architecture diagram & AWS setup notes
└── screenshots/ → Cloud deployment screenshots


---

## 🧠 Learning Outcomes
- Migrated a local system to a cloud-native architecture.  
- Learned AWS networking (VPC, subnets, security groups).  
- Implemented Infrastructure as Code using Terraform.  
- Automated server provisioning via PowerShell.  
- Gained experience with SSL, DNS, and cloud monitoring.  

---

## 📸 Screenshots
All screenshots for this phase are stored in the [screenshots folder](./screenshots).  
Recommended captures include:
- AWS VPC Dashboard  
- RDS Instance Details  
- S3 Bucket Configuration  
- IIS SSL Binding  
- Terraform Apply Output  
- osTicket Admin Portal on AWS  

---

## 🚀 Future Enhancements
- CI/CD pipeline using GitHub Actions.  
- Dockerized osTicket stack.  
- RDS snapshot automation via Lambda.  
- Multi-region Route 53 failover configuration.  

---

## 🧑‍💻 Author
**[Your Name](https://www.linkedin.com/in/your-link/)**  
Cloud & Systems Administrator | DevOps Enthusiast  
📧 youremail@example.com  

---
⭐ *If this project inspires you, consider starring the repository!*

