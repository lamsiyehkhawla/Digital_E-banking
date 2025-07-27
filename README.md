
---

# 💰 Digital Banking System

A full-stack digital banking application consisting of:

- 🏦 `ebanking-backend`: Spring Boot REST API
- 💻 `ebanking-frontend`: Angular client
- 🧰 Modular monorepo for development

---

## 🔗 Project Structure

Digital_banking/
├── ebanking-backend/ # Spring Boot API

└── ebanking-frontend/ # Angular 

---

## ⚙️ Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/lamsiyehkhawla/Digital_banking.git
cd Digital_banking
```
 Run the Backend
```bash
cd ebanking-backend
./mvnw spring-boot:run
```
Access API at:

http://localhost:8080
3. Run the Frontend
```bash
cd ../ebanking-frontend
npm install
ng serve
```
App available at:
http://localhost:4200

✅ Features Overview
Module	Description
Backend	Customer/account/transaction APIs
Frontend	Web UI for account & transaction
Data Initialization	Preloaded data for testing

🧠 Author
Khawla Lamsiyeh
GitHub: @lamsiyehkhawla

📌 Notes
You can switch from H2 to MySQL in application.properties.

Frontend uses Angular HttpClient and must match backend API URLs.

