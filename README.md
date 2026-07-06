# Expense Tracker (MERN Stack)

A modern full-stack expense management application built with the MERN stack. The project helps users organize their financial records by managing income and expenses, monitoring balances, and analyzing spending patterns through interactive visualizations.

---

## Overview

Expense Tracker is designed to simplify personal finance management. Users can securely create an account, record transactions, categorize expenses, and gain insights into their financial activity using charts and summaries.

The application follows a client-server architecture with a React frontend, Express backend, MongoDB database, and JWT-based authentication.

---

# Features

### Authentication
- User registration and login
- JWT-based authentication
- Protected application routes

### Financial Management
- Create income records
- Create expense records
- Delete existing transactions
- Track available balance

### Dashboard
- Total Balance overview
- Income summary
- Expense summary
- Recent transaction history

### Data Visualization
- Bar charts
- Pie charts
- Line charts
- Category-wise expense analysis

### Export Support
- Export income records to Excel
- Export expense records to Excel

### User Experience
- Responsive interface
- Simple navigation
- Clean dashboard layout

---

# Technology Stack

## Frontend
- React
- Vite
- Tailwind CSS
- Redux Toolkit

## Backend
- Node.js
- Express.js

## Database
- MongoDB
- Mongoose

## Authentication
- JSON Web Token (JWT)

## Development Tools
- Postman
- Git

---

# Project Structure

```text
Expense-Tracker-MERN
│
├── backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   └── uploads
│
└── frontend
    ├── public
    └── src
        ├── assets
        ├── components
        ├── context
        ├── hooks
        ├── pages
        └── utils
```

---

# Getting Started

## Requirements

Before running the project, make sure you have installed:

- Node.js
- npm
- Git
- MongoDB (or MongoDB Atlas)

---

## Clone the Repository

```bash
git clone git clone https://github.com/vaibhav-singal/Personal-Finance-Management.git

```

---

## Environment Variables

Inside the **backend** folder, create a `.env` file.

```env
PORT=8000
MONGO_URI=YOUR_MONGODB_URI
JWT_SECRET=YOUR_SECRET_KEY
```

---

## Install Dependencies

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## Run the Application

After starting both servers, open your browser and visit:

```
http://localhost:5174
```

---

# Application Modules

### Dashboard
Displays financial summaries, recent transactions, and analytics.

### Income
Manage all income entries and export records.

### Expenses
Maintain expense records with category-based tracking.

### Charts
Visual representation of financial activity for better analysis.

### Authentication
Secure access using JWT tokens.

---

# Highlights

- Full-stack MERN application
- Secure user authentication
- Interactive analytics dashboard
- Excel export functionality
- Responsive design
- RESTful API architecture
- Organized project structure

---

# Future Improvements

Potential enhancements include:

- Transaction editing
- Dark mode
- Budget planning
- Monthly reports
- Notification system
- Multi-currency support

---

# Contributing

Contributions are welcome.

If you would like to improve the project:

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

# License

This project is intended for educational and learning purposes.