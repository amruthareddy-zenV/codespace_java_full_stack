# 🧠 Managing State with Redux Toolkit and Selectors

This project demonstrates **detailed state management** using **Redux Toolkit**, including:
- Creating and organizing slices
- Using selectors to access state
- Connecting Redux store to React components

---

## ✅ Objectives

- Organize and manage global state with Redux Toolkit
- Use selectors for clean and efficient state access
- Demonstrate separation of concerns and modular Redux logic

---

## 🛠 Tech Stack

- ReactJS
- Redux Toolkit
- React Redux
- Redux Selectors

---

## 📁 Folder Structure

```
redux-toolkit-state/
├── src/
│   ├── app/
│   │   └── store.js
│   ├── features/
│   │   └── user/
│   │       ├── userSlice.js
│   │       ├── userSelectors.js
│   │       └── UserComponent.js
```

---

## 📦 Installation

```bash
npm install @reduxjs/toolkit react-redux
```

---

## 🧱 Step-by-Step Implementation

---

### 🏗️ Create Redux Store (`redux-toolkit-state/src/app/store.js`)

### 👤 User Slice (`redux-toolkit-state/src/features/user/userSlice.js`)

### 📍 User Selectors (`redux-toolkit-state/src/features/user/userSelectors.js`)

### 🧩 User Component (`redux-toolkit-state/src/features/user/UserComponent.jsx`)

### 🔗 Connect Redux Store to App (`src/main.js`)

### 🖼 Use User Component in App (`src/App.jsx`)

---

## 🚀 Run the App

```bash
npm run dev
```

---

## 📚 Key Concepts Covered

- `createSlice()` for modular state management
- `configureStore()` to setup Redux
- `useSelector()` for state access
- **Selectors** for cleaner and reusable logic
- `useDispatch()` for triggering actions

---
