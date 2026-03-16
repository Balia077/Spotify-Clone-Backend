🎧 Spotify Clone Backend

A backend API for a Spotify-like music streaming application built with Node.js, Express, and MongoDB.
This project handles user authentication, song management, and file uploads for a music platform.

🚀 Features

🔐 User Authentication (Register & Login)

🎵 Upload and manage songs

📂 File upload support

📡 RESTful API structure

🗄 Database integration with MongoDB

⚙️ Environment variable configuration

🛠 Tech Stack

Node.js

Express.js

MongoDB

Mongoose

Multer (for file uploads)

JWT Authentication

dotenv

📁 Project Structure
Spotify-Clone-Backend
│
├── src
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── config
│
├── server.js
├── package.json
└── README.md

⚙️ Installation

Clone the repository

git clone https://github.com/Balia077/Spotify-Clone-Backend.git

Go to the project folder

cd Spotify-Clone-Backend

Install dependencies

npm install
🔑 Environment Variables

Create a .env file in the root directory.

Example:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
▶️ Run the Server

Development mode

npm run dev

Production mode

npm start

Server will run on:

http://localhost:5000
📡 API Endpoints
Authentication
POST /api/auth/register
POST /api/auth/login
Songs
GET /api/songs
POST /api/songs/upload
GET /api/songs/:id
DELETE /api/songs/:id
🧪 Future Improvements

🎧 Playlist creation

❤️ Like / favorite songs

☁️ Cloud storage integration

🔎 Search songs

📊 Pagination and filtering

🎵 Streaming support

🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

📜 License

This project is licensed under the MIT License.

👨‍💻 Author

Balaram Das

GitHub:
https://github.com/Balia077
