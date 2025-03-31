# YouTube Clone - MERN Stack

## Project Overview
This is a full-stack YouTube clone application developed using the **MERN stack** (MongoDB, Express, React, Node.js). The app allows users to view, interact with videos, and manage their own channels. Users can sign up, log in, and authenticate using JWT (JSON Web Tokens). The app also supports video search, filtering, commenting, and more.

### Key Features:
- **Home Page:** Displays a YouTube-like header, sidebar, video grid with thumbnails, and filter buttons.
- **User Authentication:** Registration, login, and JWT-based authentication.
- **Search & Filter Functionality:** Search videos by title and filter by category.
- **Video Player Page:** Play selected videos with like/dislike buttons and comments section.
- **Responsive Design:** The application is fully responsive and works across all screen sizes.
- **JWT Integration:** Secure token-based authentication for protected routes.
  
## Technologies Used
- **Frontend:**
  - React.js
  - React Router
  - Axios for HTTP requests
- **Backend:**
  - Node.js
  - Express.js
  - MongoDB (MongoDB Atlas or local instance)
- **Authentication:**
  - JWT (JSON Web Tokens) for secure authentication
- **Database:**
  - MongoDB (stores users, videos, channels, and comments)

    ## Project Setup
### Prerequisites

Make sure you have the following installed:
- **Node.js**: Download Node.js
- **MongoDB**: install MongoDB locally.
- **Git**: Use GitHub 

### Backend Setup

1. Clone the repository:
   https://github.com/Madhumita-15062020/You-Tube-Clone.git
2. Navigate to the backend directory:
    cd backend
3. Install the dependencies:
    npm install
4. Set up your **MongoDB** connection (use MongoDB Atlas or a local MongoDB instance). Create a `.env` file with the following content:
    MONGO_URI=mongodb://your_mongo_uri
    JWT_SECRET=your_jwt_secret_key

5. Start the backend server:
    npm start
The backend server will be running at `http://localhost:5000`.

### Frontend Setup

1. Navigate to the frontend directory:
    cd frontend
2. Install the dependencies:
    npm install
3. Run the React app:
    npm start
The frontend application will be running at `http://localhost:3000`.

## Running the Application

### Frontend:
1. Start the frontend by navigating to the `frontend` directory and running:
    npm start
   The React app will be available at [http://localhost:3000](http://localhost:3000).

### Backend:
1. Start the backend server by navigating to the `backend` directory and running:
    npm start
   The backend server will be available at [http://localhost:5000](http://localhost:5000).

---

## Demo

A short video demo showcasing the application's features is available.


