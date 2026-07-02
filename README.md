# 🚚 Courier Tracking System (CTS)

<p align="center">

<img src="https://img.shields.io/badge/Java-17-orange?logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/JSP-JavaServer%20Pages-blue" />
<img src="https://img.shields.io/badge/Servlet-Java-success" />
<img src="https://img.shields.io/badge/Bootstrap-5-7952B3?logo=bootstrap&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-Database-4479A1?logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/Apache-Tomcat-F8DC75?logo=apachetomcat&logoColor=black" />
<img src="https://img.shields.io/badge/Status-Completed-brightgreen" />
<img src="https://img.shields.io/github/stars/Tharunnayak-45/Courier-Tracking-System-App?style=social" />

</p>

<h3 align="center">
A Modern Web-Based Courier Tracking System built using Java, JSP, Servlets, MySQL & Apache Tomcat.
</h3>

---

# 🌐 Live Demo

### 🎥 Project Demo

> ▶️ **Click below to watch the project demonstration**

https://github.com/user-attachments/assets/9db8a6f4-582b-41e7-ab63-4cb5861fa05b

---

# 📑 Table of Contents

- Overview
- Features
- System Workflow
- Technology Stack
- Project Architecture
- Installation
- Database Setup
- Screenshots
- Advantages
- Future Enhancements
- Conclusion
- Author

---

# 📌 Overview

The **Courier Tracking System (CTS)** is a dynamic web application developed using **Java, JSP, Java Servlets, MySQL, Bootstrap, and Apache Tomcat**.

The system allows customers to track courier shipments using a unique tracking number while providing administrators with a secure dashboard to manage courier records, update shipment status, and monitor delivery progress.

This project demonstrates the implementation of Java Enterprise technologies using the **MVC (Model-View-Controller)** architecture.

---

# 🎯 Objectives

- Automate courier management
- Track courier status in real time
- Reduce manual paperwork
- Improve customer satisfaction
- Maintain secure courier records
- Enhance administrative efficiency

---

# ✨ Features

## 👤 User Module

- User Registration
- Secure Login & Logout
- Track Courier using Tracking ID
- View Delivery Status
- Update Profile
- Search Shipment

---

## 🛠️ Admin Module

- Secure Admin Login
- Add New Courier
- Update Courier Details
- Update Delivery Status
- Manage Users
- Delete Courier Records
- View Courier Reports

---

## 🚚 Tracking Module

- Automatic Tracking ID Generation
- Real-Time Shipment Updates
- Delivery Confirmation
- Tracking History

---

# 🔄 System Workflow

```text
                User Registration
                       │
                       ▼
                  User Login
                       │
                       ▼
         Admin Creates Courier Record
                       │
                       ▼
        Unique Tracking ID Generated
                       │
                       ▼
      Customer Enters Tracking Number
                       │
                       ▼
        Shipment Status is Displayed
                       │
                       ▼
     Admin Updates Transit Information
                       │
                       ▼
         Courier Successfully Delivered
```

---

# 🏗 Project Architecture

```
                   Client (Browser)
                          │
                          ▼
                 JSP Pages (View)
                          │
                          ▼
               Java Servlets (Controller)
                          │
                          ▼
                 DAO / Business Logic
                          │
                          ▼
                    MySQL Database
```

---

# 🛠 Technology Stack

| Category | Technologies |
|----------|--------------|
| Language | Java |
| Frontend | HTML5, CSS3, Bootstrap 5, JavaScript |
| Backend | JSP, Java Servlets |
| Database | MySQL |
| Server | Apache Tomcat |
| IDE | Eclipse / IntelliJ IDEA |
| Version Control | Git & GitHub |

---

# 📂 Project Structure

```text
Courier-Tracking-System/
│
├── src/
│   ├── controller/
│   ├── dao/
│   ├── model/
│   ├── servlet/
│   ├── util/
│   └── database/
│
├── WebContent/
│   ├── css/
│   ├── js/
│   ├── images/
│   ├── WEB-INF/
│   ├── index.jsp
│   ├── login.jsp
│   ├── register.jsp
│   ├── dashboard.jsp
│   └── tracking.jsp
│
├── database/
│   └── courier_tracking.sql
│
└── README.md
```

---

# ⚙ Installation Guide

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Tharunnayak-45/Courier-Tracking-System-App.git
```

---

## 2️⃣ Import into Eclipse

- Open Eclipse IDE
- File → Import
- Existing Projects into Workspace
- Select the cloned repository

---

## 3️⃣ Configure Database

Create Database

```sql
CREATE DATABASE courier_tracking;
```

Import the provided SQL file into MySQL.

---

## 4️⃣ Configure Apache Tomcat

- Install Apache Tomcat 9
- Add Server in Eclipse
- Deploy the project

---

## 5️⃣ Run the Project

```
http://localhost:8081/CTS/
```

---

# 📸 Project Screenshots

## 🔐 Login Page

<img src="https://github.com/user-attachments/assets/de7f9ef8-b003-4205-9f42-f1f7767a5c82"/>

---

## 🏠 Home Page

<img src="https://github.com/user-attachments/assets/d764c84a-57b6-46ec-adb6-180fa2119ce8"/>

---

## 🔍 Courier Tracking

<img src="https://github.com/user-attachments/assets/2fd59fcc-d216-44a7-9c53-b7c3d63981d1"/>

---

## 🛠 Admin Dashboard

<img src="https://github.com/user-attachments/assets/2a87d7b6-022b-4de3-89e4-d32dc8eea277"/>

---

# 📊 Project Highlights

| Feature | Status |
|----------|:------:|
| User Authentication | ✅ |
| Courier Tracking | ✅ |
| Admin Dashboard | ✅ |
| CRUD Operations | ✅ |
| MySQL Integration | ✅ |
| Responsive Design | ✅ |
| Secure Login | ✅ |
| Session Management | ✅ |

---

# 🚀 Advantages

- Clean and Responsive UI
- Fast Courier Tracking
- Secure Authentication
- Efficient Database Management
- Easy to Use
- Reduces Manual Work
- Organized Admin Dashboard
- Real-Time Status Updates

---

# 🔮 Future Enhancements

- 📧 Email Notifications
- 📱 SMS Alerts
- 🌍 GPS Live Tracking
- 📲 Android Application
- 💳 Online Payment Integration
- 📦 QR Code Tracking
- 🔔 Push Notifications
- 📈 Analytics Dashboard
- ☁ Cloud Deployment

---

# 🎓 Learning Outcomes

Through this project, I gained hands-on experience in:

- Java Programming
- JSP Development
- Java Servlets
- MVC Architecture
- JDBC
- MySQL Database
- Session Management
- CRUD Operations
- Bootstrap UI Design
- Apache Tomcat Deployment
- Git & GitHub

---

# 🎯 Conclusion

The **Courier Tracking System (CTS)** provides an efficient and reliable solution for managing courier operations and tracking shipments in real time.

Developed using **Java, JSP, Servlets, MySQL, Bootstrap, and Apache Tomcat**, the application follows the MVC architecture and demonstrates essential concepts of Java Enterprise web development while offering a practical solution for courier service management.

---

# 👨‍💻 Author

## Mudavath Tharun

**B.Tech – Computer Science & Engineering**

### Connect with Me

- GitHub: https://github.com/Tharunnayak-45
- LinkedIn: *(www.linkedin.com/in/mudavaththarunnayak)*

---

# ⭐ Show Your Support

If you found this project helpful:

⭐ Star this Repository

🍴 Fork this Repository

🐛 Report Issues

💡 Suggest Improvements

---
