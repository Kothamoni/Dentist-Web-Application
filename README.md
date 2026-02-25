# 🦷 Dental Patient Web Application

**Smart • Secure • Efficient Dental Management System**  
Built with ❤️ for Modern Dental Clinics  

---

## 📑 Table of Contents

- 🚀 Tech Stack  
- 📋 Project Management  
- 🏗️ Project Status  
- 🌐 Live Demo  
- 👥 Team Members  
- 📜 Project Description  
- 🛠️ Getting Started  
- 🗺️ System Architecture  
- 📊 Database Models  
- 🔮 Future Improvements  
- 📄 License  

---

## 🚀 Tech Stack

### 💻 Frontend
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### ⚙️ Backend
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)

### 🗄️ Database
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=for-the-badge&logo=mongoose&logoColor=white)

### 🔐 Authentication & Security
![JWT](https://img.shields.io/badge/JWT-Authentication-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![bcrypt](https://img.shields.io/badge/bcrypt-Password%20Hashing-blue?style=for-the-badge)

### 🛠️ Tools & Deployment
![Git](https://img.shields.io/badge/Git-Version%20Control-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-API%20Testing-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![MongoDB Compass](https://img.shields.io/badge/MongoDB%20Compass-Database%20GUI-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-Frontend%20Deploy-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 📋 Project Management

**Version Control:** Git & GitHub  

**Repository:** [DentalPatient_Web_Application](https://github.com/Kothamoni/DentalPatient_Web_Application)

**Folder Structure**


📁 DentalPatient_Web_Application
├─ 📂 frontend/ # Landing page & Doc Login front-end
├─ 📂 backend/ # API & server logic
├─ 📂 database/ # DB dump / seed
├─ 📄 README.md # Project documentation
├─ 📄 .env.example # Environment variables
├─ 📄 LICENSE


---

## 🏗️ Project Status

🟢 Core Features Implemented  
🟡 UI Improvements Ongoing  
🔵 Future Features Planned  

---

## 🌐 Live Demo

(https://dentist-web-application.vercel.app/) 

Frontend: `https://dentist-web-application.vercel.app/`  
Backend API: `http://localhost:3000`

---

## 👥 Team Members

| Name | Role |
|------|------|
| Umme Nafisa Anzum Kotha | Project Lead / Full-Stack Developer |

---

## 📜 Project Description

**Dental Patient Web Application** is a full-stack web system designed to digitize dental chamber operations with:

- Secure doctor authentication  
- Patient management  
- Treatment tracking
- Precription Generator & printable PDF 

The system connects with the landing page’s **Doc-Login**, providing a secure dashboard for doctors.

---

## 🗺️ System Architecture


Client (Browser)
↓
REST API (Express.js)
↓
MongoDB Database


| Layer    | Responsibility |
|----------|----------------|
| Frontend | UI rendering & user interaction |
| Backend  | Business logic, authentication & appointment handling |
| Database | Persistent data storage |

---

## 📊 Database Models

### Collections

- Users (Doctor/Admin)  
- Patients  
- Appointments  
- Treatments  
- Prescriptions 

### Relationships

- One Doctor → Multiple Patients  
  - One Appointment → One Treatment Record  

---

## 🔮 Future Improvements

- Role-based access control (Doctor/Admin)  
- Online appointment booking for patients  
  - Dashboard analytics  
- Progressive Web App (PWA) version  

---

## 🛠️ Getting Started

### Requirements

| Requirement | Version |
|-------------|---------|
| Node.js     | v18+    |
| MongoDB     | v6+     |
| npm         | Latest  |

### Installation

```bash
git clone https://github.com/Kothamoni/DentalPatient_Web_Application.git
cd DentalPatient_Web_Application
npm install
npm run dev

Backend runs at: http://localhost:3000

📄 License

MIT License

🦷 Dental Patient Web Application

Secure • Reliable • Modern Clinic Management

Developed by Umme Nafisa Anzum Kotha
Bangladesh University of Professionals
Department of ICT
