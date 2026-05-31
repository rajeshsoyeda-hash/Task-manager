# ✅ TaskFlow — Task Management Application

A modern, full-stack task management web app with user authentication, CRUD operations, Kanban board, and real-time updates.

🔗 **Live Site:** [rajeshsoyeda-hash.github.io/taskmanager](https://rajeshsoyeda-hash.github.io/taskmanager/)  
🐙 **GitHub:** [github.com/rajeshsoyeda-hash/taskmanager](https://github.com/rajeshsoyeda-hash/taskmanager)

---

## ✨ Key Features

| Feature | Details |
|---|---|
| 🔐 Authentication | Register / Login with session management (JWT-style) |
| 📋 CRUD Operations | Create, Read, Update, Delete tasks |
| 📊 Kanban Board | Drag-style columns: To Do → In Progress → Review → Done |
| 🔴 Real-time Updates | Live sync simulation (WebSocket-ready architecture) |
| 📱 Responsive Design | Works on mobile, tablet, and desktop |
| 🔍 Search & Filter | Search by title, filter by priority & category |
| 📈 Analytics Dashboard | Progress tracking with live stats |
| 🗄️ Database | localStorage-based persistent storage (JSON DB) |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript (ES6+) |
| Authentication | Session-based auth with localStorage |
| Database | localStorage (JSON — replaceable with MongoDB/MySQL) |
| Real-time | Polling-based (upgradeable to WebSocket/Socket.io) |
| Deployment | GitHub Pages / Vercel / Netlify |

---

## 🚀 Run Locally

```bash
# Clone the repository
git clone https://github.com/rajeshsoyeda-hash/taskmanager.git

# Navigate into the folder
cd taskmanager

# Open in browser
open index.html
# OR just double-click index.html
```

---

## 🔐 Demo Login

```
Email:    demo@taskflow.app
Password: demo123
```

Or register a new account directly from the app.

---

## 📂 Project Structure

```
taskmanager/
├── index.html          # Full application (HTML + CSS + JS)
└── README.md           # Project documentation
```

---

## 🔌 API Architecture (Backend-Ready)

This project is structured to easily plug in a real backend:

```
Auth Routes:
  POST /api/auth/register   → Create new user
  POST /api/auth/login      → Login, return JWT token
  POST /api/auth/logout     → Clear session

Task Routes (Protected):
  GET    /api/tasks         → Get all user tasks
  POST   /api/tasks         → Create new task
  PUT    /api/tasks/:id     → Update task
  DELETE /api/tasks/:id     → Delete task
  PATCH  /api/tasks/:id     → Toggle done status
```

---

## 📊 Features In Detail

### 🔐 User Authentication & Authorization
- Register with name, email, password
- Login with session persistence
- Protected routes (tasks only visible after login)
- Logout clears session

### 📋 CRUD Operations
- **Create**: Add tasks with title, description, category, priority, due date
- **Read**: View all tasks in List or Kanban view
- **Update**: Edit any task details inline
- **Delete**: Remove tasks with confirmation

### ⚡ Real-time Updates
- Auto-refresh every 30 seconds
- Live stats counter (total, in-progress, done, overdue)
- Toast notifications for all actions

### 📱 Responsive Design
- Mobile hamburger sidebar
- Adaptive grid layout
- Touch-friendly buttons

---

## 🎨 Screenshots

| Login Screen | Dashboard | Kanban Board |
|---|---|---|
| Dark themed auth | Stats + task list | 4-column Kanban |

---

## 📬 Contact

- 🐙 GitHub: [github.com/rajeshsoyeda-hash](https://github.com/rajeshsoyeda-hash)
- 📧 Email: your.email@gmail.com

---

⭐ **Star this repo** if you found it helpful!
