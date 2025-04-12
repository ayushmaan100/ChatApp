
💬 Real-Time Chat Application

A full-stack real-time chat application built from scratch using **ReactJS** (Frontend), **Node.js + Express** (Backend), **MongoDB** for database, **Socket.IO** for real-time messaging, and **JWT authentication** for secure login.

---

 🧱 Folder Structure

/frontend   → ReactJS client with Tailwind CSS (or your CSS choice)
/backend    → Node.js + Express API with Socket.IO and MongoDB

---

 🚀 Features

- 🔐 JWT Authentication (Login & Signup)
- 🗨️ Real-Time Messaging (Socket.IO)
- 👥 1-on-1 and Group Chats
- 🔍 User Search & Chat List
- 📬 RESTful API for Users, Chats, and Messages
- ⚡ MongoDB (Mongoose ORM)
- 📦 Clean, modular codebase for easy scaling

---

 🛠️ Tech Stack

Frontend
- ReactJS
- Axios
- React Router
- Tailwind CSS / CSS Modules (optional)

Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.IO
- JWT (JSON Web Token)
- bcrypt.js (password hashing)
- dotenv

---

📦 Installation

⚙️ Backend Setup

```bash
cd backend
npm install

Create a .env file inside backend/:

PORT=5000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret

Start the backend server:

npm run dev



⸻

🎨 Frontend Setup

cd frontend
npm install
npm run dev

The front end will usually run at http://localhost:5173, and the back end will run at http://localhost:5000.

Ensure your frontend API requests point to the backend base URL correctly (set in axios.defaults.baseURL or use a .env in /frontend with VITE_API_BASE_URL).

⸻

📡 API Endpoints

Method	Endpoint	Description
POST	/api/user	Register new user
POST	/api/user/login	Login user
GET	/api/chat	Fetch user chats
POST	/api/chat	Create new chat
POST	/api/message	Send message
GET	/api/message/:id	Fetch messages by chat



⸻

🔐 Authentication
	•	JWT stored securely on frontend
	•	Middleware to protect API routes
	•	Passwords are hashed using bcrypt.js

⸻

🔄 Socket.IO
	•	Users join unique chat rooms based on chat ID
	•	Instant message delivery without page reloads
	•	Handles online/offline presence

⸻

🌍 Deployment Ideas
	•	Frontend: Netlify / Vercel
	•	Backend: Render / Railway / Cyclic
	•	Database: MongoDB Atlas

⸻


👨‍💻 Author

Made with ❤️ by Ayushmaan

⸻

📄 License

Open source under the MIT License.
