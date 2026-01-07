# FullStack Job Portal App | MERN Stack

A FullStack Job Portal Web Application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users and companies to post, apply, and manage jobs efficiently.

## Features

- User registration and login with authentication
- Company registration and job posting
- Job search and apply functionality
- Track applications and statuses
- Responsive frontend with React + Vite
- RESTful APIs with Express.js and MongoDB
- Cookie-based session management and CORS enabled

## Tech Stack

- Frontend: React.js, Vite, HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB
- Other: dotenv, cookie-parser, CORS

## Project Structure
```
JobPortal/
├── client/               # React + Vite frontend
├── server/               # Node/Express backend
│   ├── routes/           # API routes
│   ├── utils/            # DB connection utility
│   └── index.js          # Server entry point
├── package.json
└── README.md
```
## Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/JobPortal.git
cd JobPortal
```

2. Install backend dependencies:
```
cd server
npm install
```

3. Install frontend dependencies:
```
cd ../client
npm install
```

4. Create a .env file in the server folder with your environment variables:
```
PORT=3000
MONGODB_URL=your_mongodb_connection_string
```
## Running the Project
### Backend
```
cd server
node index.js
```
Server runs on http://localhost:3000.

### Frontend
```
cd client
npm run dev
```
Frontend runs on http://localhost:5173 (Vite default).

## API Routes

- User Routes: /api/v1/user (register, login, profile)
- Company Routes: /api/v1/company (register, post jobs)
- Job Routes: /api/v1/job (list, search, details)
- Application Routes: /api/v1/application (apply, track)

## Screenshot
<img width="705" height="297" alt="image" src="https://github.com/user-attachments/assets/abd911e9-f531-4189-a9ea-4ca9be8a2237" />

