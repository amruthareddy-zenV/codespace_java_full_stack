# ⚛️ Single Page Application (SPA) with React Router & State Management

This hands-on project demonstrates how to build a **Single Page Application (SPA)** using **React Router** for routing and **React Hooks** for state management. It includes **dynamic routing**, **shared global state with Context API**, and **component-based navigation**.

---

## ✅ Features

- Client-side routing with `react-router-dom`
- Page components: Home, About, Product List, Product Details
- Shared state management using `useContext`
- Data fetching simulation using `useEffect`
- Dynamic routing via URL parameters

---

## 🛠 Tech Stack

- ReactJS
- React Hooks: `useState`, `useEffect`, `useContext`
- React Router DOM (v6)

---

## 📁 Folder Structure

```
spa-react-router-state/
├── components/
│   ├── Navbar.js
│   ├── ProductList.js
│   └── ProductDetail.js
├── context/
│   └── ProductContext.js
├── pages/
│   ├── Home.js
│   └── About.js
└── README.md
```

---

## 📦 Installation

```bash
npm install react-router-dom
```

---

## 🔄 Context API Setup: `context/ProductContext.jsx`

## 🧭 App Setup: `App.jsx`

## 🔗 Navbar: `components/Navbar.jsx`

## 🏠 Home Page: `pages/Home.jsx`

## ℹ️ About Page: `pages/About.jsx`

## 🛍️ Product List: `components/ProductList.jsx`

## 📄 Product Detail: `components/ProductDetail.jsx`

---

## 🚀 Run the App

```bash
npm run dev
```

Navigate to:
- `/` – Home
- `/about` – About
- `/products` – Product list
- `/products/1` – View individual product

---

## 📚 Concepts Covered

- React Router (v6)
- Dynamic routes using `:id`
- Programmatic navigation with `useNavigate`
- Shared state with `useContext`
- Data fetching simulation with `useEffect`

---
