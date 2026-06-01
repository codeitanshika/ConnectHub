# 💬 Real-Time Chat Application

A modern real-time chat application built using **React**, **Vite**, **Socket.IO**, **Node.js**, and **Express.js**. The application enables users to communicate instantly through dynamic chat rooms with real-time message delivery and a responsive user interface.

---

## 🚀 Features

* ⚡ Real-time messaging using Socket.IO
* 👥 Join and chat in custom rooms
* 📱 Responsive and user-friendly interface
* 🔄 Instant message synchronization
* 🟢 Online communication without page refresh
* 🎨 Modern React-based frontend
* ⚙️ Fast development and build process with Vite
* 🔌 Client-server architecture using WebSockets

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* CSS / SCSS
* Socket.IO Client

### Backend

* Node.js
* Express.js
* Socket.IO

### Tools

* Git & GitHub
* npm

---

## 📂 Project Structure

```bash
real-time-chat-app/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── server/
│   ├── index.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/real-time-chat-app.git
cd real-time-chat-app
```

### Install Frontend Dependencies

```bash
cd client
npm install
```

### Install Backend Dependencies

```bash
cd ../server
npm install
```

---

## ▶️ Running the Application

### Start Backend Server

```bash
cd server
npm start
```

### Start Frontend

```bash
cd client
npm run dev
```

Frontend will run on:

```text
http://localhost:5173
```

Backend will run on:

```text
http://localhost:5000
```

---

## 🔄 How It Works

1. Users enter a username and room name.
2. The client establishes a Socket.IO connection with the server.
3. Users joining the same room can exchange messages instantly.
4. The server broadcasts messages to all connected users in that room.
5. Messages are updated in real time without refreshing the page.

---

## 🌟 Future Enhancements

* User authentication
* Private messaging
* Message persistence with database
* Emoji support
* File and image sharing
* Read receipts
* Voice and video calling
* Dark mode

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to the branch

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Anshika**

Interested in Full Stack Development, Artificial Intelligence, and Real-Time Web Applications.

⭐ If you found this project useful, consider giving it a star on GitHub.
