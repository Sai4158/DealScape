# 🛍️ DealScape

DealScape is a modern full-stack web application that shows trending and affordable products online — mainly from Amazon. It currently loads product data from a local JSON file and displays it in a responsive, easy-to-use design.

## 🚀 What does it do?

- ✅ Lets users **register** and **log in** securely  
- ✅ Displays **top online product deals**
- ✅ Users must be **logged in** to access deals
- ✅ **Logout** works instantly with a success alert
- ✅ Works well on **mobile and desktop** screens
- ✅ Shows helpful **toast notifications** (success, error, etc.)

## 🔧 Tech Stack

### Frontend
- `Next.js` (App Router)
- `React` (v19)
- `Tailwind CSS`
- `React Toastify` (for alerts)
- `Axios` (for API requests)

### Backend
- `MongoDB` (database)
- `Mongoose` (MongoDB object modeling)
- `bcrypt` (password hashing)
- `dotenv` (env config)

### Hosting
- `Vercel` (frontend + API deployment)
- MongoDB Atlas (cloud database)

---

## 🧪 How to Use

1. Register or Log In to access the homepage  
2. Browse product deals (loaded from local JSON file for now)  
3. Click on a deal to view it on Amazon  
4. Log out securely any time

---

## 📦 Upcoming Features

- 🛒 Live **Amazon API** integration (to load real-time deals)
- 🧠 Smart **search and filters**
- 💬 User profiles & saved items
- 📈 Deal tracking & price alerts
- 🌐 Admin dashboard for posting offers

---

## 🧑‍💻 Dev Info

To run locally:

```bash
npm install
npm run dev
