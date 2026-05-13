🚀 Todo Dashboard Frontend

Frontend for a full-stack Todo Dashboard application built with React, integrated with a Flask + MySQL backend.

📌 Features
🔐 User Authentication (Login/Register)
📊 Dashboard with real-time task statistics
✅ Task Management (Add, Complete, Delete)
📁 Sidebar Navigation (Dashboard, Tasks, Settings)
⚙️ User Settings (Update profile, logout)
🔄 API integration with backend (Flask)
🛠️ Tech Stack
React.js
React Router DOM
Context API (State Management)
CSS
Backend: Flask (Python)
Database: MySQL
📂 Project Structure
frontend/
│
├── src/
│   ├── Components/
│   │   ├── Dashboard.js
│   │   ├── List.js
│   │   ├── Login.js
│   │   ├── Sidebar.js
│   │   └── Settings.js
│   │
│   ├── context/
│   │   └── TaskContext.js
│   │
│   ├── App.js
│   └── index.js
⚙️ Setup & Installation
1. Clone Repository
git clone https://github.com/sekharchowdary774/todolist
2. Navigate to Frontend
cd todolist/frontend
3. Install Dependencies
npm install
4. Run Application
npm start

App runs on:

http://localhost:3000
🔗 Backend Integration

This frontend connects to a Flask backend running on:

http://localhost:5000

Example API usage:

Login → POST /login
Register → POST /register
Tasks → /tasks
🔐 Authentication Flow
User logs in via /login
Backend returns JWT/session
Token stored in localStorage
Protected routes (Dashboard, Tasks, Settings)
📊 Dashboard Logic

Dashboard dynamically displays:

Total tasks
Completed tasks
Pending tasks

Data is fetched from backend APIs and/or shared via Context API.

⚠️ Current Limitations

Don’t hide this — this is where most candidates lie.

❌ Limited error handling
❌ Basic UI (not production-level)
❌ No global loading states
❌ No token refresh handling
❌ Some data may reset if backend not connected properly
🚧 Future Improvements
Improve UI (Tailwind / Material UI)
Add charts (task analytics)
Add dark mode
Optimize API handling (Axios interceptors)
Add form validation
Improve state management (Redux / Zustand)
