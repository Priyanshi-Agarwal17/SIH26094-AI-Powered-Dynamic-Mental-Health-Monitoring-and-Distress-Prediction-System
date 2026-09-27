

# SIH26094 - AI-Powered Dynamic Mental Health Monitoring and Distress Prediction System

AI-Powered Dynamic Mental Health Monitoring and Distress Prediction System for Victims of Atrocities.

## 📌 Problem Statement Details 

- Problem ID: SIH26094
- Project Title: AI-Powered Dynamic Mental Health Monitoring and Distress Prediction System for Victims of Atrocities
- Sponsoring Ministry: Ministry of Social Justice and Empowerment (MoSJE)
- Department: Department of Social Justice and Empowerment
- Category: Software
- Theme: MedTech / HealthTech

## 🚀 Live Demo Link

[Click here to view the live project prototype]

(https://sahaaya.base44.app/login)

## 📖 About The Project

Victims of atrocities often face heavy emotional stress and trauma. **Sahaaya** is a smart, safe, and multilingual app designed to check on their mental health regularly. It catches early signs of stress and instantly connects them with counsellors and support teams before things get serious.

## ✨ Key Features

- Multilingual Chat Support: Understands local languages to catch stress signs from daily text check-ins.
- Easy Video Health Checks: Safely checks basic physical stress signs using the camera without storing private data.
- Voice Stress Detector: Listens to voice notes to detect emotional tiredness and heavy breathing patterns.
- Smart Alert System: Automatically sends secure alerts to authorities if high risk is detected.
- Complete Privacy: Keeps user data fully encrypted and secure.
- Clear Reports for Doctors: Gives simple reason cards to doctors so they know why an alert was sent.

## 💻 Technologies We Used

- Mobile App: Flutter (Works smoothly on Android and offline)
- Web Dashboard: React, Tailwind CSS, TypeScript
- Backend: FastAPI (Python) / Firebase
- Database: PostgreSQL and secure local storage
- AI & ML Models: IndicBERT, Whisper, MediaPipe, Random Forest, XGBoost
- Notifications: Firebase Cloud Messaging / SMS

## 📂 Folder Structure

- sahaaya-project/
  - mobile/ (Android app screens and logic)
  - web/ (Admin and doctor dashboard pages)
  - backend/ (Server and api endpoints)
  - ai-models/ (Speech, text, and camera AI tools)
  - README.md

## 🔄 How It Works

1. User Input: Users share text, voice notes, or do quick check-ins through the mobile app.
2. Smart Processing: The system runs checks locally and securely on the cloud to look for stress signs.
3. Risk Score Check: AI models check the data and calculate if the user needs help.
4. Quick Help Sent: If stress is high, trusted helpers and authorities get an instant alert with clear details.

## ⚙️ How to Run Locally

1. Clone this repository:
   git clone https://github.com/your-username/SIH26094-AI-Powered-Dynamic-Mental-Health-Monitoring-and-Distress-Prediction-System.git

2. Start the backend server:
   cd backend
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   uvicorn main:app --reload

3. Start the web dashboard:
   cd ../web
   npm install
   npm run dev

## 🔮 Future Plans

- Connect directly with national emergency help numbers for fast physical rescue.
- Add support for smartwatches to track heart rate and continuous stress.
- Expand language support to cover all major regional languages.

