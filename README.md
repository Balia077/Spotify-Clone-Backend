# 🎧 Spotify Clone Backend

> 🎵 Powering a modern music streaming experience through scalable backend architecture.  
> 🚧 **Status:** Currently under active development.

A RESTful backend API for a **Spotify-like music streaming application** built using **Node.js, Express.js, and MongoDB**.  
This project manages authentication, song uploads, and music data for a streaming platform.

---

## 🛠 Tech Stack

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4ea94b?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Multer](https://img.shields.io/badge/File%20Upload-Multer-blue?style=for-the-badge)

---

## 🚀 Features

- 🔐 User Authentication (Register & Login)
- 🎵 Upload and manage songs
- 📂 File upload handling
- 📡 RESTful API architecture
- 🗄 MongoDB database integration
- ⚙️ Environment-based configuration

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

### 2️⃣ Navigate into the project

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

## ▶️ Running the Server

### Development Mode

```
npm run dev
```

### Production Mode

```
npm start
```

Server runs at:

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
- 🔎 Search functionality
- ☁️ Cloud storage integration
- 📊 Pagination & filtering
- 🎵 Music streaming support

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository and submit a pull request.

---

## 👨‍💻 Author

**Balaram Das**

GitHub:  
https://github.com/Balia077

---

⭐ If you like this project, consider giving it a **star**!
