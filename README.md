# 🧑‍💼 Fiverr Clone - MERN Stack Freelance Marketplace

A full-stack freelance marketplace web application inspired by **Fiverr**, built using the **MERN Stack (MongoDB, Express, React, Node.js)**. Users can register as buyers or sellers, create gigs, browse services, place orders, and manage freelance workflows — replicating Fiverr's core features with a clean and responsive SCSS-based UI.

---

## 🚀 Features

- 🔐 JWT-based Authentication (Buyers & Sellers)
- 🎨 Create, edit, and delete gigs
- 🔍 Browse and search freelance services
- 📦 Order placement and tracking
- 📱 Responsive design using SCSS
- ⚙️ Separate frontend and backend with Yarn support

---

## 🛠 Tech Stack

- **Frontend**: React, React Router, SCSS, Axios
- **Backend**: Node.js, Express.js
- **Database**: MongoDB + Mongoose
- **Authentication**: JWT
- **Package Manager**: Yarn

---

## 📁 Folder Structure

fiverr-clone/
├── api/ # Backend (Express + MongoDB)
├── client/ # Frontend (React + SCSS)


---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fiverr-clone.git
cd fiverr-clone
2. Backend Setup
cd api
yarn install
yarn start
Runs server on http://localhost:5000

3. Frontend Setup
cd client
yarn install
yarn run dev
Runs frontend on http://localhost:5173 by default

🌐 Environment Variables
In api/.env:
env
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
In client/.env:
env
Copy
Edit
VITE_API_URL=http://localhost:5000/api

