# 🍔 FoodInsta

FoodInsta is a MERN stack food video sharing social media platform inspired by Instagram where users can upload, watch, and share food-related videos.

The platform is specially designed for food lovers, restaurants, cafes, chefs, and food bloggers. Restaurants can upload food reels, showcase dishes, promote offers, and attract customers through engaging video content.

---

# 🚀 Features

- 🔐 User Authentication (Login/Register)
- 🎥 Upload Food Videos
- ❤️ Like & Comment System
- 👤 User Profiles
- 🍽️ Restaurant Profiles
- 🔍 Search Users & Restaurants
- 📌 Save Favorite Videos
- 👥 Follow & Following System
- 🌍 Explore Trending Food Reels
- 📱 Responsive UI Design

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Tailwind CSS
- Axios
- React Router DOM

## Backend
- Node.js
- Express.js

## Database
- MongoDB

## Authentication
- JWT Authentication
- bcrypt.js

## Media Storage
- ImageKit

---

# 📂 Folder Structure

```bash
FoodInsta/
│
├── Backend/
│   ├── node_modules/
│   ├── src/
│   │   ├── controllers/
│   │   ├── routes/
│   │   ├── middleware/
│   │   ├── models/
│   │   └── services/
│   │
│   ├── .env
│   ├── package.json
│   ├── package-lock.json
│   └── server.js
│
├── Frontend/
│   ├── my-react-app/
│   │   ├── src/
│   │   ├── public/
│   │   ├── node_modules/
│   │   ├── package.json
│   │   └── package-lock.json
│
├── .gitignore
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/FoodInsta.git
```

---

## Frontend Setup

```bash
cd Frontend/my-react-app
npm install
npm run dev
```

---

## Backend Setup

```bash
cd Backend
npm install
npm start
```

---

# 🔑 Environment Variables

Create a `.env` file inside the Backend folder.

```env
PORT=3000

MONGO_URI=your_mongodb_connection

JWT_SECRET=your_jwt_secret

IMAGEKIT_Public_key=your_public_key
IMAGEKIT_Private_key=your_private_key
IMAGEKIT_URL_endpoint=your_url_endpoint
```

---

# 📸 Main Modules

## User Module
- Register/Login
- Follow & Unfollow Users
- Edit Profile

## Video Module
- Upload Food Videos
- Like & Comment on Videos
- Save Favorite Videos

## Restaurant Module
- Restaurant Profiles
- Upload Dish Videos
- Promote Food Offers

## Explore Module
- Trending Food Reels
- Search Restaurants & Users

---

# 🎯 Future Enhancements

- AI Food Recommendation
- Nearby Restaurant Suggestions
- Live Streaming
- Restaurant Ratings & Reviews
- Food Delivery Integration
- Voice Search

---

# 📌 Project Goal

The main goal of FoodInsta is to build a dedicated social media platform for food-related video content where users can discover restaurants, dishes, and food creators in one place.

---

# 👨‍💻 Author

Harshad Shelar  
final Year Computer Science Engineering Student

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub.
