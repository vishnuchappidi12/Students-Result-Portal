# Student Result Portal

A full-stack web application for managing student results using the MERN stack (MongoDB, Express.js, React.js, Node.js).

## Features

- Admin Authentication with JWT
- Student Registration with Photo Upload
- Result Management System
- Hall Ticket Search
- Marks Entry and Updates
- Secure Password Hashing
- Protected Admin Routes

## Tech Stack

- Frontend: React.js, React Router, Axios
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JWT, bcrypt
- File Upload: Multer

## Project Structure

```
├── Backend/               # Backend Server
│   ├── controllers/      # Route Controllers
│   ├── models/          # Database Models
│   ├── routes/          # API Routes
│   └── phots/          # Uploaded Photos
└── fend/                # Frontend React App
    ├── public/         # Static Files
    └── src/           # React Source Code
        └── comp/     # React Components
```

## Setup Instructions

1. Clone the repository
2. Install backend dependencies:
   ```bash
   cd Backend
   npm install
   ```
3. Install frontend dependencies:
   ```bash
   cd fend
   npm install
   ```
4. Start the backend server:
   ```bash
   cd Backend
   npm start
   ```
5. Start the frontend development server:
   ```bash
   cd fend
   npm start
   ```

## Environment Variables

Create `.env` file in Backend folder:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=5000
```

## Features in Detail

1. **Admin Management**
   - Admin Registration
   - Secure Login with JWT
   - Protected Routes

2. **Student Management**
   - Add New Students
   - Upload Student Photos
   - Update Student Details
   - Delete Student Records

3. **Result Management**
   - Enter Student Marks
   - Update Results
   - View Results by Hall Ticket
   - Search by Various Criteria

## Security Features

- Password Hashing using bcrypt
- JWT Authentication
- Protected Admin Routes
- Secure File Upload
