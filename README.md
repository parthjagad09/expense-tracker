# Expense Tracker

# Developer: Parth Jagad

# Overview

ExpenseTracker is a simple and efficient expense tracking application that helps users manage their finances with ease. It allows you to record expenses and incomes, view summaries, delete entries, and even download detailed reports.


# Features

*  Add expenses with amount, category, and date
*  Add incomes with amount, source, and date
*  Delete existing expenses or incomes
*  Download expense or income reports
*  View spending summaries by category or date range
*  Simple and user-friendly interface


# Tech Stack

* Frontend: React.js, Tailwind CSS, React Icons, Vite
* Backend: Node.js, Express.js (MVC Architecture)
* Database: MongoDB


# Installation & Setup

# Clone the Repository

```bash
git clone git@github.com:parthjagad09/expense-tracker.git
```

### 2️⃣ Setup Frontend

```bash
cd expense-tracker/frontend/expense-tracker
npm install
npm run dev
```

# Setup Backend

```bash
cd expense-tracker/backend
npm install
```

# Configure Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=8000
MONGO_URI=your_atlas_url
JWT_SECRET=your_jwt_key
CLIENT_URL=http://localhost:5173
```

# Run the Backend

```bash
npm run dev
```

# Usage

Open your browser and go to: 'http://localhost:5173/' 

* Add your incomes and expenses
* Manage, delete, and download your records


