# 🎯 Emotion-Aware Coding & AI Interview Platform

An AI-powered learning platform that combines coding practice, AI-powered mock interviews, real-time emotion recognition, and performance analytics to provide a personalized technical learning experience.

---

## 🚀 Features

### 🔐 User Authentication
- Secure user registration and login
- Personalized interview and coding sessions
- Session-based progress tracking

### 🎮 Story Mode
- Narrative-based coding challenges
- XP and level progression
- Building restoration mechanics
- Gamified learning experience

### 💻 Coding Practice Environment
- Interactive coding challenges
- Solution submission workflow
- Real-time coding interface

### 😊 Emotion Monitoring
- Webcam-based emotion detection
- Real-time learner-state analysis
- Detection of engagement and focus levels
- Supports emotion-aware learning experiences

### 📊 Progress Dashboard
- Track completed interview sessions
- View coding performance history
- Monitor learning progress over time
- Personalized performance analytics
- XP and level tracking
- Leaderboard support

---

## 🏗️ System Architecture

```text
User
  │
  ▼
Frontend (React + Vite)
  │
  ▼
Backend API (FastAPI)
  │
  ├── Authentication Module
  ├── Story Mode (Coding Engine)
  ├── Interview Module
  ├── Emotion Detection Module
  ├── AI Integration (Gemini)
  │
  ▼
MongoDB
```

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- Tailwind CSS
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- FastAPI
- Uvicorn

### Database
- MongoDB
- Motor (Async MongoDB Driver)

### AI & Computer Vision
- Google Gemini API
- DeepFace
- OpenCV
- TensorFlow

### Authentication
- JSON Web Tokens (JWT)
---

## 📂 Project Structure

```text
.
├── backend-20260617T174429Z-3-001/
│   └── backend/
│
├── frontend-20260617T174429Z-3-001/
│   └── frontend/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/hiflyer246/Emotion-Aware-AI-Mock-Interview-System.git
cd Emotion-Aware-AI-Mock-Interview-System
```

### 2. Create and Activate Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3. Install Backend Dependencies

```bash
cd backend
pip install -r requirements.txt
```

### 4. Install Frontend Dependencies

Open a new terminal:

```bash
cd frontend
npm install
```

---

## 🚀 Running the Application

### Start Frontend

Open Terminal 1:

```bash
cd frontend
npm run dev
```

### Start Backend

Open Terminal 2:

```bash
venv\Scripts\activate
cd backend
python app.py
```

---

## 🌐 Access the Application

Frontend:

```text
http://localhost:5173
```

Backend API:

```text
http://localhost:8000
```

## 📸 Key Modules

### Login & Authentication
Provides secure access and personalized user sessions.

### Coding Challenge Interface
Allows users to solve programming problems in an interactive environment.

### Emotion Detection System
Monitors learner engagement and emotional state through webcam-based analysis.

### Progress Tracking Dashboard
Displays completed sessions, coding history, and performance analytics.

### Session Management
Maintains learning continuity across coding and interview practice sessions.

---

## 🎓 Applications

- Mock Interview Preparation
- Coding Skill Assessment
- AI-Assisted Learning Platforms
- Emotion-Aware Educational Systems
- Personalized Learning Environments

---

## 👨‍💻 Author

**Akula Akhil**

📧 akulaakhil999@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/akula-akhil/

🐙 GitHub: https://github.com/hiflyer246

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 📜 License

This project is developed for educational and research purposes.
