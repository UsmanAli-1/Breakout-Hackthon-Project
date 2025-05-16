# 🚌 Smart Shuttle Service – Breakout Hackathon Project

A smart transport management system designed to streamline van transport for students at Iqra University. This full-stack web app lets students view real-time shuttle routes, track schedules, and book their rides easily. Admins can manage vans, assign routes, and handle drivers from a centralized dashboard. The platform ensures improved coordination, reduced wait times, and a smoother commute experience for students.

🔗 **Live Demo**: [https://smartshuttleservice.firebaseapp.com](https://smartshuttleservice.firebaseapp.com)  
📽️ **Demo Video**: [Watch the Smart Shuttle Demo](https://youtu.be/vDl8HU36Czc)

[![Watch the Demo](https://img.youtube.com/vi/vDl8HU36Czc/0.jpg)](https://youtu.be/vDl8HU36Czc)


## 🖼️ Screenshots

Here are some key views of the Smart Shuttle Service application:

| Front Pages |
|--------------|------------|
| ![Front](./assets/front-page.png) | 

| Login Pages |
|--------------|------------|
| ![Driver Login](./assets/driver-loginform.png) | ![Student Login](../assets/student-loginform.png) |
| ![Admin Login](./assets/admin-loginform.png) |

| Register Pages |
|--------------|------------|
| ![Driver Registere](./assets/driver-register-in-admin.png) | ![Student Register](../assets/student-loginform.png) |
| ![Van Register](./assets/van-register-in-admin.png) |

| Student Dashboard | Admin Dashboard | Driver Dashboard
|-------------------|-------------|
| ![Student](./assets/student-dashboard.png) | ![Admin](./assets/admin-dashboard.png) | 
| ![Driver](./assets/Driver-dashboard.png) |

| Other Features 
|-------------------|-------------|
| ![Student](./assets/student-searchvan.png) | ![Admin](./assets/driver-route-assign.png) | 
| ![Driver](./assets/assigned-route-in-admin.png) |


<!-- Add more rows as needed -->

---

## 📜 Table of Contents

- [Features](#-features)
- [Demo Credentials](#-demo-credentials)
- [Technologies Used](#-technologies-used)
- [How to Run the Project](#-how-to-run-the-project)
- [Acknowledgement](#-acknowledgement)
- [Future Improvements](#-future-improvements)

---

## ✅ Features

- 🚍 View available van routes and real-time stops
- 🕒 Live van schedule tracking
- 👤 Separate dashboards for Admin, Driver, and Student
- 🔐 Secure login system with hashed passwords
- 🛠 Admin control panel to register vans and assign routes
- 📍 Driver dashboard with route access
- 🔍 Student dashboard with route search

---

## 🔐 Demo Credentials

| Role     | Username               | Password  |
|----------|------------------------|-----------|
| Admin    | `Admin`                | `AI2025P` |
| Driver   | `12345-6789101-1`      | `rohan`   |
| Student  | `99999`                | `99999`   |

---

## 🛠 Technologies Used

- **Frontend**: React.js
- **Backend**: Python (Flask), Node.js
- **Database**: MariaDB (hosted on AWS RDS)
- **Hosting**: Firebase Hosting
- **APIs**: GoMapsPro (for mapping/location)
- **Security**: bcrypt (password hashing)
- **Libraries**: `pymysql`, `requests`, `json`, etc.

---

## 💻 How to Run the Project Locally

### 📦 Requirements:
- Node.js
- Python 3
- Visual Studio Code

### 🔧 Setup Steps:

```bash
# Step 1: Clone the repo
git clone https://github.com/UsmanAli-1/Breakout-Hackthon-Project.git

# Step 2: Start the Flask Backend
cd server
python app.py

# Step 3: Start the React Frontend
cd ../front
npm install
npm start
