# 🤖 AI Interview Simulator

An AI-powered interview preparation platform built using MERN stack that simulates real interview experiences with live feedback.

---

## 🚀 Features

- 🎤 Real-time AI interview simulation
- 🧠 AI-generated questions based on role
- 💬 Live feedback and suggestions
- 🔐 Authentication (Login/Register)
- 📊 Performance tracking
- 🌐 Full-stack MERN application

---

## 🛠️ Tech Stack

### Frontend
- React.js
- SCSS
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### AI Integration
- Gemini API (Google AI)

---

## 📁 Project Structure
/Frontend
├── src/
├── features/
├── styles/

/Backend
├── controllers/
├── routes/
├── models/
├── services/

## ⚙️ Setup Instructions

### 1. Clone the repository

git clone https://github.com/your-username/ai-interview-simulator.git

### 2.Install Dependencies
a) Backend
cd Backend
npm install

B) cd Backend
npm install

### 3. Setup Environment Variables
Create a .env file inside Backend:
MONGO_URI=your_mongo_uri
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_api_key

### 4. Run the project
Backend
npm run dev

🔗 API Endpoints
POST /api/auth/register
POST /api/auth/login
POST /api/interview/start
POST /api/interview/feedback

🎯 Future Improvements
Voice-based interview
Resume-based question generation
AI scoring system
Dashboard analytics

👨‍💻 Author
Sanskar Agrawal

⭐ Contribute

Feel free to fork this repo and contribute!



