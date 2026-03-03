🛡️ CyberShield – Cyber Threat Detection & SOC Dashboard

CyberShield is a full-stack Cyber Threat Detection and Security Operations Center (SOC) Dashboard that monitors, visualizes, and analyzes cyber attacks in real time.

It simulates how enterprise SOC platforms operate by streaming live threat events, mapping them to MITRE ATT&CK techniques, and providing AI-assisted cybersecurity insights.

🚀 Features
🔐 Authentication & Role-Based Access

Secure login & registration

JWT-based authentication

Role-based access (User / Analyst)

📊 Real-Time Threat Feed

Live cyber attack events

Attack type classification (Malware, DDoS, Phishing, SQL Injection, Brute Force)

Severity levels (Low / Medium / High / Critical)

Source & Target IP tracking

MITRE ATT&CK mapping (e.g., T1078 – Initial Access)

Real-time updates using Socket.IO

📈 Dashboard Analytics

Total threat count

Severity distribution

Attack type statistics

Geographical threat activity

🧠 AI Cybersecurity Assistant

Ask cybersecurity-related questions

AI-powered explanation system

Knowledge-based threat guidance

🌐 Network Scanner

Detect active hosts

Identify open ports

Discover potentially vulnerable systems

🔎 QR / URL Scanner

Detect malicious URLs

Evaluate suspicious QR codes

Risk scoring system

🗂 Incident Management

Group threats into incidents

Track investigation status

Monitor workflow (Active / Investigating / Resolved)

🏗️ System Architecture
Frontend (React + Tailwind)
        ↓
Node.js + Express Backend
        ↓
MongoDB Database
        ↓
Python AI Engine

Frontend: Interactive SOC dashboard

Backend: REST API + Threat engine

Database: MongoDB

AI Engine: Flask-based NLP threat assistant

Real-time Communication: Socket.IO

🛠 Tech Stack
Frontend

React.js

Tailwind CSS

Vite

Backend

Node.js

Express.js

JWT Authentication

Socket.IO

Database

MongoDB

AI Engine

Python (Flask)

TF-IDF Similarity Model

📦 Installation & Setup
1️⃣ Clone Repository
git clone https://github.com/yourusername/cybershield.git
cd cybershield
2️⃣ Setup Backend
cd server
npm install
npm run dev

Server runs on:

http://localhost:5000
3️⃣ Setup Frontend
cd client
npm install
npm run dev

Open:

http://localhost:8080
4️⃣ Setup AI Engine
cd ai-engine
pip install -r requirements.txt
python app.py

AI Engine runs on:

http://localhost:5001
🔑 Default Roles

User – Monitor dashboard & threats

Analyst – Investigate incidents & analyze threats

(Admin role optional for user management.)

🎯 Project Objectives

Provide real-time cyber threat visualization

Simulate enterprise SOC workflow

Implement threat intelligence mapping

Integrate AI-assisted cybersecurity explanations

Demonstrate full-stack security monitoring system

🌍 Real-World Inspiration

CyberShield is inspired by enterprise SOC platforms such as:

Splunk

IBM QRadar

Microsoft Sentinel

📌 Future Enhancements

Real external threat intelligence integration

Automated response mechanisms

Advanced machine learning threat detection

Email alert system

Cloud deployment (AWS/Azure)

📜 License

This project is developed for academic and educational purposes.
