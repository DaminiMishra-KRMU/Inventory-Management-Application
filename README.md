# React-Inventory-Management-System
Inventory Management System Built with React JS, Node JS, Express JS, MongoDB and Tailwind CSS.

# [<span style="color: blue;">View Live Preview from here.</span>](https://inventory-management-rosy.vercel.app)

### Project Structure  
Inventory-Management-Application/
├── backend/                # Backend server (Node.js/Express)
│   ├── controllers/        # Route handlers
│   ├── models/             # Mongoose models
│   ├── routes/             # API routes
│   ├── .env                # Environment variables
│   ├── server.js           # Server entry point
│   └── ...
├── frontend/               # Frontend application (React)
│   ├── public/             # Public assets
│   ├── src/                # Source code
│   ├── .env                # Environment variables
│   └── ...
└── README.md               # Project documentation

### Project Structure 

Clone the repository:

git clone https://github.com/DaminiMishra-KRMU/Inventory-Management-Application.git
cd Inventory-Management-Application

### Backend Setup
Go to the backend folder:
cd backend

### Install dependencies:
npm install
### Create a .env file with:

PORT=5000
MONGODB_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

### Start the server:

npm start

### Frontend Setup
Open a new terminal and go to the frontend folder:
cd frontend

### Install dependencies:

npm install

### Create a .env file with:

REACT_APP_API_URL=http://localhost:5000

### Start the frontend:

npm start

