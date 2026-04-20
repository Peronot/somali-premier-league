# ⚽ Somali Premier League - Football Management Platform

Somali Premier League is a modern web and mobile platform designed to manage, organize, and present Somali football data in a digital, real-time, and user-friendly way.

The goal is to build a unified system that connects competitions, teams, players, administrators, and fans while providing accurate and reliable football information.

## 🚀 Vision

To become the largest and most trusted football platform in Somalia by delivering:

- Live scores
- Match schedules
- League standings
- Detailed football statistics

## 🎯 Objectives

- Register and manage football competitions
- Manage teams and players
- Support real-time match tracking
- Display standings and statistics
- Build a platform that benefits the Somali football community

## 🧩 What This Platform Does

This platform focuses on:

- Competition management for leagues and cups
- Team management and team data organization
- User authentication and access control
- Admin dashboard overview endpoints
- Backend APIs ready to power web and mobile applications
- A React frontend foundation for building the user interface

## ✨ Core Features

### 📊 Competition Management

- Create competitions
- Manage seasons and stages
- Display competition overviews

### 👥 Team and Player Management

- Create and manage teams
- Maintain player profiles
- Organize squad information

### 🏟️ Match Management

- Create matches
- Schedule fixtures
- Build match detail pages

### 🔴 Live Match Center

- Live score updates
- Goal recording
- Assist tracking
- Yellow and red cards
- Substitutions
- Match status such as `Live`, `HT`, and `FT`

### 📈 Standings and Statistics

- Auto-updated league table
- Top scorers
- Player statistics
- Team performance data

### 🔐 Authentication and Roles

- Admin
- Match Operator
- User

## 🛠️ Tech Stack

### 💻 Frontend

- React.js
- Tailwind CSS
- Vite

### ⚙️ Backend

- Node.js
- Express.js

### 🗄️ Database

- MySQL

### 🛡️ Authentication

- JSON Web Tokens (JWT)

## 🗂️ Project Structure

The current project structure is:

```text
somali-premier-league/
|-- frontend/
|   |-- src/
|   |   |-- app/
|   |   |   `-- App.jsx
|   |   |-- assets/
|   |   |-- components/
|   |   |   `-- common/
|   |   |       `-- SectionBadge.jsx
|   |   |-- layouts/
|   |   |   `-- MainLayout.jsx
|   |   |-- pages/
|   |   |   `-- Home.jsx
|   |   |-- services/
|   |   |-- styles/
|   |   |   `-- global.css
|   |   |-- utils/
|   |   `-- main.jsx
|   `-- package.json
|-- backend/
|   |-- database/
|   |   `-- migrations/
|   |-- src/
|   |   |-- config/
|   |   |-- controllers/
|   |   |-- middlewares/
|   |   |-- models/
|   |   |-- routes/
|   |   |-- services/
|   |   |-- utils/
|   |   |-- app.js
|   |   `-- server.js
|   `-- package.json
`-- README.md
```

## 📦 Installation and Setup

### 1. 📥 Clone the Project

```bash
git clone https://github.com/Peronot/somali-premier-league.git
cd somali-premier-league
```

### 2. ⚙️ Backend Setup

```bash
cd backend
npm install
npm run dev
```

### 3. 💻 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

## 🔐 Environment Variables

Create a `.env` file inside the `backend` folder:

```env
PORT=5000
DB_HOST=your_db_host
DB_PORT=3306
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_NAME=your_db_name
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=7d
```

## ▶️ Usage

- Sign in using the authentication system
- Manage teams and team information
- View admin dashboard overview data
- Connect the frontend and backend for full platform development
- Extend the system with live match tracking and standings

## 🧪 Testing

The project does not yet include a full automated test suite. The backend currently includes this script:

```bash
cd backend
npm test
```

## 🔮 Future Improvements

- Complete live match center
- Full player management
- Auto-updating standings and statistics
- News and media center
- Mobile application
- Live notifications
- Advanced analytics such as xG, speed, and distance

## 🌍 Target Audience

- Somali football fans
- Teams and players
- Sports journalists
- Data and statistics enthusiasts

## ⚠️ Challenges

- Collecting accurate real-time football data
- Managing live updates efficiently
- Maintaining data consistency and accuracy

## 💡 Unique Value

Somali Premier League is not just a website. It is a connected football system that brings together:

- Football management
- Live data
- Fan community

The platform is designed to help Somalia build a modern football ecosystem tailored to the local game.

## 👥 Authors

- Ruwaydo Abdiqadir Adan - Full Stack Developer
- Abdiaziiz Mohamed Ali - Full Stack Developer
- Abukar Xasan Cumar - Full Stack Developer
- Farhio mohamud yonis - Full Stack Developer

## 📄 License

This project is open-source and available under the MIT License.

## ⭐ Final Note

This system can help Somalia build a modern football platform similar to FotMob or SofaScore, but designed specifically for the Somali football ecosystem.
