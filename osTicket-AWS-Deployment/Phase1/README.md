# 🧰 osTicket — Phase 1: Local IIS Deployment

This phase documents the **local installation and configuration of osTicket** using Windows, IIS, PHP, and MySQL.

---

## 🧱 Overview
The goal of Phase 1 is to understand how osTicket functions on a single Windows machine before moving to the AWS cloud in Phase 2.  
This phase focuses on web hosting, PHP configuration, and database management using MySQL and HeidiSQL.

---

## 🧩 Technologies Used
- Windows Server (21H2)
- Internet Information Services (IIS)
- PHP (v7.x or higher)
- MySQL Server
- HeidiSQL
- osTicket v1.15.8

---

## ⚙️ Installation Summary
1. **Prepared Windows OS** by enabling IIS and necessary features.  
2. **Installed Prerequisites:**
   - PHP Manager
   - VC Redist
   - URL Rewrite Module
   - PHP (unzipped to `C:\PHP`)
   - MySQL and HeidiSQL
3. **Deployed osTicket:**
   - Extracted files to `C:\inetpub\wwwroot\osTicket`
   - Configured IIS to serve the osTicket site.
4. **Configured Permissions & PHP Extensions:**
   - Enabled `php_imap.dll`, `php_intl.dll`, `php_opcache.dll`
   - Renamed and assigned permissions to `ost-config.php`
5. **Completed Web Installation:**
   - Set up MySQL database and admin email
   - Confirmed osTicket running on `http://localhost/osTicket`

---

## 🧠 Learning Outcomes
- Learned how to configure and host a web application on IIS.  
- Understood PHP–MySQL integration and permissions management.  
- Gained experience troubleshooting IIS and PHP configuration errors.  

---

## 📸 Screenshots
You can find all screenshots for this phase in the [screenshots folder](./screenshots).  
Recommended captures include:
- IIS Feature Installation  
- PHP Directory Setup  
- MySQL Configuration Wizard  
- osTicket Web Installation Page  
- Agent and End-User Login Screens  

---

## 🔗 Next Phase
Proceed to [Phase 2](../Phase2) — where osTicket is migrated and automated using **AWS Cloud infrastructure**.
