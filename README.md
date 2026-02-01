# 🏠 RENTIVO

**RENTIVO** is a smart, location-based rental platform that simplifies the process of finding and listing rental rooms and flats in India.  
It enables **direct, verified connections** between landlords and renters with a modern UI, map-based discovery, and preference-driven search.

---

## 🚀 Features

### 👤 Landlord
- Secure login using OTP authentication
- Upload rental listings with photos & videos
- Hierarchical location selection (Country → State → District → City)
- Monthly rent & security deposit setup
- Tenant preferences (Veg / Non-Veg, Family / Bachelor)
- Google Maps location pin (auto-detect & manual)
- Manage, edit, and delete property listings

### 🧑‍💼 Renter
- Search rental properties by location
- Apply smart filters (budget, preferences, furnishing)
- View property images, videos, rent, and facilities
- Map-based nearby property discovery
- Show interest and contact landlord after approval

---

## 🧠 System Highlights
- Role-based access control (Landlord / Renter)
- Secure contact unlocking to prevent spam
- Scalable backend-ready architecture
- Cloud media storage with CDN support
- Optimized geo-based search

---

## 🛠 Tech Stack

### Frontend
- React / Next.js
- Tailwind CSS / CSS Modules
- Framer Motion (animations)

### Backend
- Node.js / Firebase / Supabase
- RESTful APIs
- JWT Authentication

### Database
- PostgreSQL / Firestore

### Services
- Google Maps API
- Cloud Storage (Firebase / AWS S3)

---

## 🏗️ Architecture Overview

Client (Web / Mobile)
|
v
API Gateway
|
| Auth | Property | Search |
    |
 Database
    |
Media Storage


---

## 🔐 Authentication Flow
1. User enters phone number
2. OTP verification
3. JWT token generation
4. Role-based access granted

---

## 📂 Project Structure

rentivo/
│
├── client/ # Frontend application
├── server/ # Backend services
├── api/ # API routes
├── database/ # DB schemas & migrations
├── docs/ # System design & docs
├── public/ # Static assets
└── README.md


---

## ⚙️ Installation & Setup

### Prerequisites
- Node.js (>= 18)
- npm / yarn
- Google Maps API key

### Clone the Repository
```bash
git clone https://github.com/your-username/rentivo.git
cd rentivo
Install Dependencies
npm install
Environment Variables
Create a .env file:

GOOGLE_MAPS_API_KEY=your_key_here
JWT_SECRET=your_secret_here
DATABASE_URL=your_database_url
Run the App
npm run dev
🌱 Future Enhancements
In-app chat between renter & landlord

Premium & featured listings

Recommendation engine

Admin dashboard

Mobile app (Android / iOS)

🤝 Contributing
Contributions are welcome!

Fork the repo

Create a new branch

Commit your changes

Open a Pull Request
