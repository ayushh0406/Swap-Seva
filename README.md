# SwapSeva - AI-Powered Barter System

SwapSeva is an AI-driven barter system with blockchain integration, real-time trade synchronization, skill-sharing via video calls, and a user community for seamless exchange.

---

## 🚀 Features

✅ **AI-Powered Matching** – Smart trade recommendations using TF-IDF & Nearest Neighbors.  
✅ **Blockchain Integration** – Secure and transparent barter records.  
✅ **Real-Time Trade Sync** – Multi-user trade execution with WebSockets.  
✅ **OTP-Based Login** – Secure authentication via Firebase.  
✅ **Video Calls** – Skill-sharing and barter discussions using ZegoCloud.  
✅ **Community Interactions** – Engage with other users in discussion forums.  

---

## 🛠️ Tech Stack

**Frontend:** Next.js, TailwindCSS, ZegoCloud, Firebase  
**Backend:** FastAPI, MongoDB, Socket.io, Blockchain (optional)  
**AI Matching:** TF-IDF, Nearest Neighbors  

---

## 📂 Installation

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/ayushh0406/swap-seva.git
cd swap-seva
```

### **2️⃣ Setup Environment Variables**
Rename `.env.example` to `.env` and update the values:
```plaintext
# Backend
MONGO_URI=mongodb+srv://your-mongo-uri
FIREBASE_CREDENTIALS=your-firebase-key.json
ZEGOCLOUD_APP_ID=your_app_id
SECRET_KEY=your_secret_key

# Frontend
NEXT_PUBLIC_FIREBASE_API_KEY=your_api_key
NEXT_PUBLIC_ZEGOCLOUD_APP_ID=your_app_id
NEXT_PUBLIC_SOCKET_SERVER=http://localhost:8000
```

### **3️⃣ Backend Setup (FastAPI + MongoDB)**
```bash
cd server
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
uvicorn main:app --reload
```

### **4️⃣ Frontend Setup (Next.js)**
```bash
cd client
npm install
npm run dev
```

---

## ⚡ Usage
- Open `http://localhost:3000` for frontend.  
- Backend runs on `http://localhost:8000`.  
- Make sure MongoDB and Firebase are configured correctly.  




