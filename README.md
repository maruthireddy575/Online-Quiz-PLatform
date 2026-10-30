# Online-Quiz-PLatform
A comprehensive, Online Quiz Platform featuring dual portals for "Teachers" and "Students". Teachers can create and manage quizzes, while students can attempt them, track their progress, and compete on leaderboards.

## 🚀 Features

### 👨‍🏫 Teacher Portal
- Dashboard & Analytics:** Track student performance, quiz completion rates, and average scores.
- Quiz Creation:** Intuitive interface to create quizzes with multiple choice, true/false, and single-answer questions.
- Question Builder:** Add images, explanations, and set custom points per question.
- Student Management:** View individual student progress and performance metrics.

### 👨‍🎓 Student Portal
- Interactive Dashboard:** Track completed quizzes, average scores, and current streaks.
- Dynamic Quiz-Taking:** Real-time countdown timers, auto-save functionality, and question navigation grid.
- Instant Results:** Detailed performance breakdown with correct answers, explanations, and time spent per question.
- Global Leaderboard:** Compete with other students based on accuracy and speed.

### 🔒 Core Features
- Role-Based Access Control (RBAC):** Secure routing for Students, Teachers, and Admins.
- JWT Authentication:** Secure login, registration, and protected API routes.
- Responsive UI:** Fully mobile-friendly design using Tailwind CSS.

---

## 💻 Tech Stack

# Frontend:
- React.js (Vite)
- Tailwind CSS (Styling)
- React Router DOM (Navigation)
- Chart.js (Analytics)
- Axios (API Requests)
- React Icons

# Backend (Node.js Version):
- Node.js & Express.js
- MongoDB & Mongoose
- JSON Web Tokens (JWT) & Bcrypt
- Winston (Logging)


---

## 🚀 How to Run This Project Locally

> ⚠️ The backend and frontend must be run in **separate terminals**.

### 📦 Setup & Run Commands (copy-paste once)

```bash
# Clone the repository
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>

# Backend setup
cd backend
npm install
node src/server.js

# IMPORTANT:
# node src/server.js blocks the terminal.
# Open a NEW terminal before running the commands below.

# Frontend setup (new terminal)
cd frontend
npm install
npm run dev

```
## Local URLs

### Backend: http://localhost:5000

### Backend health check: http://localhost:5000/health

### Frontend: http://localhost:5173
