Overview

The Team Task Manager System is a full-stack web application designed to help teams manage tasks efficiently.
It allows users to create, assign, update, and track tasks in a simple and organized way.

This project improves productivity, collaboration, and task tracking within teams.

🚀 Features
👤 User Login & Authentication
📝 Create new tasks
👥 Assign tasks to team members
📊 Track task status (Pending / In Progress / Completed)
✏️ Update task details
❌ Delete completed tasks
📋 View all tasks in dashboard
🛠️ Tech Stack

Frontend:

HTML
CSS
JavaScript

Backend:

Node.js
Express.js

Database:

MongoDB
📁 Project Structure
team-task-manager/
│
├── backend/
│   ├── server.js
│   ├── models/
│   ├── routes/
│   └── node_modules/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
└── README.md
⚙️ Installation & Setup
1. Clone repository
git clone https://github.com/your-username/team-task-manager.git
2. Go to project folder
cd team-task-manager
3. Install dependencies
cd backend
npm install
4. Start server
node server.js

OR

npm start
🌐 Run Project

Open browser and go to:

http://localhost:5000
📸 Demo Flow
Login / Register
Create Task
Assign Task
Update Status
Delete Task
🔌 API Endpoints
Method	Endpoint	Description
POST	/api/tasks	Create task
GET	/api/tasks	Get all tasks
PUT	/api/tasks/:id	Update task
DELETE	/api/tasks/:id	Delete task
🎯 Future Improvements
🔔 Notifications
👥 Role-based access (Admin/User)
📅 Task deadlines
📊 Kanban board UI
📱 Mobile app version
