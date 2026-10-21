# Hi, I'm Filippo 👋

**Junior full-stack developer** based in Brussels 🇧🇪. I graduated in Application Development from
Haute École Léonard de Vinci in 2026. I like building complete products, from the database schema
to the screen, and I care about tests, security and shipping things that actually get used.

- 💼 Open to **full-stack, web and software developer** roles in Belgium (on-site, hybrid or remote)
- 🧪 Test-driven by habit: Vitest, Jest, testthat, pgTAP
- 🤖 Into AI, VR, 3D printing, drones, and automating anything I do twice
- 🌍 Italian (native) · French (C2) · English (C1)
- 🤽 Water polo player and former youth coach

---

### 🛠️ Tech stack

**Languages**<br>
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)

**Frontend & mobile**<br>
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square&logo=react&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)

**Backend & data**<br>
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=flat-square)

**DevOps & tools**<br>
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Keycloak](https://img.shields.io/badge/Keycloak-4D4D4D?style=flat-square&logo=keycloak&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white)

---

### 🚀 What I've built

#### 🧬 DataMapper · internship at Dnalytics (2026)
A complete module of **Hercule**, a SaaS platform for optimizing pharmaceutical processes, built on my own from functional analysis to production.
React 19 + TypeScript frontend (~6,900 lines), a 12-endpoint REST API in R Plumber with Keycloak role-based access,
a PostgreSQL schema with integrity triggers, and ~40 test files written test-first.
<sub>Proprietary code, not public.</sub>

#### 🏋️ FFT · training & diet app (actively developed)
🌐 Try it in your browser: [web-fft.up.railway.app](https://web-fft.up.railway.app)  
📱 Install it on Android: [fft.up.railway.app](https://fft.up.railway.app/)  
<sub>Source code is private; happy to walk through it in an interview.</sub>

A working mobile app for workouts, nutrition and progress tracking. It is free to use today, and its architecture is ready for a future premium tier.

**How it was built:** I designed the product, the data model, the architecture and the engineering rules. Most of the code was written by Claude Code under my direction, and nothing ships unless the automated checks pass.

- **Stack:** Expo / React Native, TypeScript in strict mode, Expo Router, TanStack Query, Zustand, i18next, Supabase (Postgres, Auth, Storage, Edge Functions)
- **Local-first:** the free tier keeps all data on the device, in a local store that mirrors the Supabase query API, so the same code runs with or without an account. Active workouts survive going offline.
- **Database:** versioned SQL migrations, Row Level Security on every table (a test fails if one is missing), and health-safety rules enforced both in TypeScript and as database constraints
- **Quality:** 207 Jest tests plus 25 database checks on an embedded Postgres, ESLint, Prettier, and zero `any` in the codebase
- **CI/CD:** GitHub Actions gates every push on lint, typecheck and tests, then ships an over-the-air update or a new APK build (EAS) depending on whether the native code changed
- **Product care:** accessibility settings (text scale, high contrast, reduced motion, one-hand mode), undo on every important action, and health data handled with GDPR in mind

#### 🧩 Smaller side projects
A Discord bot for my friends' server (Python, pytest, GitHub Actions) and a small management app for a cleaning business (React, Node.js, PostgreSQL).

---

### 📫 Let's talk

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Filippo_Faiella-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/filippo-faiella-876310329)
[![Email](https://img.shields.io/badge/Email-filfai1003@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:filfai1003@gmail.com)

<sub>🐧 Linux is user-friendly. It's just picky about who its friends are.</sub>
