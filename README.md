# 🧠 ApnaGPT – A ChatGPT Clone using MERN Stack

ApnaGPT is a simple ChatGPT-like AI chatbot built using the MERN stack (MongoDB, Express, React, Node.js) and OpenAI API. Users can send messages and receive real-time AI responses with typing animation.

---

## 🚀 Features

- 💬 Chat with AI using OpenAI GPT API
- 🧵 Multi-threaded chat (create & switch between conversations)
- ⌨️ Typing animation effect for real-time feel
- ⚛️ React frontend with Context API for state
- 📡 Express.js backend with OpenAI integration
- 💾 MongoDB database for storing conversations

---

## 📁 Project Structure

ApnaGPT/
├── Frontend/ # React app
├── Backend/ # Node.js + Express server
└── README.md


## 🧑‍💻 How to Run the Project Locally

### 📦 1. Clone the Repository

bash
git clone https://github.com/manish-kumar0/ApnaGPT.git
cd ApnaGPT   


Install Backend Dependencies


cd Backend

npm install

MONGODB_URI=your_mongodb_connection_string
OPENAI_API_KEY=your_openai_api_key


Start the backend server

nodemon server.js

Install Frontend Dependencies


cd ../Frontend

npm install

npm run dev


URLs

Frontend: http://localhost:5173

Backend API: http://localhost:8080/api

