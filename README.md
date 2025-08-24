```markdown
# QuickChat (FullStack) — Real-Time Chat App with Socket.io

QuickChat is a simple, full-stack real-time chat application built with **Node.js**, **Express**, **Socket.io**, and **React (Vite)**. It enables instant messaging, live user notifications, and a smooth real-time chat experience.

---

## ✨ Features

- Real-time messaging with Socket.io
- User join/leave system notifications
- Online user list updates in real time
- Typing indicators
- Clean UI with responsive design
- Full separation of **client** and **server** codebases

---

## 🛠 Tech Stack

- **Server**: Node.js, Express, Socket.io, dotenv, CORS
- **Client**: React (Vite), Socket.io-client
- **Dev Tools**: Nodemon, Vite

---

## 📂 Project Structure

```

QuickChat\_With\_Socket.io\_Using\_FullStack/
├─ server/              # Back-end (Express + Socket.io)
│  ├─ index.js          # Server entry point
│  ├─ package.json      # Server dependencies
│  └─ .env.example      # Example env file
└─ client/              # Front-end (React + Vite)
├─ src/              # React components & styles
├─ index.html        # Entry HTML
└─ package.json      # Client dependencies

````

---

## ⚙️ Setup & Installation

### Prerequisites
- [Node.js](https://nodejs.org/) (v16+ recommended)
- npm (bundled with Node.js) or Yarn

### Clone the Repo
```bash
git clone https://github.com/saitejasevella1914/QuickChat_With_Socket.io_Using_FullStack.git
cd QuickChat_With_Socket.io_Using_FullStack
````

### Install Dependencies

#### Server

```bash
cd server
cp .env.example .env   # configure environment variables
npm install
```

#### Client

```bash
cd ../client
npm install
```

---

## 🚀 Running the App

### Start the Server

```bash
cd server
npm run server   # for development (with nodemon)
npm start     # for production
```

Default: [http://localhost:5000](http://localhost:4000)

### Start the Client

```bash
cd client
npm run dev
```

Default: [http://localhost:5173](http://localhost:5173)

---

## 📌 Usage

* Open the client in your browser.
* Enter a username to join.
* Chat in real time with other connected users.
* See who’s online and when others are typing.

---

## 🔧 Customization

* Change `PORT` or `CORS_ORIGIN` in `server/.env`
* Modify UI in `client/src/App.css`
* Extend with features like chat rooms, authentication, or message persistence (MongoDB, Firebase, etc.)

---

## 🤝 Contributing

Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to change.

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use and modify.

---

## 👨‍💻 Author

Maintained by [**saitejasevella1914**](https://github.com/saitejasevella1914)
