# 🚀 ResolveX – AICTE Integrated Case Management System

**ResolveX** is a centralized web-based case management and monitoring platform designed to streamline institution-related complaint handling across different AICTE bureaus and cells.

The platform helps administrators and officers register institutions, manage complaint cases, track case progress, identify overlapping complaints, and monitor resolution workflows through a unified dashboard.

## 🎯 Problem Statement

Managing institution-related complaints across multiple AICTE bureaus can lead to fragmented information, delayed responses, duplicate complaints, and difficulties in tracking case progress.

ResolveX addresses these challenges by providing a centralized platform for efficient complaint registration, monitoring, coordination, and resolution.

## ✨ Key Features

- 📊 **Interactive Dashboard** – Overview of total, pending, ongoing, and resolved cases.
- 📝 **Case Management** – Create, view, update, and track complaint cases.
- 🏫 **Institution Management** – Register and maintain institution information.
- 🔍 **Overlap Detection & Alerts** – Identify potential overlapping cases.
- 🔄 **Case Status Tracking** – Track Pending, Under Process, Resolved, and Rejected cases.
- ⚡ **Priority Management** – Categorize cases by Low, Medium, and High priority.
- 👨‍💼 **Role-Based Access** – Separate Admin and Officer permissions.
- 📜 **Workflow History** – Maintain case update and activity history.
- 📈 **Reports & Analytics** – Monitor case statistics and performance.
- 🔐 **Secure Authentication** – JWT-based authentication and password hashing.

## 🛠️ Tech Stack

**Frontend**
- React.js
- JavaScript
- HTML5
- CSS3
- Vite

**Backend**
- Node.js
- Express.js
- REST API
- JWT
- Bcrypt.js

**Database**
- MySQL
- SQLite
- SQL

**Tools**
- Visual Studio Code
- Git & GitHub
- npm

## 🏗️ System Architecture

ResolveX follows a client-server architecture:

1. **Frontend:** React.js provides the user interface and dashboard.
2. **Backend:** Node.js and Express.js handle API requests and business logic.
3. **Database:** Stores user, institution, case, and workflow information.
4. **Authentication:** JWT verifies users and protects authorized resources.

## 📂 Project Structure

```text
ResolveX/
├── backend/
│   ├── database/
│   │   ├── schema.sql
│   │   └── seed.sql
│   ├── data/
│   ├── create-admin.js
│   ├── db.js
│   ├── server.js
│   └── package.json
├── public/
├── src/
│   ├── assets/
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
├── run-project.bat
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/ResolveX.git
```

### 2. Navigate to the Project

```bash
cd ResolveX
```

### 3. Install Frontend Dependencies

```bash
npm install
```

### 4. Install Backend Dependencies

```bash
cd backend
npm install
```

### 5. Configure Environment Variables

Create a `.env` file inside the backend folder and configure the required database and authentication settings.

```env
JWT_SECRET=your_secure_secret_key
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_mysql_password
DB_NAME=aicte_casesync
```

Keep your `.env` file private. Never upload credentials to GitHub.

### 6. Start the Backend

From the backend directory:

```bash
npm start
```

### 7. Start the Frontend

Open another terminal in the main project directory:

```bash
npm run dev
```

### 8. Access the Application

Open your browser and visit:

```text
http://localhost:5173
```

## 🗄️ Database Structure

| Table | Purpose |
|---|---|
| users | Admin and officer accounts |
| institutions | Institution details |
| cases | Complaint and case information |
| case_history | Case activity history |
| overlap_reviews | Overlap alert reviews |

## 🔐 User Roles

### Admin
- Manage institution records.
- Create and manage complaint cases.
- Monitor overall case activities.
- Review overlap alerts.
- Access reports and analytics.

### Officer
- View and track complaint cases.
- Update case status and details.
- Monitor assigned case workflows.
- Review institution information.

## 🚀 Future Enhancements

- AI-powered complaint classification.
- Advanced duplicate complaint detection.
- Automated notifications and reminders.
- Enhanced analytical reports.
- Document upload and verification.
- Real-time case updates.
- Advanced cross-bureau collaboration.

## 🎯 Project Objective

To improve transparency, coordination, accountability, and efficiency in handling institution-related complaints through a centralized digital case management system.

## 👨‍💻 Developed For

**Smart India Hackathon (SIH)**

**Project Name:** ResolveX

**Domain:** AICTE – Integrated Complaint Case Management System

---

⭐ If you find this project interesting, consider giving this repository a star!

**ResolveX – Simplifying Case Management, Strengthening Accountability.**
