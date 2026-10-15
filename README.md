# 🔗 URL Shortener

A simple and efficient URL Shortener built using the **MERN stack technologies** (MongoDB, Express.js, React.js, and Node.js). It converts long URLs into short links, making them easier to share and manage.

## 🚀 Features

- 🔗 **Shorten URLs** — Convert long URLs into short, shareable links.
- 📋 **Copy Short URL** — Copy generated links easily.
- ↗️ **Redirect to Original URL** — Open the original website using the short link.
- 📊 **Click Tracking** — Track how many times a short URL is visited.
- 🗑️ **Delete URLs** — Remove saved URLs when no longer needed.
- 📱 **Responsive UI** — Clean interface for desktop and mobile devices.
- ⚡ **REST API** — Backend APIs built with Express.js.

## 🛠️ Tech Stack

**Frontend**
- React.js
- Vite
- Axios
- CSS

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose

**Tools**
- Git & GitHub
- npm

## 📁 Project Structure

```text
URL-Shortner/
├── backend/
│   └── src/
│       ├── app/
│       ├── config/
│       ├── models/
│       ├── routes/
│       └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── main.jsx
│   └── package.json
│
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/RajaKumar207-de/URL-Shortner.git
cd URL-Shortner
```

### 2. Set up the backend

```bash
cd backend
npm install
```

Create a `.env` file in the backend directory and configure your MongoDB connection string and any environment variables required by your code.

Example:

```env
PORT=3000
MONGO_URI=your_mongodb_connection_string
```

Start the backend:

```bash
npm run dev
```

### 3. Set up the frontend

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

Open the local URL displayed by Vite in your browser.

## 🔌 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/url` | Create a short URL |
| GET | `/api/url` | Retrieve saved URLs |
| DELETE | `/api/url/:id` | Delete a saved URL |
| GET | `/:code` | Redirect to the original URL |

*Note: The endpoints above describe the intended project routes; confirm them against your backend implementation.*

## 💡 How It Works

1. Enter a long URL in the input field.
2. Submit the form to generate a unique short code.
3. Save the original URL and short code in MongoDB.
4. Open the short link to redirect to the original website.
5. Track clicks and manage saved links from the interface.

## 🔐 Environment Variables

Keep database credentials and API secrets in `.env` files. **Never commit secrets or `.env` files to GitHub.**

## 👨‍💻 Author

**Raja Kumar**

- GitHub: [@RajaKumar207-de](https://github.com/RajaKumar207-de)

## ⭐ Support

If you find this project useful, consider giving the repository a star!

---

Built with ❤️ using React, Node.js, Express.js, and MongoDB.
