
# SABRANG Setup Instructions

## Backend (Render)
1. Go to `backend/`
2. Copy `.env.example` → `.env`
3. Run:
   npm install
   node server.js

### Required ENV Vars:
MONGO_URI=mongodb+srv://kumaranshuraj10:7992469345@cluster0.nuttzp2.mongodb.net/
JWT_SECRET=sabrang_secret_key
PORT=5000
ADMIN_EMAIL=kumaranshuraj10@gmail.com

## Frontend (Vercel)
Set this in environment:
REACT_APP_API_URL=https://your-backend.onrender.com
