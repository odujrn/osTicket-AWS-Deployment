<p align="center">
  <img src="./banner.png" alt="osTicket AWS Banner" width="100%" />
</p>

<h1 align="center">osTicket Helpdesk Deployment on AWS</h1>
<h3 align="center">Windows Server 2025 • IIS • PHP • MySQL • AWS Cloud</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Phase-1%20%7C%20Phase%202-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws" />
  <img src="https://img.shields.io/badge/osTicket-Helpdesk-success?style=for-the-badge" />
</p>

---

## 📖 Project Overview
This repository documents my full **osTicket Helpdesk Deployment journey** — from a local Windows IIS setup to a production-grade AWS deployment.  
It demonstrates my experience with:
- Windows Server administration  
- IIS, PHP, and MySQL setup  
- AWS cloud infrastructure (EC2, RDS, S3, Route 53, ACM, CloudWatch)  
- Automation using Terraform and PowerShell  
- Security hardening and performance optimization  

---

## ⚙️ Phase 1 — Local IIS Deployment
📁 [Phase1](./Phase1)

### 🧩 Technologies Used
- Windows 10 / Windows Server  
- IIS, PHP, MySQL, HeidiSQL  
- osTicket v1.15.8  

### 🧠 Highlights
- Configured IIS web server to host osTicket locally  
- Installed and configured PHP extensions and MySQL database  
- Enabled necessary IIS modules and permissions  
- Verified access for both end-users and agents  

📸 *Screenshots available in* [`/Phase1/screenshots`](./Phase1/screenshots)

---

## ☁️ Phase 2 — AWS Production Deployment
📁 [Phase2](./Phase2)

### 🧩 Technologies Used
- AWS EC2, RDS, S3, Route 53, ACM, CloudWatch  
- IIS, PHP, osTicket  
- Terraform & PowerShell automation  

### 🧠 Highlights
- Deployed osTicket on Windows Server 2025 (EC2)  
- Configured RDS (MySQL) in a private subnet  
- Integrated S3 for file/attachment storage  
- Used Route 53 and ACM for domain + SSL management  
- Added CloudWatch for monitoring and alerting  
- Automated setup with Terraform (infra) & PowerShell (server config)  

📸 *Screenshots available in* [`/Phase2/screenshots`](./Phase2/screenshots)

---

## 🧰 Repository Structure

osTicket-AWS-Deployment/
├── Phase1/ → Local deployment setup
├── Phase2/ → AWS production configuration
└── banner.png → Project banner for README


---

## 🔐 Security and Best Practices
- HTTPS enforced with valid SSL certificate  
- IAM least-privilege access policies  
- RDS private subnet access only via EC2  
- Regular EC2 & RDS snapshots for recovery  
- Removed public write permissions post-deployment  

---

## 📈 Future Enhancements
- Dockerized osTicket stack (Nginx + PHP-FPM + MySQL)  
- GitHub Actions CI/CD integration  
- Automated RDS backups via Lambda  
- Multi-region redundancy (Route 53 failover routing)  

---

## 💡 Learning Outcomes
- Understanding of Windows Server web hosting  
- Exposure to hybrid IT & cloud migration  
- Hands-on experience with AWS infrastructure design  
- Real-world implementation of Infrastructure-as-Code principles  

---

## 🧑‍💻 Author
**[Oduamadi Ndubuisi](https://www.linkedin.com/in/your-link/)**  
Cloud & Systems Administrator | DevOps Enthusiast  
📧 ndu_euro@outlook.com  

---

⭐ *If you found this project helpful, please consider starring the repository!*
