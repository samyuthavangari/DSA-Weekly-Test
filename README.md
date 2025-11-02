# DSA Weekly Test Application

A full-stack application designed for taking weekly Data Structures and Algorithms (DSA) tests. This project features a React frontend and a Node.js backend.

---

### &#128640; Technologies Used

<p align="center">
  <img src="https://img.shields.io/badge/-ReactJs-61DAFB?logo=react&logoColor=white&style=for-the-badge" alt="React" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=Vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB" alt="Express" />
  <img src="https://img.shields.io/badge/-MongoDB-13aa52?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" />
</p>

---

## &#128295; Project Structure

This project is a monorepo with two main parts:

* **/frontend**: A React application built with Vite.
* **/backend**: A Node.js and Express server with MongoDB.

### Frontend (dsa-test-app-frontend)

* **React 19**: For building the user interface.
* **Vite**: As the frontend build tool and dev server.
* **React Router (`react-router-dom`)**: For client-side routing.
* **Axios**: For making API requests to the backend.

### Backend (dsa-test-app-backend)

* **Node.js**: As the runtime environment.
* **Express**: As the web server framework.
* **Mongoose**: For object data modeling (ODM) with MongoDB.
* **JSON Web Token (`jsonwebtoken`)**: For user authentication (JWT).
* **bcryptjs**: For password hashing.
* **CORS**: To handle cross-origin resource sharing.
* **dotenv**: For managing environment variables.

## &#128679; Setup and Installation

To run this project locally, you will need to set up both the backend and frontend.

### 1. Backend Setup

```bash
# 1. Navigate to the backend directory
cd backend

# 2. Install dependencies
npm install

# 3. Create a .env file in the /backend directory
#    Add your environment variables (like MONGO_URI, JWT_SECRET, etc.)
touch .env

# 4. Start the development server (using nodemon)
npm run test 
# Note: Your "test" script currently just echoes an error. 
# You may want to add a "start" or "dev" script to your backend/package.json,
# for example: "dev": "nodemon server.js"
