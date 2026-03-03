# Entresst-AI

[![GitHub Contributors](https://img.shields.io/github/contributors/srakshitha0802/Entresst-AI-)](https://github.com/srakshitha0802/Entresst-AI-/graphs/contributors)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/srakshitha0802/Entresst-AI-)](https://github.com/srakshitha0802/Entresst-AI-/commits/main)

**Lead Developer:** srakshitha0802, lakshmijahnavik 
**Contributors:** SaiPriyamshu, sirishapyadav16

A comprehensive full-stack AI-powered career development platform that helps users track their skills, prepare for interviews, explore job opportunities, and accelerate their career growth.

![Entresst Logo](Entresst%20Logo.jpeg)

## 🚀 Features

### 1. Dashboard
- **User Profile Overview**: Display personalized information based on your target role
- **Skills Radar Chart**: Visual representation of your current skill levels
- **Statistics Cards**: Role match percentage, skill gaps, market growth, certifications due
- **AI Recommendations**: Personalized career advice powered by AI
- **Quick Actions**: Easy navigation to all features from one place.

### 2. Profile Setup
- **Onboarding Flow**: Complete profile setup with name, email, role, and target role
- **Skills Assessment**: Add skills with proficiency levels (1-100 scale)
- **Career Goals**: Define your current role and target role for personalized recommendations
- **Profile Persistence**: Save profile data to storage (Supabase, MongoDB, or in-memory)

### 3. AI-Powered Quiz
- **Dynamic Question Generation**: AI generates questions based on user skill level
- **Adaptive Difficulty**: Quiz gets harder or easier based on performance
- **Category Selection**: Technical, Behavioral, System Design, etc.
- **Real-time Feedback**: Get explanations after each answer
- **Progress Tracking**: Track your quiz history and performance
# Entresst — AI Career Companion

Entresst is a full-stack AI-powered career development platform that helps users track skills, prepare for interviews, explore job opportunities, and accelerate career growth.

Features include: dashboard and profile setup, AI-powered quizzes, mock interviews, resume analysis, job market insights, learning resources, and a game-like XP system.

Quick start
```
git clone https://github.com/lakshmijahnavik/Entresst.git
cd Entresst-AI--main
npm install
npm run dev
```

Available scripts
- `npm run dev` — start the dev server (server + client as configured)
- `npm run build` — build for production
- `npm run start` — start production server
- `npm run check` — run TypeScript checks

Repository layout
- `client/` — React + Vite frontend (TypeScript)
- `server/` — Express backend (TypeScript)
- `shared/` — shared types and schema
- `script/` — build and helper scripts
- `package.json` — project metadata and scripts

Environment
- Node.js 18+ recommended
- Optional env vars: `OPENAI_API_KEY`, `GEMINI_API_KEY`, `HUGGINGFACE_API_KEY`, `MONGODB_URI`, `SUPABASE_*`

Contributing
- Fork, create a feature branch, commit, push, and open a PR.

License
- MIT

If you want the README expanded (badges, screenshots, detailed setup, or contributor list), tell me what to include and I will update it.