

# 💬 **Real-Time Chat App (MERN + Socket.IO)**

A **real-time chat application** built using the **MERN stack** (MongoDB, Express.js, React, Node.js) with **Socket.IO** for instant messaging. Users can join chat rooms, send/receive messages in real-time, and enjoy a smooth, responsive chat experience.

---

## ✅ **Features**

* ⚡ **Real-time messaging** using **WebSockets (Socket.IO)**
* 👥 **One-to-one & Group chat support**
* 🔔 **Instant message notifications**
* 🖼 **Profile picture & username support** (optional)
* 📱 **Responsive UI** built with React
* 💾 **Persistent chat history** stored in MongoDB
* 🔐 **User authentication (JWT)** *(if implemented)*

---

## 🛠 **Tech Stack**

### **Frontend**

* **React.js** – UI
* **Socket.IO Client** – for WebSocket communication
* **Axios** – for API requests
* **Tailwind ** – (choose whichever you used)

### **Backend**

* **Node.js & Express.js** – server
* **Socket.IO** – real-time bidirectional communication
* **MongoDB + Mongoose** – chat & user data storage
* **JWT ** – authentication

---

## 🚀 **Installation & Setup**

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/mern-chat-app.git
cd mern-chat-app
```

### **2. Install Dependencies**

#### **Backend**

```bash
cd server
npm install
```

#### **Frontend**

```bash
cd client
npm install
```

---

### **3. Configure Environment Variables**

Create a `.env` file in the **server** folder:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key  # if authentication is used
```

---

### **4. Start the Application**

#### **Backend**

```bash
cd server
npm start
```

#### **Frontend**

```bash
cd client
npm start
```

The app will run at:

* **Frontend:** `http://localhost:3000`
* **Backend API & Socket:** `http://localhost:5000`

---

## 💻 **How It Works**

1. **User connects to the server** via Socket.IO.
2. **Server maintains active users** and broadcasts messages to the correct chat room.
3. **Messages are stored in MongoDB** for persistence.
4. **React updates in real-time** whenever new messages arrive.

