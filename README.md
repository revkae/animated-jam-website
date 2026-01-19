# 🎬 Animation Jam Site

A full-stack web platform for hosting animation competitions, built for **TEDU Animation Jam**. Users can submit their animations, vote on entries, comment, and compete for recognition.

<p align="center">
 <img width="800" height="400" alt="hero" src="https://github.com/user-attachments/assets/eaef8d78-094d-4c26-a2b6-81e24af95cf2" />
</p>

---

## ✨ Features

- 🔐 User authentication with role-based access (user/moderator/admin)
- 🎥 YouTube video submissions with thumbnail extraction
- ⭐ Multi-criteria voting system (creativity, technical skill, etc.)
- 💬 Commenting with likes
- 🛠️ Admin dashboard for managing submissions, users, and settings
- 🛡️ CSRF protection with double-submit cookie pattern
- 🔧 Maintenance mode toggle
- 📱 Responsive design with custom TEDU branding

---

## 📸 Screenshots

<p align="center">
  <img width="400" height="250" alt="jampage" src="https://github.com/user-attachments/assets/8908d438-6c05-430d-a211-0e5c1a75948a" />
  <img width="400" height="250" alt="leaderboardpage" src="https://github.com/user-attachments/assets/cbd4a750-acab-48e3-9fb1-e6751d2d5d74" />
</p>

<p align="center">
  <img width="400" height="250" alt="adminpanelpage" src="https://github.com/user-attachments/assets/9c0336bd-805c-411e-a72e-9bde0fb4ec02" />
  <img width="400" height="250" alt="profilepage" src="https://github.com/user-attachments/assets/94791dad-3253-4894-acaa-bebed037d967" />
</p>

---

## 🛠️ Tech Stack

### Frontend
<p align="left">
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js_15-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
  <img alt="React" src="https://img.shields.io/badge/React_19-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript_5-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS_4-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  <img alt="shadcn/ui" src="https://img.shields.io/badge/shadcn/ui-000000?style=for-the-badge&logo=shadcnui&logoColor=white"/>
  <img alt="GSAP" src="https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black"/>
</p>

### Backend & Database
<p align="left">
  <img alt="Supabase" src="https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white"/>
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

### Forms & Validation
<p align="left">
  <img alt="React Hook Form" src="https://img.shields.io/badge/React_Hook_Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white"/>
  <img alt="Zod" src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white"/>
</p>

### Testing
<p align="left">
  <img alt="Vitest" src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white"/>
  <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white"/>
</p>

---

## 🔒 Security Features

| Feature | Implementation |
|---------|----------------|
| Authentication | Supabase Auth with session management |
| Authorization | Row Level Security (RLS) policies |
| CSRF Protection | Double-submit cookie pattern |
| XSS Prevention | DOMPurify input sanitization |
| Type Safety | Generated Supabase types + Zod validation |

---

## 📚 What I Learned

- Implementing secure authentication flows with Supabase Auth
- Writing Row Level Security policies for fine-grained access control
- Building a robust CSRF protection system from scratch
- Structuring a large Next.js project with services and hooks patterns
- Type-safe development with generated Supabase types
- E2E testing with Playwright across multiple browsers
- Managing complex state with React 19 features
- Input sanitization to prevent XSS attacks

---

<p align="center">
  Built with ❤️ for <b>TEDU Animation Jam</b>
</p>
