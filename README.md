# 🚀 CareerForge – AI Career Companion

- **🔗Live Demo:** https://career-forge-pi.vercel.app/

CareerForge is an AI-powered career guidance platform designed to help students and early professionals understand their career readiness, identify skill gaps, plan learning paths, prepare for interviews, and explore relevant job opportunities — all in one place.

---

## 🧠 Problem Statement

Many learners struggle with:
- Lack of clarity about their career readiness
- Not knowing which skills they are missing
- Random learning without a structured plan
- Difficulty preparing for interviews
- Confusion about where and how to apply for jobs

CareerForge solves this by acting as a **personal career operating system**.

---

## 💡 Solution Overview

CareerForge analyzes a user’s resume and target role, then uses AI to:
- Evaluate career readiness
- Identify missing and existing skills
- Generate a personalized learning plan
- Suggest resume-worthy project ideas
- Conduct AI-driven mock interviews
- Recommend relevant job opportunities and market trends

---

## ✨ Key Features

### 🔐 Authentication
- Email & password-based authentication (client-side for hackathon scope)
- User-specific data persistence using local storage
- Easily replaceable with Firebase/Auth0 in production

---

### 📄 Resume Analysis
- Accepts resume text or PDF upload
- AI extracts skills and evaluates readiness for a chosen role
- Generates:
  - Readiness score
  - Strengths & weaknesses
  - Skill gap analysis

---

### 📚 Personalized Learning Plan
- Weekly structured learning roadmap
- Tasks categorized as:
  - Courses
  - Projects
  - Reading
- Users can:
  - Mark tasks as completed
  - Add or delete tasks manually
  - Track learning progress

---

### 🛠️ Project Recommendations
- AI-generated project ideas tailored to the target role
- Includes:
  - Difficulty level
  - Tech stack
  - Key features
  - Resume value explanation

---

### 🎤 AI Mock Interview
- Interactive chat-based interview simulation
- Voice input (speech-to-text)
- AI voice responses (text-to-speech)
- Post-interview feedback with:
  - Score
  - Strengths
  - Improvement areas
  - Focus recommendations

---

### 💼 Job Matching (AI-Assisted)
- AI-generated job recommendations based on:
  - Target role
  - Skill set
- Includes:
  - Company
  - Location
  - Skill match score
  - Suggested application links  
⚠️ *For hackathon scope, job listings are AI-suggested and not fetched from live APIs.*

---

### 📊 Market Trends
- AI-generated insights on:
  - Salary ranges
  - Demand levels
  - Emerging technologies
  - Industry news and impact

---

## 🧩 Tech Stack

### Frontend
- **React 19**
- **TypeScript**
- **Tailwind CSS**
- **Lucide Icons**
- **Recharts**

### AI & Logic
- **Google Gemini API**
- Resume analysis
- Learning plan generation
- Interview simulation
- Job & trend recommendations

### Tooling & Deployment
- **Vite**
- **Vercel**
- **Local Storage** (hackathon persistence)

---

## 🏗️ Project Structure

```
careerforge/
│
├── components/
│   ├── DashboardCards.tsx
│   ├── LandingPage.tsx
│   ├── ScoreGauge.tsx
│   ├── Sidebar.tsx
│   ├── SkillCard.tsx
│   ├── SkillsContainer.tsx
│   └── TopNavigation.tsx
│
├── services/
│   ├── authService.ts
│   └── gemini.ts
│
├── App.tsx
├── README.md
├── index.html
├── index.tsx
├── metadata.json
├── package.json
├── package-lock.json
├── tsconfig.json
├── types.ts
├── vercel.json
├── vite-env.d.ts
└── vite.config.ts
```

---

## 🔐 Authentication Note

Authentication is **mocked and client-side** for hackathon demonstration purposes.  
The architecture is designed to support production-grade authentication services such as Firebase or OAuth without refactoring core logic.

---

## ⚠️ Disclaimer

This project was built as part of a hackathon.  
Some data such as job listings and application links are **AI-suggested** and not fetched from real-time APIs. The system is designed to be easily extended with live data sources.

---

## 🎯 Future Enhancements

- Real-time job API integration (LinkedIn, Indeed)
- Firebase authentication
- Cloud database (Firestore)
- Resume versioning
- Career progress analytics
- Multi-language support

---

## 👥 Team

Built with passion and purpose by our hackathon team 💙  
CareerForge is a step toward smarter, clearer career decisions.

---

## 🏁 Conclusion

CareerForge doesn’t just tell users what they lack —  
It tells them **exactly what to do next**.
