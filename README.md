TalkTown 💬 | Realtime Chat App using MERN Stack

TalkTown is a real-time chat application where friends and strangers can connect instantly. Built using the MERN Stack with Socket.io, it enables live messaging with a sleek and responsive design using TailwindCSS and DaisyUI.

----------------------------
✨ Features:
- Authentication & Authorization with JWT
- Real-time messaging using Socket.io
- Online user status
- Profile update, logout, and settings
- Global state management with Zustand
- Client & server-side error handling
- Clean UI using TailwindCSS + DaisyUI
- Fully deployed frontend and backend

----------------------------
🛠 Tech Stack:
Frontend: React.js, Zustand, TailwindCSS, DaisyUI  
Backend: Node.js, Express.js, MongoDB, Socket.io, JWT  
Database: MongoDB Atlas  
Deployment: Vercel (frontend), Render/Railway (backend)

----------------------------
📦 Getting Started:

1. Clone the repository:
   git clone https://github.com/mayankgaur0405/TalkTown.git

2. Backend Setup:
   cd backend
   npm install
   # Create .env file (based on .env.example)
   npm run dev

3. Frontend Setup:
   cd ../frontend
   npm install
   npm run dev

----------------------------
🔐 Backend .env Example:
PORT=5000  
MONGO_URI=your_mongodb_uri  
JWT_SECRET=your_jwt_secret  
CLIENT_URL=http://localhost:5173  

----------------------------
📡 Socket Events:
- connect / disconnect
- sendMessage / receiveMessage
- getOnlineUsers
- setOnline

----------------------------
 📸Images:

 <img width="958" height="473" alt="talktown5" src="https://github.com/user-attachments/assets/60295367-48e2-412a-940f-dd6d1b752058" />



----------------------------

----------------------------
🚀 Deployment:
Deployed on Render (backend) and Vercel (frontend)  
Supports free hosting, SSL, and custom domains

----------------------------
🧠 Folder Structure:
- frontend/ : React app with Zustand and TailwindCSS
- backend/ : Express API with JWT, MongoDB, and Socket.io

----------------------------
🤝 Contributing:
Contributions are welcome!  
Fork the repo and open a pull request.

----------------------------
⭐ Support:
If you found this project helpful, give it a ⭐ on GitHub!

----------------------------
Made with ❤️ by Mayank Gaur

Live Demo: https://talktown-8lif.onrender.com/
