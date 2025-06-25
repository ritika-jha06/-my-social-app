# 📸 My Social Media App
A full-stack MERN social platform where users can register, upload photo posts, like and comment — all wrapped in a sleek, animated glassmorphism UI.

## Built with:

🖥️ React + Context API

🌐 Node.js + Express

🧠 MongoDB + Mongoose

🔐 JWT Authentication

🌈 Fully responsive, with attractive login/register/create post UI, animated gradients, and clean UX.

🚀 Features
🔐 Register & Login with JWT authentication

📸 Create and delete posts with image upload

❤️ Like & 💬 Comment on posts

👤 Personalized feed

🧊 Glassmorphism UI with dynamic gradients

🎨 Styled with custom CSS, animations, and Google Fonts

🔄 Fully responsive & mobile friendly

## 🧑‍💻 Technologies Used
Frontend:

React.js with Context API

Axios for API calls

React Router DOM

Netlify (for deployment)

Google Fonts + Unsplash Backgrounds

Custom CSS with animations (no frameworks!)

Backend:

Node.js + Express.js

MongoDB + Mongoose

Multer (image upload)

JWT (authentication)

Bcrypt (password hashing)

CORS, dotenv, etc.

## 🖼️ Screenshots
Login Page	Home Feed	Create Post

📸 Place your screenshots in a folder named /screenshots in the root of the repo.

## 🔧 Folder Structure
my-social-app/
├── backend/ (Node + Express)
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ └── server.js
├── frontend/ (React app)
│ ├── src/
│ │ ├── pages/
│ │ ├── components/
│ │ └── context/AuthContext.js
│ └── public/
├── .gitignore
├── README.md
└── package.json

## 📦 Installation & Setup
Clone the repo:

git clone https://github.com/yourusername/my-social-app.git
cd my-social-app

### Backend Setup:

cd backend
npm install
Create a .env file:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_jwt_secret

Start server:

npm start

### Frontend Setup:

cd ../frontend
npm install
npm start

## 🌐 Deployment
Frontend: Netlify

Build command: npm run build

Publish directory: /build

Backend: Render / Railway / Vercel (API)

Make sure to allow CORS and connect frontend URL to your backend.

## 🔐 Environment Variables
For backend:

.env

PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret_key

## ✨ Live Demo
🔗 Frontend: https://yourprojectname.netlify.app
🔗 Backend: https://your-api.render.com

## 🙋‍♀️ Author
Made with 💙 by Ritika Jha

🔗 GitHub: @ritika-jha06

📫 Email: ritikajha06@gmail.com
