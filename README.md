# 🚇 HCMC Metro Web Systems – PAWA & OPWA

[![Java](https://img.shields.io/badge/Backend-Spring%20Boot-green?logo=springboot&logoColor=white)](https://spring.io/projects/spring-boot)
[![JavaScript](https://img.shields.io/badge/Frontend-JavaScript-blue?logo=javascript&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Security](https://img.shields.io/badge/Security-JWT%20%7C%20OAuth2-orange)](https://jwt.io/)
[![API](https://img.shields.io/badge/API-REST-red)](https://restfulapi.net/)

## 📖 Overview
This project delivers two integrated enterprise-grade web applications for the **Ho Chi Minh City Metro System**:  

- **PAWA (Passenger Web Application):**  
  Enables passengers to register, book tickets, manage e-wallets, purchase passes, view metro lines, and receive **real-time service alerts**.  

- **OPWA (Operator Web Application):**  
  Supports operators in managing metro schedules, station data, line suspension alerts, and real-time announcements.  

Both systems are designed to **communicate seamlessly** via REST APIs, improving passenger experience and operational efficiency.

---

## 🚀 Features
### PAWA (Passenger App)
- User registration & authentication (**JWT, OAuth2, Google login**)  
- Ticket booking (One-way, Daily, Three-day, Monthly)  
- Passenger **e-Wallet** with top-up & payment integration  
- Persistent ticket cart for multiple purchases  
- Ticket history & activation simulation  
- Real-time suspension alerts & announcements  
- Metro line search & schedule display with **Map API visualization**

### OPWA (Operator App)
- Manage metro line data & schedules  
- Publish announcements and service updates  
- Trigger real-time suspension alerts  
- Provide APIs for ticketing & wallet management  

---

## 🛠️ Tech Stack
- **Backend:** Spring Boot (Java), N-tier modular architecture  
- **Frontend:** JavaScript (Vanilla/React structure)  
- **Security:** JWT, OAuth2, HTTPS  
- **APIs:** RESTful APIs (Booking, Payment, Wallet, Metro Info)  
- **Database:** JPA/Hibernate with partitioning & sharding for scalability  

---

## 📂 Project Structure
HCMC-Metro-Web-Systems-PAWA/
 ├─ .mvn/               # Maven wrapper
 ├─ src/
 │   ├─ main/
 │   │   ├─ java/com/example/pawa/
 │   │   │   ├─ config/        # Security, JWT, OAuth2
 │   │   │   ├─ controller/    # REST controllers
 │   │   │   ├─ model/         # Entities, DTOs
 │   │   │   ├─ repository/    # JPA repositories
 │   │   │   └─ service/       # Business logic
 │   │   └─ resources/         # application.properties, static, templates
 │   └─ test/java/...          # Unit/integration tests
 ├─ target/             # Build output (ignored in Git)
 ├─ pom.xml             # Maven build file
 └─ README.md


---

## 🎓 Background
Developed as part of **EEET2580 – Enterprise Application Development (RMIT University, Semester 2025A)**.  
The project applied **modularized architectures, secure authentication, and real-time system integration** to simulate enterprise-scale web systems.  

---

## 👨‍💻 Authors
- **Le Trung Kien** – [GitHub](https://github.com/ElwizScott) · [LinkedIn](https://www.linkedin.com/in/elwizscott)  
- **Luu Tuan An** – [GitHub](https://github.com/luutuanan2003)  
- **Pham Nguyen Minh Dang** – [GitHub](https://github.com/darmondcv)  
- **Dang Vinh Luan** – [GitHub](https://github.com/luandang2112)  
- **Duy Huynh** – [GitHub](https://github.com/duyhnynh)

---

## 📜 License
This project is for educational purposes. Feel free to fork and explore, but please credit the original authors when reusing code.  

---

## 📌 Note
This repository is a **copied and maintained version** of the original repo.  
👉 [Original PAWA Repository](https://github.com/BeggerClan/PAWA)  
My sID is **s3878260**.  
