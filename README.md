# 🏨 Marketplace Project (MERN)

A **MERN stack** marketplace application for browsing, searching, filtering, and managing hotel/place listings with secure authentication, image uploads, and advanced search filters.

---

## 📽️ Demo Video

🔗 **[Watch Demo](https://drive.google.com/file/d/1jE9HdL1V10zz2pWn_ruxvlRysq3p_oTP/view?usp=sharing)**

---

## 📌 Overview

This application allows users to:
- View and search hotel/place listings.
- Filter listings by category, location, or other criteria.
- View detailed pages for each listing with images and descriptions.
- Sign up or log in securely with **JWT**, **Firebase**, and **Google OAuth**.
- Add, edit, and delete listings.
- Store listing images securely using **Cloudinary**.

---

## 🚀 Features

### 🏘️ Website (User)
- **View all listings** with title, image, and key details.
- **Search feature** to find listings quickly.
- **Filter listings** using MongoDB queries (e.g., location, category).
- **Listing detail pages** with full description, images, and amenities.

### 📊 Dashboard (User/Admin)
- **CRUD operations**: Create, Read, Update, Delete listings.
- Upload images using **Cloudinary**.
- Secure authentication with **JWT** and **Firebase/Google OAuth**.
- Manage and organize personal listings.

---

## 🧰 Tech Stack

- **Frontend:** React.js (hooks like useState, useEffect), Redux Toolkit, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Authentication:** JSON Web Token (JWT), Firebase Auth, Google OAuth
- **Image Hosting:** Cloudinary
- **Security:** bcryptjs (password hashing)
- **Database:** MongoDB + Mongoose

---


---

## ⚙️ Environment Variables

Create a `.env` file in the `server/` folder and add:

```env
MONGO_URL =''
PORT =  
JWT_SECRET = ''
CLOUDINARY_API_KEY = ""
CLOUDINARY_API_SECRET =""
CLOUD_NAME = ""
```
## 📦 Installation
# Clone repository
git clone https://github.com/yourusername/marketplace-app.git

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

## ▶️ Run the Application
# Start backend
cd server
npm run start

# Start frontend
cd ../client
npm run dev

