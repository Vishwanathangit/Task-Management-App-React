# ✅ Task Management App

A simple and responsive task manager built with **React**, **Tailwind CSS**, and **Vite**.  
This app allows users to manage tasks with features like adding, editing, deleting, and updating the task status (Pending/Completed). It uses **localStorage** to persist data.

## ✨ Features

- 📌 Add tasks with title, description, due date, and status
- ✏️ Edit task details
- ❌ Delete tasks
- ✅ Mark tasks as "Pending" or "Completed"
- 🔍 Clean and responsive UI using Tailwind CSS
- 💾 Data stored in `localStorage` (no backend required)

## 🗂️ File Structure

<pre>
  ```
  task-management-app/
├── node_modules/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── images/
│   │       ├── icon.png
│   │       └── react.svg
│   ├── pages/
│   │   ├── AddTask.jsx
│   │   ├── EditTask.jsx
│   │   └── Home.jsx
│   ├── App.css
│   ├── App.jsx
│   ├── data.jsx             # Helper for localStorage (getTasks, saveTasks)
│   ├── index.css            # TailwindCSS imported here
│   └── main.jsx             # App entry point
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
├── README.md
└── Task Management App.code-workspace

  ```
</pre>

## 🚀 Getting Started
1. Clone the Repository
git clone https://github.com/your-username/task-management-app.git
cd task-management-app

2. Install Dependencies
npm install

3. Run the App
npm run dev

## 🛠️ Built With
React
Tailwind CSS
Vite
localStorage

## 💡 Future Improvements
Task filters (by date/status)
Search functionality
Dark mode toggle
Backend API integration

GitHub Repo : [https://github.com/Vishwanathangit/Task-Management-App-React.git]
LiveDemo : [https://task-management-app-react-one.vercel.app/]
