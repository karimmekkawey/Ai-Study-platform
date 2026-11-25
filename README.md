# AI Study Platform

A student project for university students to upload lecture PDFs, generate AI summaries and quizzes, and organize study materials.

## Project structure
- `frontend/` — React + Vite
- `backend/` — Node.js + Express + TypeScript
- `backend/src/` — API source code

## Run locally

### 1. Backend
```bash
cd backend
npm install
copy .env.example .env
npm run dev
```
Set the values in `backend/.env` before using database, authentication, storage, or AI features.

### 2. Frontend
Open a second terminal:
```bash
cd frontend
npm install
copy .env.example .env
npm run dev
```

Frontend runs at http://localhost:5173 and backend at http://localhost:5000.

## Important
- Never upload `.env` files or API keys to GitHub.
- This is a starter project structure. Add the database, authentication, PDF, Supabase Storage, and OpenAI implementation to the backend modules before expecting those features to work.
