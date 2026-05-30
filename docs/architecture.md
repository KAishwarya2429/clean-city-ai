# System Architecture

## High Level Architecture

Citizen App / Web Portal
↓
Frontend Layer
(Next.js + React)
↓
Backend API Layer
(FastAPI)
↓
AI Services Layer
↓
Database & Storage Layer
↓
Municipal Dashboard
↓
Notification Services

---

## Frontend Layer

Technologies:

- Next.js
- React
- Tailwind CSS

Responsibilities:

- User authentication
- Complaint submission
- GPS location capture
- Photo and video upload
- Complaint tracking
- Municipal dashboard interface

---

## Backend Layer

Technologies:

- FastAPI
- REST APIs
- JWT Authentication

Responsibilities:

- User management
- Complaint processing
- Status updates
- Notification handling
- Integration with AI services

---

## AI Layer

Modules:

### Image Analysis

Detect:

- Garbage accumulation
- Overflowing bins
- Illegal dumping
- Smoke and pollution

### Complaint Classification

Automatically classify:

- Missed collection
- Overflowing dustbin
- Illegal dumping
- Pollution issue

### Prediction Engine

Predict:

- Bin overflow
- Waste generation trends
- Collection demand

---

## Database Layer

Technology:

- PostgreSQL

Core Tables:

- Users
- Complaints
- SmartBins
- Workers
- Vehicles
- Wards
- Notifications
- Reports

---

## Storage Layer

Technology:

- AWS S3
- Firebase Storage

Stores:

- Images
- Videos
- Reports
- System logs

---

## IoT Layer

Components:

- ESP32 Controller
- Ultrasonic Sensor
- Smoke Sensor
- GPS Module

Functions:

- Monitor fill levels
- Detect fire/smoke
- Send real-time alerts
- Track smart bin locations

---

## Notification Layer

Channels:

- Email
- SMS
- Push Notifications
- WhatsApp

---

## Future Architecture Enhancements

- AI route optimization
- Real-time vehicle tracking
- Voice complaint system
- Smart city integrations
- Carbon impact analytics
