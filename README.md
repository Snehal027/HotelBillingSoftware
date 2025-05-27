# HotelBillingSoftware


A full-stack billing system application built with Node.js/Express for the backend and a modern frontend interface. This application handles user authentication, table and room management, and order processing.

## 🚀 Features

- Table and Room Management
- Order Placement and History
- RESTful API structure
- Environment-based configuration
- Modularized folder structure for scalability

## 🛠 Tech Stack

### Backend:
- Node.js
- Express.js
- MongoDB
- Mongoose


### Frontend:
- HTML
- CSS
- React
## 📁 Project Structure

Billing 2.0/
├── Backend/
│ ├── Controllers/
│ ├── Database/
│ ├── Middleware/
│ ├── Models/
│ ├── Routers/
│ ├── .env
│ ├── index.js
│ └── package.json
├── Frontend/
└── package.json


## 📦 Installation & Setup

### Backend Setup

```bash
cd "Billing 2.0/Backend"
npm install
npm run dev
###Ensure that .env file
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

cd "Billing 2.0/Frontend"
npm install
npm run dev
