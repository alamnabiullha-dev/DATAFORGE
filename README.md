# 🚀 DataForge SaaS Dashboard

DataForge is a modern SaaS-style **admin dashboard** built with HTML, CSS, JavaScript, Firebase, and Chart.js.  
It includes authentication, real-time database, CRUD operations, and a futuristic UI with animations.

---

## ✨ Features

- 🔐 Google Login (Firebase Auth)
- 📊 Real-time Firestore data sync
- ➕ Add / Edit / Delete users (CRUD)
- 📈 Live analytics chart
- 🔍 Search users
- 📥 Export data to CSV
- - 👑 1 Leader + 👥 Up to 3 Members system
- 📩 Email notifications (Leader + Members + Owner)
- 🧠 Auto form validation
- 🎨 Animated futuristic UI (particles, glow, gradient background)
- 🧊 Glassmorphism design
- 📱 Fully responsive (Mobile / iPad / Laptop)
- ⚡ Smooth success screen + auto redirect
- 🔥 Clean modern UI/UX


---

## 🛠 Tech Stack

- HTML5  
- CSS3  
- JavaScript (ES6)  
- Firebase (Auth + Firestore)  
- Chart.js  

---

## 🚀 How to Run

1. Clone repo or download files  
2. Open `index.html` in browser  
3. Or use VS Code Live Server  

---

## 🔥 Firebase Setup

1. Create project in Firebase Console  
2. Enable Authentication → Google Sign-in  
3. Enable Firestore Database  

Add your config:

```js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};

