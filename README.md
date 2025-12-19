# 🛒 BEST — Firebase-Based E-Commerce Web Application

BEST is a **basic yet functional e-commerce web application** built with **React** on the frontend and **Firebase** as the backend. The project demonstrates how a complete shopping experience can be built **without a traditional server**, leveraging Firebase services for authentication and data management.

---

## 🚀 Features

### 👤 Authentication

* User registration and login using Firebase Authentication
* Protected routes for authenticated users
* Persistent login sessions

### 🛍️ E-Commerce Functionality

* Product listing and browsing
* Product filtering and display
* Add to cart functionality
* Cart management
* Orders page

### 🔥 Firebase Integration (Key Differentiator)

* Firebase Authentication for user management
* Firebase configuration handled centrally
* No custom backend or server required

### 🎨 User Interface

* Modular React component structure
* Reusable UI components
* Responsive layout
* Simple and clean design

---

## 🧠 Tech Stack

### 🎨 Frontend

* React
* JavaScript (ES6+)
* CSS

### ☁️ Backend (Firebase)

* Firebase Authentication
* Firebase configuration

---

## 📁 Project Structure

```
best-buy/
├── public/
│   └── index.html
│
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── FilterSidebar/
│   │   ├── Navbar/
│   │   ├── OrderTable/
│   │   ├── Product/
│   │   └── UI/
│   │
│   ├── config/
│   │   └── firebase.js
│   │
│   ├── context/
│   │   ├── Auth/
│   │   │   ├── AuthContext.js
│   │   │   ├── AuthReducer.js
│   │   │   ├── AuthState.js
│   │   │   └── types.js
│   │   │
│   │   └── Products/
│   │       ├── ProductsContext.js
│   │       ├── ProductsReducer.js
│   │       ├── ProductsState.js
│   │       └── types.js
│   │
│   ├── pages/
│   │   ├── HomePage/
│   │   ├── CartPage/
│   │   ├── LoginPage/
│   │   ├── RegisterPage/
│   │   ├── OrdersPage/
│   │   └── NotFoundPage/
│   │
│   ├── utils/
│   │   ├── data.js
│   │   └── utils.js
│   │
│   ├── App.js
│   ├── index.js
│   ├── App.css
│   └── setupTests.js
│
├── package.json
└── README.md
```

---

## ⚙️ Firebase Setup

Create a Firebase project and add your credentials in `src/config/firebase.js`:

```
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```

---

## ▶️ Running Locally

```bash
npm install
npm start
```
---

## 👨‍💻 Author

**Aakarshit Khajuria**
GitHub: [https://github.com/Aakarshit5705](https://github.com/Aakarshit5705)

---

## 📄 License

This project is licensed under the **MIT License**.
