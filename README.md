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
git clone https://github.com/sohila-nabil/market-place.git

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

## ▶️ Run the Application
### Start backend
cd server
npm run start

### Start frontend
cd ../client
npm run dev

## 📷 Screenshots

<img width="1341" height="590" alt="mr6" src="https://github.com/user-attachments/assets/c5224601-74b6-4e9e-903f-2e35fc8e5efc" />
<img width="1332" height="592" alt="mr4" src="https://github.com/user-attachments/assets/1da8eaee-c60d-42b5-b880-bc37c9aa38f7" />
<img width="1311" height="607" alt="mr3" src="https://github.com/user-attachments/assets/5d8bfe7f-9e80-47cd-ad75-cb69cf6313fb" />
<img width="1342" height="616" alt="mr2" src="https://github.com/user-attachments/assets/6c5e76ce-a732-4660-84c9-46859828b617" />
<img width="1351" height="608" alt="mr1" src="https://github.com/user-attachments/assets/6d1cae73-7f05-4b56-95c5-7b9bcdff6282" />
<img width="1321" height="600" alt="mr9" src="https://github.com/user-attachments/assets/7a0b287b-93ad-402c-b557-fca28d083334" />
<img width="1293" height="590" alt="mr8" src="https://github.com/user-attachments/assets/d80dbffd-7d53-4011-b85b-737070891eb7" />
<img width="1352" height="574" alt="mr7" src="https://github.com/user-attachments/assets/3657c2e0-0ca8-4d09-bc05-69e11bf7747a" />
