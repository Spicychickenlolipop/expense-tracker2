# 💰 Expense Tracker

A full-stack web application to **track income, expenses, and manage personal finances** with authentication, analytics, and Excel import support.

---

## 📌 Overview

This Expense Tracker allows users to **monitor spending, manage transactions, and visualize financial data** in a clean and intuitive interface.

It supports **secure login, file uploads, and real-time analytics**, making it a practical personal finance tool.

---

## ✨ Features

* 🔐 User authentication (JWT + bcrypt)
* ➕ Add & manage income/expenses
* 📊 Real-time balance tracking
* 📉 Analytics with charts (Recharts)
* 🧾 Transaction history
* ❌ Delete transactions
* 📂 Import Excel files
* 😊 Emoji-based categories
* ⚡ Fast & responsive UI

---

## 🖼️ Screenshots

### 🏠 Dashboard

<img width="1599" height="819" alt="Screenshot 2026-04-19 000243" src="https://github.com/user-attachments/assets/89310488-7101-4a6b-842e-6acf51a3648c" />

### ➕ Add Transaction

<img width="1599" height="817" alt="Screenshot 2026-04-19 000408" src="https://github.com/user-attachments/assets/6336a34a-3b47-4496-89c1-0a330795edc8" />

### 📊 Analytics

<img width="1599" height="818" alt="Screenshot 2026-04-19 000427" src="https://github.com/user-attachments/assets/614bb6cd-9aea-4a5c-bd30-d5dce003ac3e" />

---

## 🛠️ Tech Stack

### 🎨 Frontend

* React + Vite
* Tailwind CSS
* Axios
* React Router
* Recharts
* React Hot Toast
* Emoji Picker
* Moment.js

### ⚙️ Backend

* Node.js + Express
* MongoDB + Mongoose
* JWT Authentication
* bcryptjs
* Multer (file upload)
* XLSX (Excel parsing)

---

## 📂 Project Structure

```bash id="0nq2kp"
expense-tracker2/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── server.js
│
├── frontend/expence-tracker/
│   ├── public/
│   ├── src/
│   └── index.html
│
└── README.md
```

---

## ⚙️ Setup

### 1️⃣ Clone

```bash id="3d8k1m"
git clone https://github.com/Spicychickenlolipop/expense-tracker2.git
cd expense-tracker2
```

---

### 2️⃣ Backend Setup

```bash id="7w2pql"
cd backend
npm install
```

Create `.env`:

```env id="2x9cvm"
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key
```

Run:

```bash id="8m4sda"
npm run dev
```

---

### 3️⃣ Frontend Setup

```bash id="5r1nky"
cd frontend/expence-tracker
npm install
npm run dev
```

---

## 🚀 Usage

1. Open `http://localhost:5173`
2. Register / Login
3. Add income & expenses
4. View analytics dashboard

---

## 📊 Excel Import Format

```id="1o8xpk"
Date | Amount | Category | Type (Income/Expense)
```

---

## 🌐 Deployment

* Frontend → Vercel
* Backend → Render
* Database → MongoDB Atlas

---

## 👨‍💻 Author

GitHub: https://github.com/Spicychickenlolipop

---

## ⭐ Support

If you like this project, give it a ⭐
