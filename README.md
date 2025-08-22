# Prodexa
> **Connect. Collaborate. Compete.**, A modern platform for productivity and community.

<!-- ![Prodexa Cover](docs/cover.png) -->

<p align="center">
  <a href="#key-features">Features</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#security">Security</a> •
  <a href="#team">Team</a> •
  <a href="#roadmap">Roadmap</a> •
  <a href="#demo">Demo</a> •
  <a href="#License">License</a>
</p>


<p align="center">
  <img alt="MERN" src="https://img.shields.io/badge/Stack-MERN-1f6feb"/>
</p>

---

## Overview

Our platform is a **comprehensive hub for collaboration, productivity, and community engagement**. It seamlessly integrates tools for **task management, communication, and knowledge sharing**, enabling users to stay organized and connected.  

Whether used by **individuals**, **teams**, or **communities**, the platform adapts to different needs, from **custom dashboards and smart scheduling** to **interactive chats, social media features, and gamified competitions**. Its modular design ensures scalability, making it suitable for both small groups and large organizations.

By combining productivity, engagement, and collaboration in one environment, the platform reduces tool fragmentation and helps users **focus on achieving results**.


### Why Prodexa?

* One platform for **profiles, dashboards, chat, social, calendar, and competitions**.
* **Clean UX** for casual users; **deep features** for admins and power users.
* **Future‑ready** architecture: modular services, real‑time updates, and strong security.

---

<a id = "key-features"></a>
## 🚀 Key Features 

### 1) Smart User Profiles

* Public profile (bio, skills/tags, activity) and private profile (sensitive settings).
* Role and rank indicators; avatar & cover; privacy controls.

### 2) Role‑Based Dashboards

* Dashboards tuned for **Admins** (analytics, moderation, configuration) and **Users** (progress, tasks, achievements).
* Flexible role system ready for **moderators, mentors, and organization owners**.

### 3) Real‑Time Community Hub

* Group channels & DMs with **media sharing** (images, files, links previews).
* **Reactions, upvotes/downvotes**, message pinning, mentions, and typing indicators.
* Online presence and **WebSocket** updates (Socket.IO planned).

### 4) Integrated Social Layer

* Create posts, comment, react, and **follow** users.
* Rich activity feed with filtering (people you follow, trending, groups).

### 5) Calendar, Events & Deadlines

* Personal and community events with **reminders**.
* Deadlines and recurring events.

### 6) Gamification & Competitions

* **Pop quizzes**, challenges, and ice‑breaker games.
* **Leaderboards** (global, group, friends) and **time‑boxed** rounds.
* Achievements & badges, anti‑cheat basics (randomization, attempt limits).

### 7) Notifications Center

* Real‑time and email notifications for mentions, deadlines, and activity.
* Notification preferences and granular mute settings.

### 8) Accessibility & Internationalization

* Built with accessibility in mind: supports screen readers, keyboard navigation, and clear labels for all users.
* Ready for **multi‑language** UI with RTL support.

### 9) Admin Controls & Analytics

* User management, reports/moderation queue, configurable roles/ranks.
* Usage analytics (engagement, leaderboard stats).

---

<a id = "tech-stack"></a>

## 🧱 Tech Stack

* **Frontend:** React, TypeScript, Tailwind CSS, Redux (state)
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (+ Mongoose)
* **Real‑time:** Socket.IO
* **Auth:** JWT (access/refresh), encryption, OTP email
* **Testing:** TBD
* **Deployment:** TBD

---

<a id = "security"></a>

## 🔐 Security & Privacy

* **Authentication:** short‑lived **access tokens** + rotating **refresh tokens**; secure cookies support.
* **Authorization:** role‑based access control & permission checks in route guards.
* **Input Validation:** central schema validation for **all** endpoints.
* **Headers & Hardening:** CORS rules, rate‑limiting, request size limits.
* **Sensitive Data:** hashed passwords, signed URLs for media.
* **Data Privacy:** clear data retention policy (docs/policies), user‑controlled visibility on profiles.

---

## ♿ Accessibility & UX Principles

* Keyboard‑first navigation, visible focus states, and screen‑reader labels.
* Color‑contrast checked components and scalable typography.
* Motion‑reduced variants for animations.

---

<a id="team"></a>

## 👥 Team

* Ali Said Mohammed
* Emad Adham Mandouh
* Mahmoud Tarek Eid
* Marawan Abdulrahim Sayed
* Mohammed Atef Abdelwahab
---

<a id = "roadmap"></a>

## 🗺️ Roadmap

### Phase 0 - Project Setup (Weeks 1–2)

* Create the GitHub repository and basic project structure.
* Set up frontend tools (React, TailwindCSS, ESLint/Prettier).
* Define commit and naming convention.
* Create wireframes and mockups for the main pages.

---

### Phase 1 - User Profiles & Dashboards (Weeks 3–4)

* Build user profile pages (public and private).
* Add profile pictures/avatars and simple rank levels.
* Create basic user dashboards with placeholder widgets.
* Build an early admin dashboard layout.

---

### Phase 2 - Social Features & Chat UI (Weeks 5–6)

* Create posts and comments UI (frontend only).
* Add reactions (likes, upvotes/downvotes).
* Build trending and sorting options.
* Build chat interface, with typing indicators and file upload buttons.
* start with authentication (sign up, login, logout).

---

### Phase 3 - Calendar & Events (Weeks 7–8)

* Add personal and group event pages.
* Implement reminders and RSVP buttons.
* Create deadline widgets and a weekly overview on dashboards.
* Export events as **.ics files** (so users can import into Google or Outlook calendars).

---

### Phase 4 - Quizzes & Gamification (Weeks 9–10)

* Build a quiz builder (create questions, options, and answers).
* Implement attempts, scoring, and time limits.
* Add leaderboards and achievement badges.
* Add basic anti-cheat measures (like question randomization).

---

### Phase 5 - Final Polish & Launch (Weeks 11–12)

* Improve accessibility (keyboard navigation, color contrast, screen reader support).
* Add multi-language support (English + Arabic, with right-to-left support).
* Write clear documentation and API specifications.
* Test user flows end-to-end.
---

<a id="demo"></a>

## Demo
A live demo will be available soon. Stay tuned!  

---

<a id="License"></a>
## 📄 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.