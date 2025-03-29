# Synco (PROTOTYPE)

🚀 **Synco** – A Real-Time Collaborative Coding Platform

## 📌 Project Overview
Synco is a web-based platform that enables developers to **write, edit, and debug code in real time** with others. Think of it as **Google Docs for coding**, allowing multiple users to collaborate on a single code file seamlessly.

## 🎯 MVP (Initial Phase) Features
- **Real-Time Code Editing** – Multiple users can edit the same document simultaneously.
- **WebSockets for Live Updates** – Changes are instantly synced across all connected users.
- **Code Editor** – A rich code editor with syntax highlighting (powered by Monaco or CodeMirror).
- **Lightweight & Scalable** – Built with a modular architecture to support future expansion.

## 🛠️ Tech Stack
### **Frontend:**
- **React** (or Preact for a lightweight alternative)
- **CodeMirror/Monaco Editor** (for the code editing interface)
- **TailwindCSS** (for styling)
- **Socket.IO (Client-side)** (for real-time collaboration)

### **Backend:**
- **Node.js + Express** (handles WebSocket connections and session management)
- **Socket.IO (Server-side)** (real-time communication layer)
- **Redis (Optional for Scaling)** (for managing active sessions in later phases)

## 🚀 Getting Started
### **Prerequisites**
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### **Installation & Setup**
```sh
# Clone the repository
git clone https://github.com/yourusername/synco.git
cd synco

# Install dependencies
npm install  # or yarn install
```

### **Running the Development Server**
#### Backend
```sh
cd backend
npm start  # or yarn start
```
#### Frontend
```sh
cd frontend
npm start  # or yarn start
```

The app should now be running at `http://localhost:3000/`.

## 🔮 Future Enhancements
- **User Authentication & Project Storage** (Phase 2)
- **Code Execution Support** (Phase 3)
- **Version Control & AI-Powered Features** (Phase 4)

## 📜 License
GNU General Public License v3.0

---

🎉 **Join us in building Synco!** Contributions, feedback, and suggestions are welcome.
