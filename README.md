
# AI-Powered Digital Forensics for Hidden Account Detection

## 📌 Problem Statement
Fake or compromised employee accounts can remain hidden within an organization's network for weeks or months using legitimate credentials. Traditional security systems fail to detect them immediately, leading to risk of data exfiltration, financial loss, and privacy breaches.

## 💡 Solution Overview
An AI-driven digital forensics platform that tracks user behavior, builds continuous behavioral baselines, detects anomalies using machine learning, and provides dynamic risk scores along with an interactive forensic timeline.

## 🛠️ Tech Stack
- **Frontend:** React + Vite, Framer Motion, Recharts, React Flow
- **Backend:** Python, FastAPI
- **Database:** PostgreSQL
- **AI/ML:** Python, Scikit-learn
- **Security:** JWT, bcrypt/Argon2

## 🚀 Setup & Installation

### Frontend Setup
1. `cd frontend`
2. `npm install`
3. `npm run dev`

### Backend Setup
1. `cd backend`
2. `pip install -r requirements.txt`
3. `uvicorn main:app --reload`

## 🔒 Environment Variables
Create a `.env` file in the backend root directory:
DATABASE_URL=postgresql://user:password@localhost:5432/forensic_db
JWT_SECRET=your_secret_key
