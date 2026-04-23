# 🚀 Cloud-Based QR Attendance System

A scalable, serverless attendance management system that uses QR codes to mark and track student attendance in real-time. Built with modern cloud architecture and a clean, responsive frontend.

---

## 📌 Project Overview

This project enables seamless attendance tracking using dynamically generated QR codes. Each student scans a time-bound QR to mark attendance, ensuring secure and duplicate-free records.

The system is designed using a **serverless architecture**, ensuring high scalability, low operational overhead, and cost efficiency.

---

## 🎯 Key Features

- 🔐 **Role-Based Access**
  - Separate interfaces for Admin and Students

- 📷 **QR Code-Based Attendance**
  - Unique QR per session
  - Auto-expiry (5 minutes)

- 🚫 **Duplicate Prevention**
  - Ensures one-time attendance marking per session

- ⚡ **Real-Time Tracking**
  - Instant attendance updates

- 📊 **Dashboard UI**
  - Clean and modern admin dashboard
  - Attendance analytics and logs

- ☁️ **Cloud Integration**
  - Fully deployed using AWS services

---

## 🏗️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- React Router
- HTML5 QR Scanner

### Backend (Serverless)
- AWS Lambda
- API Gateway
- DynamoDB

### Cloud & Tools
- AWS (Serverless Architecture)
- Git & GitHub

---

## 🧠 System Architecture

1. Admin generates QR code for a session
2. QR contains session ID + expiry timestamp
3. Student scans QR using frontend
4. API validates:
   - Session validity
   - Expiry time
   - Duplicate entry
5. Attendance is stored in DynamoDB

---

## 🔐 Security Features

- Time-bound QR codes (5-minute expiry)
- Input validation at API level
- Duplicate attendance prevention logic
- Secure API endpoints

---

🚀 Future Enhancements
📊 Advanced analytics dashboard
📱 Mobile app integration
🔔 Notification system
🌐 Multi-organization support
🔐 Authentication with AWS Cognito

---

👩‍💻 Author

Sravanthi V
Aspiring Software Engineer | Cloud & Full Stack Developer

---

⭐ Acknowledgements

This project was built as part of a cloud-based system design implementation focusing on serverless architecture and real-world scalability.
