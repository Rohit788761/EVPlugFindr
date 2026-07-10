# EVPlugFindr
EV Charging Locator &amp; Smart Booking System 

# 🚗⚡ EvPlugFindr – AI-Based EV Charging Locator & Smart Booking System

<p align="center">
  <b>Find • Book • Charge Smartly</b><br>
  An AI-powered platform for locating EV charging stations, checking real-time availability, and booking charging slots.
</p>

---

## 📖 About the Project

EvPlugFindr is an AI-powered EV Charging Locator and Smart Booking System developed as a Final Year Engineering Project. The platform helps electric vehicle users find nearby charging stations, view real-time charger availability, reserve charging slots, and receive intelligent charging recommendations based on distance, availability, and waiting time.

The system also provides separate dashboards for users, station owners, and administrators to efficiently manage charging infrastructure and bookings.

---

## 🎯 Problem Statement

Electric Vehicle (EV) users often face several challenges:

- Difficulty finding nearby charging stations.
- Long waiting times due to occupied chargers.
- Lack of real-time charger availability.
- No intelligent recommendation system.
- Inefficient booking management.

EvPlugFindr addresses these problems by providing a smart and user-friendly charging management platform.

---

# ✨ Features

## 👤 User Features

- User Registration & Login
- Secure Authentication
- Search Nearby Charging Stations
- Interactive Map View
- Real-Time Charger Availability
- Smart Charging Recommendations
- Slot Booking
- Booking History
- Favorite Stations
- Ratings & Reviews
- Notifications
- User Profile Management

---

## 🏢 Station Owner Features

- Owner Dashboard
- Add & Manage Charging Stations
- Manage Chargers
- Update Slot Availability
- View Bookings
- Revenue Dashboard
- Customer Reviews

---

## 🛠️ Admin Features

- Admin Dashboard
- User Management
- Station Management
- Booking Management
- Reports & Analytics
- System Monitoring

---

## 🤖 AI Features

- Smart Charging Recommendation
- Demand Prediction
- Waiting Time Estimation
- Intelligent Station Ranking

---

# 🛠️ Technology Stack

### Frontend
- React.js
- TypeScript
- Vite
- Tailwind CSS
- ShadCN UI
- Framer Motion

### Backend
- Node.js
- Express.js

### Database
- Firebase Firestore

### Authentication
- Firebase Authentication

### Maps
- Mapbox GL

### AI/ML
- Python
- FastAPI
- LightGBM / LSTM *(Based on Implementation)*

---

# 🏗️ System Architecture

```
                 User
                   │
                   ▼
      React + TypeScript Frontend
                   │
                   ▼
          Node.js + Express Backend
                   │
        ┌──────────┴──────────┐
        ▼                     ▼
 Firebase Authentication   Firestore Database
                   │
                   ▼
       AI Recommendation Service
                   │
                   ▼
      Smart Charging Suggestions
```

---

# 📂 Project Structure

```
EvPlugFindr/
│
├── client/               # React Frontend
├── server/               # Express Backend
├── shared/               # Shared Models
├── ml_service/           # AI Prediction Service
├── simulator/            # Charging Data Simulator
├── functions/            # Firebase Cloud Functions
├── package.json
└── README.md
```

---

# 📸 Screenshots

> Add screenshots of your application here.

- Dashboard
<img width="962" height="477" alt="image" src="https://github.com/user-attachments/assets/d4bcb59c-3383-41c9-a0f8-42250aee8770" />

- My Stations
<img width="965" height="453" alt="image" src="https://github.com/user-attachments/assets/d2648796-810b-455c-aefe-803295b8edcf" />

- Financial Ledger
<img width="972" height="552" alt="image" src="https://github.com/user-attachments/assets/21948598-eece-486d-8be3-520c263aa1d6" />

- Mobile Screen
<img width="318" height="666" alt="image" src="https://github.com/user-attachments/assets/96a04b31-ba87-4e9d-a632-f8c8e16d0f55" />
<img width="315" height="657" alt="image" src="https://github.com/user-attachments/assets/71ae4445-888e-4430-ad87-f7c3f4026f3d" />

---

# 🔄 Workflow

```
User Login
      │
      ▼
Search Charging Station
      │
      ▼
Check Availability
      │
      ▼
AI Recommendation
      │
      ▼
Book Charging Slot
      │
      ▼
Payment
      │
      ▼
Booking Confirmation
```

---

# 🚀 Future Enhancements

- IoT-enabled Smart Chargers
- AI Demand Forecasting
- Dynamic Pricing
- EV Battery Health Prediction
- Android & iOS Mobile Applications
- Carbon Emission Tracking
- Voice Assistant Integration

---

# 📚 References

- React Documentation
- Node.js Documentation
- Express.js Documentation
- Firebase Documentation
- Mapbox Documentation
- Python Documentation
- IEEE Research Papers

---

# ⭐ Support

If you found this project useful:

⭐ Star this repository

🍴 Fork this repository

🛠️ Contribute to improve the project

🐞 Report issues if you find any bugs

