# 💸 Expense Tracker — Frontend

A single-page frontend for the Multi-Currency Expense Tracker. Built with vanilla HTML, CSS, and JavaScript — no frameworks, no build tools.

---

## 🌐 Live URL

```
https://expense-tracker-frontend-wbpa.onrender.com
```

---

## ✨ Features

- **Dashboard** — monthly spending overview with stats cards and AI-powered insights
- **Spending Trend Chart** — interactive line chart showing last 3, 6, or 12 months of spending
- **Expense Logging** — add expenses in any of 31 currencies with automatic USD conversion
- **CSV Export** — download monthly expenses as a CSV file
- **Receipt Upload** — attach images to expenses via Cloudinary, view and remove receipts
- **Budget Tracking** — set monthly per-category budgets with visual progress bars and over-budget alerts
- **AI Monthly Report** — Llama 3 powered financial insights, cached for instant repeat views
- **Group Expenses** — create groups, add members, split bills equally, by percentage, or exact amounts
- **2FA Security** — enable/disable TOTP two-factor authentication via Google Authenticator
- **Dark & Light Mode** — toggle between themes
- **Session Expiry** — auto-logout on expired JWT token with notification
- **Password Strength Meter** — real-time validation during registration

---

## 🛠 Tech

- Vanilla HTML5, CSS3, JavaScript (ES6+)
- Chart.js — spending trend line chart
- No frameworks, no build step, no dependencies to install

---

## 🚀 Running Locally

```bash
# Clone the repo
git clone https://github.com/aleyakewseedin-web/expense-tracker-frontend.git
cd expense-tracker-frontend

# Serve with Python
python -m http.server 5500
```

Open `http://localhost:5500` in your browser.

> **Note:** Make sure the backend is also running at `http://localhost:8000`. See the backend repo for setup instructions.

---

## 🔗 Backend

The frontend connects to the FastAPI backend:

| Environment | URL |
|---|---|
| Production | https://expense-tracker-backend-zskj.onrender.com |
| Local | http://localhost:8000 |

Backend repository: https://github.com/aleyakewseedin-web/expense-tracker-backend

---

## 📁 Structure

```
expense-tracker-frontend/
└── index.html    # Single-page application — all HTML, CSS, and JS in one file
```

---

## 👤 Author

**Aleya Kewseedin**  
GitHub: [@aleyakewseedin-web](https://github.com/aleyakewseedin-web)
