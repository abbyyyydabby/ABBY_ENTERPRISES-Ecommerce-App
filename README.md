ABBY ENTERPRISES: MERN E-commerce App

Welcome to ABBY ENTERPRISES, a full-stack MERN E-commerce Application.
This project is built using the MERN stack – MongoDB, Express.js, React.js, and Node.js.

It’s a demo of how a modern online store works:

Users can browse products, add them to a cart, and place orders.

Secure login & signup system.

Checkout process with order confirmation.

Smart product recommendations (using vector search).

This project shows both the frontend (user interface) and the backend (server + database) in action.

Live Demo

Frontend App: ABBY ENTERPRISES App

Backend API: ABBY ENTERPRISES API

⚠️ Note: The backend may take a few seconds to load since it runs on a free server.

Main Features

Products: Browse, search, and view details.

Shopping Cart: Add/remove items, see total price.

Checkout: Enter shipping/payment info & confirm order.

User Accounts: Register, login, reset password.

Recommendations: Suggests similar products.

Tech Stack

Frontend: React.js, Material-UI, React Router, React Hook Form, Toast notifications.

Backend: Node.js, Express.js, MongoDB, JWT (login security), Bcrypt (password hashing).

Extra Tools: Weaviate (recommendations), FAISS + LangChain (vector search), Jest (testing), Swagger (API docs), Docker (containerization).

How to Run Locally
Prerequisites

Make sure you have:

Node.js + npm

MongoDB (local or cloud)

Git

Installation

Clone this repo:

git clone https://github.com/hoangsonww/MERN-Stack-Ecommerce-App.git
cd MERN-Stack-Ecommerce-App


Install dependencies:

# Backend
cd backend
npm install

# Frontend
cd ..
npm install


Add your .env file in backend/ with:

MONGO_URI=mongodb://localhost:27017/Ecommerce-Products
JWT_SECRET=your_secret_key


Seed database with sample products:

cd backend/seed
node productSeeds.js dev


Start servers:

# Backend
cd backend
npm start

# Frontend
cd ..
npm start


Now visit http://localhost:3000
 to use the app.

Testing

Run backend tests:

cd backend
npm test


Run frontend tests:

npm test

Project Structure (Simple View)
ABBY-ENTERPRISES/
├── backend/   # API, database, authentication
├── src/       # Frontend React code
├── public/    # Static assets (logo, favicon, etc.)
└── tests/     # Automated tests
