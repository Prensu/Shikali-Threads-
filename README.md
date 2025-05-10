
# 🧵 Shikali Threads

Shikali Threads is a full-stack e-commerce web application for traditional and modern Nepali wearables. This project is built using the MERN stack (MongoDB, Express.js, React, and Node.js).

## 📁 Folder Structure

```
shikali-threads/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       └── App.js
├── .env.example
└── README.md
```

## 🚀 Features

- Product listing and details
- Add to cart functionality
- React context for global state
- Express backend with RESTful APIs
- MongoDB integration for data storage
- Local currency support (NPR)
- Clean responsive design using Tailwind CSS

## 🛠️ Requirements

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/) (local or Atlas)
- [Git](https://git-scm.com/)
- A package manager: `npm` or `yarn`

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/shikali-threads.git
cd shikali-threads
```

Or if you downloaded ZIP:
- Unzip the folder
- Open it in your code editor
- Proceed to the steps below

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file based on `.env.example`:

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/shikalidb
```

Then start the backend server:

```bash
npm run dev
```

### 3. Setup Frontend

In a new terminal:

```bash
cd frontend
npm install
npm start or npm run dev
```

This will run the frontend on `http://localhost:3000`

## 🌐 Environment Variables

Update your `.env` files in both `frontend` and `backend` directories as needed:

#### Backend `.env`:
```env
PORT=5000
MONGO_URI=your-mongodb-uri
```

#### Frontend `.env` (optional):
```env
REACT_APP_API_URL=http://localhost:5000/api
```

## 💰 Currency Format

The project is pre-configured to use **Nepali Rupees (Rs.)** for all product prices.

## 👨‍💻 Developer

- 🔗 Prensu Dangol (https://prensu.com.np)
- 📧 dangolprensu17newar@gmail.com

## 📃 License

This project is open-source and free to use under the [MIT License](LICENSE).
