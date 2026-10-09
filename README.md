# CSC220 Week 11 - Full-Stack Student Manager

React (Vite) + Express + MongoDB + CORS + JWT.

## Run
1. `cd server && npm install`, copy `.env.example` to `.env` and fill in `MONGO_URI`, then `npm run dev` (http://localhost:3000)
2. Register a user once in Postman: POST /api/auth/register `{"email":"student1@example.com","password":"password123"}`
3. `cd client && npm install && npm run dev` (http://localhost:5173)
