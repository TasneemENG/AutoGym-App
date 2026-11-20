# 💪 AutoGym — AI-Powered Fitness App

<p align="center">

![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-9-512BD4?logo=dotnet&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-AI-orange)

</p>

<h3 align="center">
AI-Powered Fitness Ecosystem • Flutter • ASP.NET Core • Python • MediaPipe
</h3>

**AutoGym** is a complete **AI-powered fitness ecosystem**, built as a graduation project by a team of five: a **Flutter mobile app**, an **ASP.NET Core backend**, and a **Python AI service** for real-time pose and exercise analysis.

I worked on AutoGym as a **Flutter Developer**, building the mobile experience with my team from clean architecture and state management to real-time AI feedback in the UI.

---

## ✨ Key Features

### 🤖 AI Features

✅ **AI Personal Trainer & Chatbot** — conversational coaching with Markdown-formatted responses  
✅ **Real-Time Pose Detection** — live form analysis for 13 exercises  
✅ **Exercise Form Analysis** — rep counting, joint angles, 0–100 form scores, and coaching cues  
✅ **Personalized Workout Recommendations**

### 🏋️ Fitness Features

✅ **Workout Tracking** — sessions, quick workouts, history, and a workout calendar  
✅ **Routine Builder** — folders, duplication, shareable routines, and community discovery  
✅ **Exercise Library** — filters by muscle and equipment, personal records per exercise  
✅ **Progress Analytics** — per-muscle volume and strength charts  
✅ **Body Measurements & Achievements** — milestones for consistency and personal records  
✅ **Nutrition & Meal Tracking** — daily logs and meal posts  
✅ **Community** — workout and meal posts, reactions, comments, and a follow system  
✅ **Smart Notifications** — push (FCM) and real-time (SignalR), with per-type preferences

### 🛠️ Engineering Highlights

✅ Clean Architecture on every layer  
✅ RESTful APIs with JWT auth and token versioning  
✅ WebSocket streaming between the app and the AI service  
✅ Dockerized backend with scheduled background jobs

---

## 🎥 Demo

✨ Watch the app in action:

- [📱 Watch the Demo Video](https://drive.google.com/file/d/15LENsfWVCLiv9Bzb5lojLtSJIEDtZ6VT/view?usp=drivesdk)

---

## 📱 My Work on the Mobile App (Flutter)

As a Flutter developer on the team, my work on the app included:

- **Feature-first architecture** — one module per product domain, with the repository pattern separating data sources from business logic
- **BLoC state management** across the app with `flutter_bloc`
- **REST integration with Dio** — JWT auth, token refresh, and interceptors
- **Real-time WebSockets** — streaming camera frames to the AI service and rendering live rep counts, form scores, and coaching cues
- **SignalR client** — real-time notifications and social updates without polling
- **Adaptive, responsive UI** — resolution-adaptive layouts across device sizes, shimmer loading states, Syncfusion analytics charts, workout calendars, and rest-timer visualizations
- **Localization** — multi-language support
- **Firebase Authentication** — Google and Facebook social login

---

## 🏗️ System Architecture

| Layer | Technology | Responsibility |
|---|---|---|
| Mobile | Flutter | UX, workout tracking, analytics, and AI-assisted user flows |
| Backend | ASP.NET Core (.NET) | Authentication, business logic, APIs, persistence |
| AI Service | FastAPI + MediaPipe | Pose analysis and exercise intelligence |

---

## 👥 Team

| Member | Role |
|---|---|
| Rania Atef | Team Lead / Flutter Developer |
| **Tasneem Khaled** | **Flutter Developer** |
| Mohamed Abdelghany | Backend Developer & AI Engineer |
| Rana Shehta | Backend Developer |
| Randa Adel | UI/UX Designer |

**Technical Supervisor:** Mohamed Emad

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flutter/flutter-original.svg" height="40" alt="flutter"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dart/dart-original.svg" height="40" alt="dart"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/dotnetcore/dotnetcore-original.svg" height="40" alt="dotnet"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="40" alt="fastapi"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" height="40" alt="firebase"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain.svg" height="40" alt="docker"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="git"/>
</p>

---

## 📬 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/tasneem-khaled-aa7bb9330)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white&style=for-the-badge)](mailto:tasneemshaheen2004@gmail.com)

---

⭐ This repository is for **showcasing the project only (code is private)**.  
If you’re interested in collaboration, feel free to connect!
