# 📓 Daily Journal Tracker

A fullstack web app to help users write daily journal entries, track their moods, and visualize emotional patterns over time.

---

## 🧠 Features

- ✅ User authentication (Register / Login)
- 📖 Write and view daily journal entries
- 😊 Mood tagging (happy, neutral, sad, etc.)
- 📅 Calendar-style journal history
- 📊 Dashboard with mood stats and charts
- 🌙 Dark/Light mode toggle
- 🔒 Supabase Auth + JWT-based API security

---

## 🧱 Tech Stack

### Frontend (React + Tailwind)
- Vite + React
- Tailwind CSS
- React Router
- date-fns (for date handling)

### Backend (Node + Express)
- Express.js
- PostgreSQL
- JSON Web Tokens (JWT)
- dotenv

---

## 📁 Folder Structure

<!-- folder structure here -->


---

## 🚀 Setup Instructions

### 1. Clone the repo
```bash
git clone https://github.com/brillianttonsa/journal-tracker-app.git
cd journal-tracker


cd client
npm install


cd ../server
npm install


# SUPABASE_URL=your_url
# SUPABASE_ANON_KEY=your_key
# JWT_SECRET=your_jwt_secret


# VITE_SUPABASE_URL=your_url
# VITE_SUPABASE_ANON_KEY=your_key

cd server
npm run dev

cd client
nodemon server.js