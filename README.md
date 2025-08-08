# 🌱 HabitHive – Track. Grow. Thrive.

Welcome to **HabitHive** — your personal eco-friendly habit tracker designed to help you make small, consistent changes that have a **big impact** on the planet. From logging green actions to earning badges for your efforts, HabitHive makes building sustainable habits **fun, rewarding, and inspiring**.

---

## 🌍 Why HabitHive?

In a world where our choices shape the future, HabitHive empowers you to **track your habits**, **measure your progress**, and **celebrate your wins**. Whether it's reducing plastic, saving energy, or planting trees, HabitHive keeps you on the path to a greener lifestyle.

---

## 🚀 Features That Make You Buzz

* **🔐 Secure Login & Signup** — Powered by Firebase Authentication.
* **📊 Dashboard Insights** — View progress, streaks, and daily achievements.
* **🏆 Achievement Badges** — Unlock milestones like *Plastic-Free Hero* or *Habit Master*.
* **💡 Easy Habit Tracking** — Add, edit, and monitor your habits.
* **👥 Profile Customization** — Update your details anytime.
* **🌐 Accessible Anywhere** — Fully responsive design for mobile & desktop.

---

## 📂 Project Structure

```
HabitHive_GHT/
│── index.html           # Landing page
│── login.html           # Login page
│── signup.html          # Signup page
│── dashboard.html       # User dashboard
│── tracker.html         # Habit tracker
│── badges.html          # Achievements & badges
│── profile.html         # Profile management
│── app.js               # App navigation logic
│── auth.js              # Authentication logic
│── signup.js            # Signup form handling
│── firebase-config.js   # Firebase configuration
│
├── assets/              # Images & icons
├── css/                 # Stylesheets
├── scripts/             # JS modules (dashboard.js, tracker.js, badges.js)
```

---

## 💡 Tech Stack

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Backend:** Firebase Authentication & Firestore
* **Hosting:** Vercel / Firebase Hosting

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/HabitHive_GHT.git
cd HabitHive_GHT
```

### 2. Set Up Firebase

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a project & enable Authentication + Firestore Database.
3. Replace the config in `firebase-config.js`:

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_PROJECT_ID.firebaseapp.com",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_PROJECT_ID.appspot.com",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

### 3. Run Locally

Open `index.html` in your browser or use a local server like **VS Code Live Server**.

### 4. Deploy to Vercel

* Push your project to GitHub.
* Import the repo into [Vercel](https://vercel.com/) and deploy.

---

## 🌟 How to Use

1. **Sign up** and create your account.
2. **Add green habits** you want to track.
3. **Log daily progress** to maintain streaks.
4. **Earn badges** and share your achievements.

---

## 🛠️ Future Buzz

* Habit reminders & notifications
* Progress analytics & charts
* Global community challenges

---
