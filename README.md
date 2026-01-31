# Mini CRM System

A full-stack **Mini CRM (Customer Relationship Management)** system built to manage business leads, track their status, and understand basic analytics.  
This project was created to simulate how real-world businesses handle incoming clients and follow-ups.

---

## 🚀 Features

- Admin login system  
- Lead management (Add, View, Update)
- Lead status tracking: **New → Contacted → Converted**
- Follow-up notes for each lead
- Simple analytics dashboard (total leads, conversions)
- Clean and responsive UI
- REST API–based backend architecture

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- MySQL

### Tools
- Git & GitHub
- VS Code
- Postman

---

## 📂 Project Structure
mini-crm/ │ ├── backend/ │   ├── server.js │   ├── db.js │   ├── routes/ │   └── package.json │ ├── frontend/ │   ├── index.html │   ├── dashboard.html │   ├── style.css │   └── app.js │ └── README.md

## 🚀 How to Run Locally

### Prerequisites
- Node.js
- MySQL
- Git

### Steps
1. Clone the repository
   ```bash
   git clone https://github.com/priyanshu-bhardwaj12/mini-crm.git

### Backend setup
cd backend
npm install
node server.js

backend will run on: http://localhost:5000

### frontend setup
open frontend/index.html in your browser

demo credential(local)
username : admin
password : admin123

<img width="1845" height="747" alt="Screenshot 2026-01-30 195602" src="https://github.com/user-attachments/assets/b3c16655-a38a-409f-8d39-32288d82ea7f" />
<img width="1813" height="894" alt="Screenshot 2026-01-30 195533" src="https://github.com/user-attachments/assets/0953e209-36e4-4556-a078-e42f43652936" />
<img width="1436" height="844" alt="Screenshot 2026-01-30 195503" src="https://github.com/user-attachments/assets/588cb7a5-6be3-424d-ab7d-ae40aba4cbf6" />

**🧠 What I Learned**
Building REST APIs using Express
Connecting frontend with backend using fetch API
MySQL database integration
Handling real-world errors and debugging
GitHub version control and project structuring
Difference between local development and deployment environments

**🚧 Notes**
This project is designed to run locally.
Backend deployment was experimented with but not exposed publicly for security reasons.
Database setup is required to fully use the application.

**🗄 Database Info**
MySQL is used as the database
Database is configured for local development
Database credentials are stored in backend configuration files
ℹ️ Cloud database hosting can be integrated in the future.

**🚧 Deployment Status**
Project is currently intended for local development
Frontend and backend can be deployed separately if required
No cloud database is configured at this stage
Project is currently intended for local development
Frontend and backend can be deployed separately if required
No cloud database is configured at this stage

**👤 Author**
Priyanshu Bhardwaj
GitHub: https://github.com/priyanshu-bhardwaj12

**📌 Future Improvements**
JWT-based authentication
Role-based access
Advanced analytics & charts
Cloud database integration
Production-ready deployment

**⭐ Feedback**
If you find this project useful, feel free to star ⭐ the repository.
