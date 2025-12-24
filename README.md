# 🚀 SyncNexus

**SyncNexus** is a full-stack platform designed to efficiently connect **job seekers** with **employers**. It addresses inefficiencies in traditional job searching and task assignment by providing a **centralized system** for job posting, task management, and workforce tracking.

---

## ✨ Features
- **Centralized job and task posting system**  
- **Efficient job discovery and application workflow**  
- **Secure user authentication**  
- **Employee location path tracking** for workforce monitoring  
- **Seamless frontend-backend communication** via REST APIs  
- **Mobile-friendly interface** for on-the-go management  

---

## 🖥️ Tech Stack

### Frontend
- **Framework:** Flutter  
- **Language:** Dart  
- **State Management:** Provider / Bloc  
- **HTTP Requests:** Dio / http package  
- **Navigation:** GoRouter  
- **Authentication:** OAuth 2.0  

### Backend
- **Language:** Python  
- **Framework:** FastAPI  
- **Database:** PostgreSQL (Google Cloud SQL)  
- **Authentication:** Firebase Authentication  
- **Deployment:** Google Cloud Run  

---

## 🏗️ Architecture
- Flutter frontend communicates with FastAPI backend via **HTTP APIs**  
- **Firebase Authentication** ensures secure access  
- Backend handles request processing and interacts with **PostgreSQL database**  
- Cloud-hosted SQL database ensures **reliability and low latency**  

---

## 📂 Project Structure

syncnexus/
├── frontend/ # Flutter mobile app
├── backend/ # FastAPI backend
├── demo/ # Demo video and screenshots
└── README.md # This file

### Backend Structure (FastAPI)

backend/
├── auth/ # Authentication modules
├── client/ # Firebase and database clients
├── db/ # Database schema & models
│ ├── base.py
│ ├── tables/
│ └── views/
├── responses/ # Request/response schemas
├── routers/ # API endpoints
├── services/ # Business logic
└── main.py # Application entry point

### Frontend Structure (Flutter)

frontend/
├── lib/screens/ # App screens (Home, Jobs, Tasks)
├── lib/widgets/ # Reusable widgets
├── lib/providers/ # State management
├── lib/services/ # API requests & authentication
└── lib/utils/ # Utility functions

---

## 📌 Setup Instructions

### Backend
1. Set up **virtual environment** and install dependencies  
2. Add **Firebase and Google Cloud credentials** to `keys` folder  
3. Run **database migrations**  
4. Start the **backend server**  

### Frontend
1. Install **Flutter SDK**  
2. Install dependencies:  
flutter pub get
Set environment variables (API base URL, OAuth keys)

Run the app on emulator or device:

flutter run
🌐 Backend API
API documentation is included in the backend repo

🎥 Demo
Watch Demo Video: https://youtu.be/TEWc9LUVjVw?si=tELv3GgJ72YgjuVl 

🧠 Skills Demonstrated
Flutter · Dart · Python · FastAPI · REST APIs · Firebase Authentication · PostgreSQL · Cloud Deployment · Docker · Cloud Architecture · API Design
