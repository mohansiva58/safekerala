# 🏥 Digital Health Record Management System for Migrant Workers – SIH 2025  

![Smart India Hackathon](https://upload.wikimedia.org/wikipedia/en/thumb/f/f9/Smart_India_Hackathon_Logo.png/300px-Smart_India_Hackathon_Logo.png)

## 🚀 Problem Statement
**PS ID:** 25083  
**Title:** Digital Health Record Management System for Migrant Workers in Kerala aligned with Sustainable Development Goals.  
**Organization:** Government of Kerala – Health Service Department  

Kerala hosts a significant migrant population that lacks a **comprehensive health record system**. Migrants often face **language barriers, lack of access to medical history, and mobility issues**, which increases the risk of **infectious disease spread** and limits fair healthcare access.  

Our solution provides a **secure, AI-powered, blockchain-backed health record system** that enables **anywhere access, multilingual support, and government health surveillance**.

---

## 🛠️ Tech Stack

### **Frontend**
- ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)
- ![Typescript](https://img.shields.io/badge/Typescript-3178C6?logo=typescript&logoColor=white)
- ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white)
- ![Framer Motion](https://img.shields.io/badge/FramerMotion-0055FF?logo=framer&logoColor=white)

### **Backend**
- ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
- ![Express.js](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white)
- ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
- ![API](https://img.shields.io/badge/REST%20API-FF6F00?logo=fastapi&logoColor=white)

### **Security**
- ![JWT](https://img.shields.io/badge/JWT-000000?logo=jsonwebtokens&logoColor=white)
- End-to-End Encryption (AES-256)
- OAuth2.0 + Multi-Factor Authentication
- Blockchain (Hyperledger / Ethereum private chain)

### **AI & Advanced**
- ![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white) (Chatbot + Summarizer)  
- ![LangChain](https://img.shields.io/badge/LangChain-000000?logo=chainlink&logoColor=white) (AI Agents)  
- ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white) (Predictive Analytics)  
- ![Google Cloud Speech](https://img.shields.io/badge/Speech%20API-4285F4?logo=googlecloud&logoColor=white) (TTS/STT)  

### **Deployment**
- ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
- ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
- ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white)

---

## ✨ Features & How They Work

### 1. 🔐 **User Registration & Authentication**
- Migrants sign up via **Email / Phone / Aadhaar / OTP**.
- Govt Admin verifies documents → issues **unique Health ID + QR Code**.
- Security: **JWT + Blockchain-based verification**.

---

### 2. 📂 **Health Record Management**
- Users upload medical docs (prescriptions, X-rays, lab reports).
- Stored in **Firebase + Blockchain ledger** (tamper-proof).
- AI Summarizer → Converts medical jargon into **simple, migrant-friendly language**.

---

### 3. 🌍 **Multi-language + Text-to-Speech (TTS/STT)**
- Supports **Malayalam, Hindi, Bengali, Tamil, English**.
- Migrants can **listen to reports in their language** or **speak queries**.
- Powered by **react-i18next + Google Speech API**.

---

### 4. 🤖 **AI Chatbot & Summarizer**
- Migrants ask health questions in their language.
- AI explains test reports & government alerts.
- Built using **GPT/Gemini + LangChain + RAG**.

---

### 5. 📅 **Reminders & Appointments**
- Automatic reminders for **vaccines, medicine doses, checkups**.
- Migrants can book **nearest hospitals/doctors** via **Google Maps integration**.

---

### 6. 🚑 **Emergency Support**
- One-click emergency button → auto-shares health record with nearest hospital.
- Geo-location → Shows **nearest hospital/ambulance contact**.

---

### 7. 🩺 **Doctor / Hospital Access**
- Doctors scan QR → Instantly see verified health records.
- Records are summarized by AI → saves time in emergencies.

---

### 8. 🧠 **Predictive Analytics for Govt**
- AI models analyze health trends in migrant areas.
- Detects possible **disease outbreaks** early.
- Govt dashboards show **public health insights**.

---

### 9. 📱 **Progressive Web App (PWA)**
- Works in **offline mode** (low network regions).
- Migrants can **download app by scanning QR code**.

---

### 10. ⛓ **Blockchain Security**
- Records are **immutable** → can’t be tampered with.
- Migrants control **data sharing consent** with doctors/hospitals.

---

### 11. 📡 **IoT & Wearable Integration** *(Future-ready)*
- Sync data from smart devices (BP monitors, glucose sensors, wearables).
- Auto-updates migrant health profile.

---

## 🏗️ System Architecture
(Add your PPT diagram here – showing **User → Dashboard → Blockchain + Cloud → Doctor → Govt Analytics**)

---

## ⚡ Installation & Setup

```bash
# Clone repo
git clone https://github.com/your-repo.git

# Install dependencies
npm install

# Run development
npm run dev

# Build production
npm run build
npm start
