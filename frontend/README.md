SkillSphere 
AI-Powered Learning & Collaboration Platform — built with the MERN stack.

Students learn through courses and an AI assistant, mentors create and manage courses, and admins run the platform.

---

Tech Stack
**Frontend:** React, Tailwind CSS, React Router
**Backend:** Node.js, Express, MongoDB
**AI:** Groq (Llama 3.1)

---

Features
- Login/Register with roles: Student, Mentor, Admin
- Browse & enroll in courses, track lesson progress
- AI Assistant — ask questions, get quizzes & roadmaps
- Community feed — post, like, comment
- Resume builder with PDF download
- Separate dashboard for each role
- Admin panel — manage users, courses, categories, mentor approvals

---

How to Run

**Backend**
```bash
cd backend
npm install
cp .env.example .env    # add your MongoDB URI, JWT secret, Groq API key
npm run seed             # adds demo data (optional)
npm run dev
```

**Frontend**
```bash
cd frontend
npm install
cp .env.example .env
npm run dev
```

Open **http://localhost:5173**

---

Demo Logins
| Role | Email | Password |
|------|-------|----------|
| Admin | admin@skillsphere.com | Admin@123 |
| Mentor | mentor@skillsphere.com | Mentor@123 |

---

Team
| Member | Worked On |
|--------|-----------|
| Soumya (Lead) | Login/Register, Dashboards, Admin Panel |
| Kajal | Courses & Categories |
| Shivangi | Community, AI Assistant, Resume Builder |
| Himanshu | Landing Page & UI Components |

---

*Built for academic project submission.*
