# 🎧 Spotify Clone Backend

A RESTful backend API for a **Spotify-like music streaming application** built using **Node.js, Express.js, and MongoDB**.  
This project handles authentication, song management, and file uploads for a music platform.

---

## 🚀 Features

- 🔐 User Authentication (Register & Login)
- 🎵 Upload and manage songs
- 📂 File upload support
- 📡 RESTful API architecture
- 🗄 MongoDB database integration
- ⚙️ Environment variable configuration

---

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB**
- **Mongoose**
- **JWT Authentication**
- **Multer**
- **dotenv**

---

## 📁 Project Structure

```
Spotify-Clone-Backend
│
├── src
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── config
│
├── uploads
├── server.js
├── package.json
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Balia077/Spotify-Clone-Backend.git
```

### 2️⃣ Navigate into project folder

```bash
cd Spotify-Clone-Backend
```

### 3️⃣ Install dependencies

```bash
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

Example:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

---

## ▶️ Run the Server

### Development Mode

```bash
npm run dev
```

### Production Mode

```bash
npm start
```

Server runs on:

```
http://localhost:5000
```

---

## 📡 API Endpoints

### Authentication

```
POST /api/auth/register
POST /api/auth/login
```

### Songs

```
GET    /api/songs
POST   /api/songs/upload
GET    /api/songs/:id
DELETE /api/songs/:id
```

---

## 🧪 Future Improvements

- 🎧 Playlist creation
- ❤️ Like / favorite songs
- ☁️ Cloud storage integration (Cloudinary/AWS)
- 🔎 Song search functionality
- 📊 Pagination & filtering
- 🎵 Audio streaming support

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Balaram Das**

GitHub: https://github.com/Balia077
