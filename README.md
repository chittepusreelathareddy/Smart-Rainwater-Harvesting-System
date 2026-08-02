# Smart-Rainwater-Harvesting-System
IoT-based Smart Rainwater Harvesting System built with React, Vite, Node.js, Express, MongoDB, JWT Authentication, and Arduino/ESP32. Features real-time rain detection, buzzer alerts, sensor monitoring, analytics dashboard, rain event history, and secure user authentication.
# 🌧️ Smart Rainwater Harvesting System

![React](https://img.shields.io/badge/React-19-blue?logo=react)
![Vite](https://img.shields.io/badge/Vite-Frontend-646CFF?logo=vite)
![Node.js](https://img.shields.io/badge/Node.js-22-green?logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-Backend-black?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-38BDF8?logo=tailwind-css)
![Arduino](https://img.shields.io/badge/Arduino-IoT-blue)

## 📌 Overview

The Smart Rainwater Harvesting System is an IoT-based full-stack application that detects rainfall using a rain sensor connected to an Arduino or ESP32. When rain is detected, the system activates a buzzer, records the event, updates the dashboard in real time, and stores the data in MongoDB for monitoring and analysis.

The project combines IoT hardware with modern web technologies to provide an intelligent and automated rain monitoring solution.

---

# ✨ Features

## User Module

- User Registration
- Secure Login
- JWT Authentication
- Profile Management

---

## Rain Monitoring

- Rain Detection
- Sensor Value Monitoring
- Real-time Status
- Rain Event Logging
- Last Detection Time

---

## IoT Integration

- Arduino Support
- ESP32 Support
- Rain Sensor
- Buzzer Alert
- Serial Communication
- HTTP Communication

---

## Dashboard

- Live Rain Status
- Rain Events
- Sensor Readings
- Statistics
- Water Conservation Analytics

---

## Admin Module

- Admin Dashboard
- User Management
- Rain Event Management
- Analytics Reports

---

## Analytics

- Daily Reports
- Weekly Reports
- Monthly Reports
- Rain Frequency
- Sensor Analytics

---

# 🛠 Tech Stack

## Frontend

- React
- Vite
- Tailwind CSS
- Axios

## Backend

- Node.js
- Express.js

## Database

- MongoDB
- Mongoose

## Authentication

- JWT
- bcrypt

## Hardware

- Arduino Uno
- ESP32
- Rain Sensor Module
- Active Buzzer

---

# 🏗 System Architecture

```

Rain Sensor
│
▼
Arduino / ESP32
│
▼
Express Backend
│
▼
MongoDB
│
▼
React Dashboard

```

---

# 📂 Project Structure

```

rainwater-harvesting-system/

frontend/
src/
components/
pages/
services/
hooks/

backend/
controllers/
models/
routes/
middleware/
config/

arduino/
Arduino\_Uno\_Serial/
ESP32\_RainSensor/

docs/
screenshots/

README.md

```

---

# ⚙ Installation

Clone Repository

```bash
git clone https://github.com/yourusername/rainwater-harvesting-system.git
```

Install Frontend

```bash
cd frontend

npm install
```

Install Backend

```bash
cd ../backend

npm install
```

---

# 🔑 Environment Variables

Backend

```

PORT=5000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_secret

DEVICE_SECRET=your_device_secret

```

---

# ▶ Running the Project

Backend

```bash
npm run dev
```

Frontend

```bash
npm run dev
```

---

# 🌐 Main Pages

- Home
- Login
- Register
- Dashboard
- Rain Monitoring
- Rain History
- Analytics
- Profile
- Admin Dashboard
- Settings

---

# 📡 Project Workflow

1. Rain falls on the sensor.

2. Rain sensor detects water.

3. Arduino/ESP32 processes the sensor value.

4. If rain is detected:

   - Buzzer turns ON.
   - Rain event is generated.
   - Sensor data is sent to the backend.

5. Backend stores the data in MongoDB.

6. Dashboard updates the current rain status.

7. Users can view analytics and rain history.

---

# 📊 Database Collections

## User

- Name
- Email
- Password
- Role

---

## RainEvent

- Sensor Value
- Rain Status
- Buzzer Status
- Timestamp
- Duration

---

# 📸 Screenshots

Add screenshots here.

- Home
- Login
- Dashboard
- Rain Monitoring
- Analytics
- Admin Dashboard

---

# 🚀 Future Enhancements

- Water Level Sensor
- Automatic Pump Control
- Solenoid Valve Automation
- SMS Alerts
- Email Notifications
- Weather API Integration
- Mobile Application
- Cloud IoT Dashboard

---

# 🤝 Contributing

Contributions are welcome.

1. Fork repository

2. Create feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Create Pull Request

---

# 📄 License

MIT License

