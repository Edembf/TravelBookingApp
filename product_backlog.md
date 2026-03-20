# 🧘 Meditation App - Full Product Backlog

This backlog contains all the User Stories from Exercise 2 to Exercise 10, prioritized by functional areas.

---

## 🔐 1. Authentication & Security (Ex 2, 8 & 9)

| ID | Title | Description | Priority |
|:---|:---|:---|:---|
| #1 | User Registration | Register with username, email, and password. | High |
| #2 | User Login | Access account via email and password. | High |
| #3 | Error Handling | Receive alerts for empty fields or invalid credentials. | High |
| #4 | Auth Persistence | Stay logged in across sessions using LocalStorage. | Medium |
| #5 | Secure Logout | Clear session data and redirect to login page. | High |
| #6 | Account Update | Update email and password in Settings. | Medium |

---

## 🏠 2. Homepage & Navigation (Ex 3 & 4)

| ID | Title | Description | Priority |
|:---|:---|:---|:---|
| #7 | Personalized Greeting | Display "Hello [Name]" and a welcoming title. | Medium |
| #8 | Data Overview | Show daily progress (steps, calories, or minutes) at a glance. | High |
| #9 | Onboarding Guide | Quick introduction carousel for new users. | Low |
| #10| Quick Access | Direct shortcuts to Favorites, Reports, and Settings. | High |

---

## 🧘 3. Exercise Details & Interactions (Ex 5 & 7)

| ID | Title | Description | Priority |
|:---|:---|:---|:---|
| #11| Detailed Info | Display banner, benefits (About), and instructions. | Medium |
| #12| Interactive Actions | Add to Favorites or Share directly from the detail page. | High |
| #13| Related Content | Suggest similar exercises based on the current category. | Low |
| #14| External APIs | Show real-time weather or maps for outdoor sessions. | Low |

---

## ❤️ 4. Favorites & Personalization (Ex 5, 6 & 9)

| ID | Title | Description | Priority |
|:---|:---|:---|:---|
| #15| Favorites Toggle | Heart icon logic (Add/Remove) with UI updates. | High |
| #16| Favorites Screen | Central list to manage all saved meditation items. | Medium |
| #17| Dark Mode | Toggle Light/Dark theme with instant CSS updates. | Low |
| #18| Persistent Prefs | Remember theme and language settings across sessions. | Medium |

---

## ⚙️ 5. Settings & Admin Controls (Ex 8 & 9)

| ID | Title | Description | Priority |
|:---|:---|:---|:---|
| #19| Settings Access | Gear icon available on all screens for quick navigation. | High |
| #20| Categorized Menu | Group settings into Profile, Notifications, and Privacy. | Medium |
| #21| Admin Toggles | Restricted access to sensitive settings controlled by admin. | High |

---

## 🔔 6. Notifications & Engagement (Ex 10)

| ID | Title | Description | Priority |
|:---|:---|:---|:---|
| #22| Daily Reminders | Automatic 9:00 AM alerts to complete daily habits. | High |
| #23| Feature Updates | Notify users about new meditation modules or updates. | Low |
| #24| Notification Opt-out| Toggle promotional alerts vs essential reminders. | Medium |
| #25| Targeted Blasts | Admin tool to message specific user segments. | Medium |

---

## 🛠️ Technical Stack Checklist
- [ ] **Frontend**: HTML5, CSS3 (Variables for Themes), JS (ES6).
- [ ] **Storage**: LocalStorage API for all persistence stories.
- [ ] **APIs**: OpenWeatherMap / Google Maps / Web Share API.
- [ ] **Navigation**: Single Page Application (SPA) logic or structured routing.
