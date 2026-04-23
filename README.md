# Lost & Found Item Management System

A full-stack MERN (MongoDB, Express, React, Node.js) application for managing lost and found items on a college campus.

## 🚀 Features
- **Secure Authentication**: JWT-based registration and login.
- **Premium UI**: Modern, minimalist design with a warm aesthetic and glassmorphism.
- **Item Management**: Report lost/found items with categories, locations, and descriptions.
- **Search**: Real-time search by item name or category.
- **Responsive**: Fully responsive design for mobile and desktop.
- **Database Fallback**: Includes a mock data layer to ensure functionality even without a local MongoDB instance.

## 🛠️ Tech Stack
- **Frontend**: React, Vite, Axios, React Router.
- **Backend**: Node.js, Express, Mongoose.
- **Auth**: JWT, Bcrypt.js.
- **Styling**: Vanilla CSS (Custom Design System).

## 📦 Installation

### Prerequisites
- Node.js installed.
- MongoDB (Optional, app includes mock fallback).

### Steps
1. **Clone the repository**:
   ```bash
   git clone <your-repo-url>
   cd devansh
   ```

2. **Setup Backend**:
   ```bash
   cd server
   npm install
   # Create a .env file with MONGO_URI and JWT_SECRET
   npm start
   ```

3. **Setup Frontend**:
   ```bash
   cd client
   npm install
   npm run dev
   ```

4. **Access the app**:
   Open [http://localhost:5173](http://localhost:5173) in your browser.

## 📄 License
MIT
