# 🌿 BeingWell – Health Management App

**BeingWell** is a cross-platform mobile application developed using **React Native**, **Firebase**, and **Android Studio**, designed to support users' mental and physical well-being. This fork reflects academic work completed as part of a group software engineering project at Queen Mary University of London.

> 📦 Built with a modular, user-centric design architecture, the app supports mood journaling, goal setting, activity tracking, and access to mental health ambassadors.

---

## 📲 Features

- 🧘‍♂️ Mood journaling and reflection with optional goal tracking
- 📋 Ticket booking system to connect with health ambassadors
- 🥗 Nutrition logging (Food & Water)
- 💤 Sleep and step tracking with aggregation into a health log
- 🧠 Guided meditation modules
- 📈 BMI calculator and personalised fitness plans
- 🔐 Secure login and encrypted data handling

---

## 🛠️ Tech Stack

- **React Native** (frontend)
- **Firebase** (backend: Realtime Database & Storage)
- **Android Studio** (deployment & emulation)
- **JavaScript (ES6+)**
- **Design Patterns:** Singleton, Adapter, Player-Role

---

## 🧩 System Design Highlights

- **Modular dashboards**: UserDashboard, NutritionDashboard, TrackingDashboard
- **Comprehensive class relationships** with aggregation, composition, and generalisation
- **Role-based inheritance**: Admin, FDM Employee, Health Ambassador
- **Design patterns implemented**:
  - **Singleton** for managing user sessions
  - **Adapter** for integrating step tracking APIs
  - **Player-Role** for flexible role extensions

---

## 🔐 Non-Functional Requirements

| Requirement | Type | Priority |
|------------|------|----------|
| Secure password and data encryption | Security | Core |
| Two-step deletion confirmation | Reliability | Optional |
| iOS & Android support | Platform | Core |
| 5s max loading time | Response Time | Core |
| Data backups and offline syncing | Reliability | Core |
| Anonymised mental health data sharing | Security | Core |

---

## 📦 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/BinulaM/beingWell.git
cd beingWell
```
### 2. Install Dependencies

```bash
npx install expo
npx expo start
```

> 🧑‍🎓 This project was developed as part of a **group Software Engineering module at Queen Mary University of London (2023–2024)**.

> This fork reflects our academic work, including system design, frontend and backend implementation, and applied design patterns. The app supports mood journaling, booking with health ambassadors, activity tracking, and personalised health metrics.
