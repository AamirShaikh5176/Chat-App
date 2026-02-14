<p align="center">
  <img src="https://github.com/user-attachments/assets/1e6cc34e-ed4f-4983-a9d9-57026b52c8ab" width="45%" />
  <img src="https://github.com/user-attachments/assets/1b149457-9440-4672-bc3b-c02ce32c20e3" width="45%" />
</p>

# 💬 JS Chat App (WebSocket)

A simple **real-time chat application** built using **HTML, CSS, JavaScript, Node.js, and WebSocket**.
This project demonstrates how to implement **two-way communication between client and server** using WebSockets.

The app allows multiple users to connect and exchange messages instantly without refreshing the page.

---

## ✨ Features

* ⚡ Real-time messaging
* 🔌 WebSocket server using Node.js
* 🎨 Simple chat UI with Bootstrap
* 👤 Username stored using localStorage
* 📡 Message broadcasting to all connected clients

---

## 📁 Project Structure

```
project-folder/
│
├── index.html
├── styles.css
├── chat_app.js
├── socket_server.js
├── package.json
└── README.md
```

---

## ⚙️ Installation

Make sure Node.js is installed.

```bash
npm install
```

Or install WebSocket manually:

```bash
npm install ws
```

---

## ▶️ Run the Project

Start the WebSocket server:

```bash
node socket_server.js
```

Then open:

```
index.html
```

in your browser.

---

## 🧠 How It Works

1. Client connects to WebSocket server
2. User enters a name
3. Messages are sent to the server
4. Server broadcasts messages to all clients
5. Chat updates instantly

---

## 📦 Dependencies

* Node.js
* ws (WebSocket library)
* Bootstrap
* jQuery

---

## 🔮 Future Improvements

* 🔐 Authentication system
* 💬 Chat rooms
* 🗄 Database storage
* 🖼 File/image sharing
* 🛡 Security improvements

---

## 👨‍💻 Author

Made with ❤️ by **Aamir**
