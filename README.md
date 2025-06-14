# 🎬 MovieMitra

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Made with MERN](https://img.shields.io/badge/stack-MERN-green)
![Deployed on Vercel](https://img.shields.io/badge/deployed-Vercel-blue)

MovieMitra is a full-stack movie ticket booking web application where users can browse movies, view showtimes, and book tickets seamlessly. Built using the MERN stack with real-time email notifications, secure payment integration, and role-based admin features.

🔗 **Live App**: [https://moviemitra-kappa.vercel.app/](https://moviemitra-kappa.vercel.app/)  
📁 **Backend Repo**: [GitHub - MovieMitra](https://github.com/rishitagrawal217/MovieMitra)

---

## 🚀 Features

- 🔐 User authentication and role-based access with **Clerk**
- 🎞 Movie data integration using **TMDB API**
- 🛒 Seat selection and ticket booking
- 💳 Online payments via **Stripe**
- 📬 Email confirmations via **Brevo**
- 🧠 Background tasks and reminders using **Inngest**
- 🛠 Admin dashboard to manage movies and shows

---

## 🛠 Tech Stack

**Frontend**:
- React + Vite
- Tailwind CSS
- Axios
- Clerk

**Backend**:
- Node.js + Express
- MongoDB Atlas
- Stripe API
- TMDB API
- Brevo (email service)
- Inngest (background jobs)

---

## 🧑‍💻 How to Run Locally

### ✅ Prerequisites

- Node.js & npm
- MongoDB Atlas Account
- TMDB Account
- Clerk Account
- Brevo Account
- Inngest Account
- Stripe Account

### 📦 Backend Setup

```bash
git clone https://github.com/rishitagrawal217/MovieMitra.git
cd MovieMitra/server
npm install
