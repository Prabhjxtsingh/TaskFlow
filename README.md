TaskFlow – Monochrome Kanban Dashboard

TaskFlow is a modern, responsive Monochrome Task Management Dashboard built using HTML, Tailwind CSS (CDN), and Vanilla JavaScript.

It features a clean black & white aesthetic with smooth animations, drag-and-drop Kanban functionality, task management, notifications, dark/light theme toggle, and profile settings.

🌟 Features
🔐 Authentication Flow

Animated loading screen

Smooth login transition

Simulated login (no backend required)

📊 Dashboard

Task statistics:

Total Tasks

In Progress

Completed

High Priority

Recent tasks table

Quick action buttons

Fully animated components

📌 Kanban Board

3 Columns:

To Do

In Progress

Done

Drag & drop task movement

Manual move buttons (mobile-friendly)

Task priority indicators

Deadline tracking with overdue highlighting

➕ Task Management (CRUD)

Create tasks

Edit tasks

Delete tasks

Update task status

Priority levels:

Low

Medium

High

Deadline support

Real-time dashboard updates

🔔 Notifications System

Task activity notifications

Unread badge indicator

Mark as read on open

Clear all option

🌙 Dark / Light Mode

Class-based dark mode using Tailwind

Animated icon switch

Smooth theme transitions

⚙ Settings Page

Update name & email

Toggle email notifications

Save confirmation feedback

Sidebar auto-update on save

📱 Responsive Design

Mobile sidebar with overlay

Adaptive layout

Touch-friendly controls

🛠 Tech Stack
Technology	Purpose
HTML5	Structure
Tailwind CSS (CDN)	Styling
Vanilla JavaScript	Logic & State Management
Phosphor Icons	UI Icons
📂 Project Structure

Since this is a single-file application:

TaskFlow/
│
└── index.html

Everything (HTML, CSS, JS) is contained inside index.html.

⚙ How to Run

Download the file

Save as index.html

Open in any modern browser

No installation required.
No backend required.
No build tools required.

🧠 Application Architecture
State Management

tasks[] → Stores all task data

userProfile{} → Stores user settings

notifications[] → Stores notification data

statuses[] → Defines Kanban columns

All updates automatically trigger UI re-rendering via:

renderBoard()

renderDashboard()

renderNotifications()

🎯 Core Functional Modules
1. Authentication Flow
handleLogin()

Transitions from login screen to main application.

2. Theme Toggle
toggleTheme()

Switches between light and dark mode.

3. Routing System
navigate(pageId)

Controls page visibility (Dashboard / Kanban / Settings).

4. Drag & Drop
setupDragAndDrop()
handleDragStart()
handleDragEnd()

Handles Kanban column movement.

5. Task CRUD
handleFormSubmit()
updateTaskStatus()
deleteTask()
6. Modal Controls
openModal()
closeModal()
🎨 Design System

Fully monochrome UI

Black/White contrast-based hierarchy

Soft shadows & hover effects

Rounded components

Minimalistic Kanban styling

Smooth animations (fade-up, scale, transitions)

🔮 Future Improvements

LocalStorage persistence

Backend integration (Node / Django / Firebase)

Authentication system

Task filtering & search logic

Tags and categories

Due date reminders

Multi-user collaboration

Real-time sync

Data export (CSV / JSON)

🧩 Default Demo Credentials

Pre-filled login:

Email: alex@taskflow.inc
Password: password123

(Login is simulated – no validation logic implemented.)

📌 Key Highlights

✔ Modern UI
✔ Fully responsive
✔ Drag & drop Kanban
✔ Animated transitions
✔ Dark mode
✔ Real-time updates
✔ Clean architecture
✔ No dependencies except CDN

👨‍💻 Author

TaskFlow – Monochrome Dashboard
Designed & Built as a Frontend UI Demonstration Project.
