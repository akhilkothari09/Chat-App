# 💬 WhisprAi-WhatsApp Clone with AI Chatbot Assistant

A full-featured WhatsApp-like chat app built using the MERN stack (MongoDB, Express, React, Node.js) enhanced with cutting-edge AI features powered by OpenAI.

---

## 🚀 Features

### Core Chat Functionality
- 🔐 User Authentication (JWT-based)
- 💬 One-to-one messaging with real-time updates (via WebSocket or polling)
- 📷 Media support (images, voice, attachments)
- 🌙 Dark mode support
- 👤 User presence and typing indicators

### 🤖 AI Features
- ✅ Smart Reply Suggestions
- 🔄 Message Auto-Translation (Coming Soon)
- 🗣️ Voice-to-Text Transcription (Planned)
- 🔊 Text-to-Speech (Planned)

---

## 📂 Project Structure

\`\`\`bash
server/
├── controllers/
│   ├── auth.controller.js
│   ├── message.controller.js
│   └── ai.controller.js    <-- AI logic
├── routes/
│   ├── auth.route.js
│   ├── message.route.js
│   └── ai.route.js         <-- AI endpoint
├── models/
│   ├── User.js
│   └── Message.js
├── utils/
│   └── openai.js           <-- OpenAI setup
└── server.js

client/
├── components/
│   ├── ChatContainer.jsx
│   ├── MessageInput.jsx
│   ├── SmartReply.jsx
│   └── LiveTranscriber.jsx (planned)
├── store/
│   ├── useAuthStore.js
│   └── useChatStore.js
├── App.jsx
└── index.js
\`\`\`

---

## ⚙️ Getting Started

### Prerequisites
- Node.js v18+
- MongoDB
- OpenAI API Key

### Setup

\`\`\`bash
# Clone the repository
git clone https://github.com/AmanKumar2202/Chat-app
cd whatsapp-clone-ai

# Backend
cd backend
npm install
npm run dev

# Frontend
cd ../frontend
npm install
npm run dev
\`\`\`

### 🧠 AI Integration (OpenAI)

1. In the \`server/\` directory, create a \`.env\` file based on \`.env.example\`:
   \`\`\`env
   OPENAI_API_KEY=your_openai_key_here
   \`\`\`
2. Seed the bot user (\`ChatAI\`) into the database manually or via a provided script.

### 💬 How the AI Chatbot Works
- A special user \`ChatAI\` appears in your contact list.
- When a user messages \`ChatAI\`, the client calls the \`/api/ai/respond\` endpoint.
- The server forwards the conversation context to OpenAI GPT-3.5.
- GPT-3.5 returns a human-like reply.
- The reply is saved and displayed just like any regular message.

---

## 📦 Tech Stack
- **Frontend**: React + Tailwind CSS + Zustand
- **Backend**: Node.js + Express
- **Database**: MongoDB + Mongoose
- **AI**: OpenAI GPT-3.5 API
- **Auth**: JWT + bcrypt
- **Others**: Cloudinary, Socket.io 

---

## 📌 Upcoming Features
- 🔄 Auto Message Translation
- 🧠 AI-powered Search & Summarization
- 🛡️ Message Moderation (Toxicity Filter)
- ✅ AI Chatbot Assistant

---
<<<<<<< HEAD
<<<<<<< HEAD
## 🔗 Deployed Link
[https://whisprai-nine.vercel.app](https://whisprai-nine.vercel.app)
=======

>>>>>>> c797755 (Created readme)
=======
   ## 🔗 Deployed Link
   [https://whisprai-nine.vercel.app](https://whisprai-nine.vercel.app)
>>>>>>> 97aa948 (Adding smart Reply feature)
