# 📝 ToDo Ts
 
> Task manager built with React and TypeScript — create, edit, and delete tasks with a difficulty level, all in a clean and simple interface.
 
[![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
 
![Project Preview](https://github.com/user-attachments/assets/f566c047-1c47-48ad-8331-f5188c7c52f0)
![Project Preview 2](https://github.com/user-attachments/assets/b0ab3252-b5b8-4642-bcc8-2b2974faa7ac)
 
## 🎯 About

 
A to-do list app built with React and TypeScript. Each task has a title and a numeric difficulty level, and can be created, edited via modal, or deleted. State is managed locally with `useState` — no data persistence, so tasks reset on page reload. Built to practice TypeScript typing in React components and props-based communication between them.
 
## ✨ Features
 
- ✅ **Create tasks** — Add tasks with a title and difficulty level
- ✏️ **Edit tasks** — Update any task through a modal form
- 🗑️ **Delete tasks** — Remove tasks individually
- 🎯 **Difficulty rating** — Assign a numeric difficulty to each task
- 🧩 **Component-based structure** — Organized with reusable React components
 
## 🛠️ Built With
 
- **React 18** — UI and state management via hooks
- **TypeScript** — Static typing for components, props, and interfaces
- **Vite** — Fast dev server and build tool
- **CSS Modules** — Scoped styling per component
 
## 🚀 Getting Started
 
### Prerequisites
 
- Node.js 18+
- npm
 
### Installation
 
```bash
# Clone the repository
git clone https://github.com/Luan-Neumann-Dev/todo-ts.git
 
# Navigate to project directory
cd todo-ts
 
# Install dependencies
npm install
 
# Start the dev server
npm run dev
```
 
Then open your browser at `http://localhost:5173`.
 
Or check the **[live demo →](https://to-do-ts-two.vercel.app/)**
 
## 📁 Project Structure
 
```
src/
├── components/
│   ├── Header.tsx          # App header
│   ├── Footer.tsx          # App footer
│   ├── TaskForm.tsx        # Form for creating and editing tasks
│   ├── TaskList.tsx        # Renders the list of tasks
│   └── Modal.tsx           # Modal wrapper for the edit form
├── interfaces/
│   └── ITask.ts            # TypeScript interface for the Task type
├── App.tsx                 # Root component with main state and logic
└── main.tsx                # Entry point
```
 
## 🎓 What I Learned
 
- Typing React components, props, and state with TypeScript interfaces
- Managing shared state between sibling components via lifting state up
- Controlling UI behavior (modal show/hide) with DOM manipulation alongside React state
- Reusing a single form component for both create and edit flows using optional props
 
## 📝 Notes
 
- This is a **frontend-only** practice project — data is not persisted between sessions
- No external libraries were used for state management or UI components
 
## 📄 License
 
This project is open source and available under the [MIT License](LICENSE).
 
## 👤 Author
 
**Luan Neumann**
 
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luan-neumann-dev/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Luan-Neumann-Dev)
 
---
 
⭐ If you found this project helpful, consider giving it a star!
