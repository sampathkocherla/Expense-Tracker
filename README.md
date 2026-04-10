# 💰 Expense Tracker App (MERN Stack)

A **fully responsive Expense Tracker application** built using the **MERN stack (MongoDB, Express, React, Node.js)**.  
This app helps users securely manage their income and expenses, visualize financial data with interactive charts, and export reports in **Excel format**.

---

## 🚀 Features

### 🔐 User Authentication
- Secure **Sign Up & Login** using **JWT authentication**
- Protected routes to ensure user data privacy

### 📊 Dashboard Overview
- Displays **Total Balance**, **Total Income**, and **Total Expenses**
- Summary cards with real-time updates

### 💵 Income Management
- Add, view, and delete income records
- Track multiple income sources
- Export income data to **Excel**

### 🧾 Expense Management
- Add, view, and delete expenses
- Category-based expense tracking
- Export expense data to **Excel**

### 📈 Interactive Charts
- Visual representation of financial data using:
  - Bar Charts
  - Pie Charts
  - Line Charts
- Helps analyze income and expense trends

### 🕒 Recent Transactions
- Displays the most recent income and expense records
- Quick access to latest activities

### 📥 Reports & Export
- Download complete **income and expense reports** in Excel format
- Useful for budgeting and financial analysis

### 📱 Responsive UI
- Fully responsive design
- Works smoothly on **desktops, tablets, and mobile devices**

### 🧭 Intuitive Navigation
- Sidebar navigation for:
  - Dashboard
  - Income
  - Expenses
  - Logout

### 🗑️ Delete Functionality
- Hover over income/expense cards to reveal delete options
- Simple and user-friendly interaction

---

## 🛠 Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Chart libraries (Bar, Pie, Line)

### Backend
- Node.js
- Express.js
- JWT Authentication

### Database
- MongoDB with Mongoose

### Additional Tools
- Excel export functionality
- RESTful APIs

---
## ⚙️ Installation and Setup

### ✅ Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- MongoDB (Local or MongoDB Atlas)
- Git

---

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/expense-tracker.git
cd expense-tracker
```

### 2️⃣ Backend Setup
```bash
cd backend
npm install
```

Create a .env file inside the server folder:

```.env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=8000
```
Start the backend server:
```bash
npm start
```

Backend runs on:
  http://localhost:5000

### 3️⃣ Frontend Setup

Open a new terminal:
```bash
cd frontend
npm install
npm start
```

Frontend runs on:
  http://localhost:3000

### 4️⃣ Access the Application

Open your browser and visit:

  http://localhost:3000

You can now register, log in, track income & expenses, view charts, and export reports in Excel format.

---

## 🎯 Learning Outcomes

- JWT-based authentication and authorization
- Building scalable **MERN stack applications**
- Managing state and data flow in React
- Data visualization using charts
- Exporting data in Excel format
- Creating responsive and user-friendly UIs

---


## 📜 License

This project is open-source and intended for **learning and educational purposes**.

