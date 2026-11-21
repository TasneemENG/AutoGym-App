<p align="center">
  <img src="assets/banner.png" width="100%" alt="AutoGym Banner"/>
</p>

<h1 align="center">💪 AutoGym • AI-Powered Fitness Ecosystem</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter&logoColor=white" alt="Flutter"/>
  <img src="https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white" alt="Dart"/>
  <img src="https://img.shields.io/badge/.NET-9-512BD4?logo=dotnet&logoColor=white" alt=".NET"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" alt="FastAPI"/>
  <img src="https://img.shields.io/badge/MediaPipe-AI-orange" alt="MediaPipe"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker"/>
</p>

<h3 align="center">
Flutter Mobile App • ASP.NET Core Backend • Python AI Service • Real-Time Pose Analysis
</h3>

<p align="center">
  <a href="https://drive.google.com/file/d/15LENsfWVCLiv9Bzb5lojLtSJIEDtZ6VT/view?usp=drivesdk">
    <img src="https://img.shields.io/badge/%E2%96%B6_Watch_the_Demo_Video-FF5722?style=for-the-badge" alt="Watch the Demo Video"/>
  </a>
</p>

---

## 🌟 About the Project

**AutoGym** is a complete **AI-powered fitness ecosystem**, built as a graduation project: a **Flutter mobile app**, an **ASP.NET Core backend**, and a **Python AI service** for real-time pose and exercise analysis.

I worked on AutoGym as a **Flutter Developer**, building the mobile experience from clean architecture and state management to real-time AI feedback in the UI. This repository is a visual showcase of that work.

---

## 🎥 Demo

✨ See AutoGym in action:

- [📱 Watch the Full Demo Video](https://drive.google.com/file/d/15LENsfWVCLiv9Bzb5lojLtSJIEDtZ6VT/view?usp=drivesdk)

---

## 📱 My Work on the Mobile App (Flutter)

As the Flutter developer behind the mobile app, my work included:

- **Feature-first architecture**: one module per product domain, with the repository pattern separating data sources from business logic
- **BLoC state management** across the app with `flutter_bloc`
- **REST integration with Dio**: JWT auth, token refresh, and interceptors
- **Real-time WebSockets**: streaming camera frames to the AI service and rendering live rep counts, form scores, and coaching cues
- **SignalR client**: real-time notifications and social updates without polling
- **Adaptive, responsive UI**: resolution-adaptive layouts across device sizes, shimmer loading states, Syncfusion analytics charts, workout calendars, and rest-timer visualizations
- **Localization**: multi-language support
- **Firebase Authentication**: Google and Facebook social login

---

## ✨ Key Features

### 🤖 AI Features

✅ **AI Personal Trainer & Chatbot**: conversational coaching with Markdown-formatted responses  
✅ **Real-Time Pose Detection**: live form analysis for 13 exercises  
✅ **Exercise Form Analysis**: rep counting, joint angles, 0–100 form scores, and coaching cues  
✅ **Personalized Workout Recommendations**

### 🏋️ Fitness Features

✅ **Workout Tracking**: sessions, quick workouts, history, and a workout calendar  
✅ **Routine Builder**: folders, duplication, shareable routines, and community discovery  
✅ **Exercise Library**: filters by muscle and equipment, personal records per exercise  
✅ **Progress Analytics**: per-muscle volume and strength charts  
✅ **Body Measurements & Achievements**: milestones for consistency and personal records  
✅ **Nutrition & Meal Tracking**: daily logs and meal posts  
✅ **Community**: workout and meal posts, reactions, comments, and a follow system  
✅ **Smart Notifications**: push (FCM) and real-time (SignalR), with per-type preferences

### 🛠️ Engineering Highlights

✅ Clean Architecture on every layer  
✅ RESTful APIs with JWT auth and token versioning  
✅ WebSocket streaming between the app and the AI service  
✅ Dockerized backend with scheduled background jobs

---

## 📸 App Screenshots

| ![](assets/1.jpeg)  | ![](assets/2.jpeg)  | ![](assets/3.jpeg)  | ![](assets/4.jpeg)  |
| :-----------------: | :-----------------: | :-----------------: | :-----------------: |
| ![](assets/5.jpeg)  | ![](assets/6.jpeg)  | ![](assets/7.jpeg)  | ![](assets/8.jpeg)  |
| ![](assets/9.jpeg)  | ![](assets/10.jpeg) | ![](assets/11.jpeg) | ![](assets/12.jpeg) |
| ![](assets/13.jpeg) | ![](assets/14.jpeg) | ![](assets/15.jpeg) | ![](assets/16.jpeg) |
| ![](assets/17.jpeg) | ![](assets/18.jpeg) | ![](assets/19.jpeg) | ![](assets/20.jpeg) |
| ![](assets/21.jpeg) | ![](assets/22.jpeg) | ![](assets/23.jpeg) | ![](assets/24.jpeg) |
| ![](assets/25.jpeg) | ![](assets/26.jpeg) | ![](assets/27.jpeg) | ![](assets/28.jpeg) |
| ![](assets/29.jpeg) | ![](assets/30.jpeg) | ![](assets/31.jpeg) | ![](assets/32.jpeg) |
| ![](assets/33.jpeg) | ![](assets/34.jpeg) | ![](assets/35.jpeg) | ![](assets/36.jpeg) |
| ![](assets/37.jpeg) | ![](assets/38.jpeg) | ![](assets/39.jpeg) | ![](assets/40.jpeg) |
| ![](assets/41.jpeg) | ![](assets/42.jpeg) | ![](assets/43.jpeg) | ![](assets/44.jpeg) |

---

## 🏗️ System Architecture

<p align="center">
  <img src="assets/arch.jpg" width="900" alt="AutoGym System Architecture"/>
</p>

| Layer      | Technology            | Responsibility                                          |
| ---------- | --------------------- | ------------------------------------------------------- |
| Mobile     | Flutter               | UX, workout tracking, analytics, and AI-assisted flows  |
| Backend    | ASP.NET Core (.NET)   | Authentication, business logic, APIs, persistence       |
| AI Service | FastAPI + MediaPipe   | Pose analysis and exercise intelligence                 |

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

## 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/tasneem-khaled-aa7bb9330)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white&style=for-the-badge)](mailto:tasneemshaheen2004@gmail.com)

---

⭐ This repository is for **showcasing the project only (code is private)**.  
If you're interested in collaboration, feel free to connect!
