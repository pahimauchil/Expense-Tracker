# Expense Tracker App

A full-stack expense tracking application built using MongoDB, Express, React, and Node.js. It includes user authentication, income and expense tracking, chart visualizations, and Excel data export.

## 🔧 Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Auth**: JWT (JSON Web Tokens)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <repo-url>
cd <project-folder>
```
🖥️ Frontend Setup
```bash
cd frontend
npm install
npm start
```
This runs the React app on:
http://localhost:3000

🔙 Backend Setup
```bash
cd backend
npm install
```
Create a .env file in the backend folder with the following content:

env
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```
Then run the backend:

```bash
npm run dev
This starts the server on:
http://localhost:5000
