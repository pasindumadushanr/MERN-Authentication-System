# MERN Authentication System

This is a **MERN-based authentication system** that includes user registration, login, and authentication using JWT. The project follows best practices for security and scalability.

## Features
- User Registration & Login
- JWT-based Authentication
- Password Hashing with bcrypt
- MongoDB Database Integration
- Protected Routes

## Technologies Used
- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ORM)
- **Authentication:** JWT, bcrypt

## Installation & Setup
### Prerequisites
Make sure you have installed:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
- Git

### Clone the Repository
```sh
git clone https://github.com/<your-username>/mern-auth.git
cd mern-auth
```

### Install Dependencies
#### Backend (server)
```sh
cd server
npm install
```

#### Frontend (client)
```sh
cd client
npm install
```

### Setup Environment Variables
Create a `.env` file inside the **server** directory and add:
```
MONGO_URI=<your-mongodb-connection-string>
JWT_SECRET=<your-secret-key>
PORT=5000
```

### Run the Application
#### Start Backend Server
```sh
cd server
npm run dev
```

#### Start Frontend
```sh
cd client
npm start
```

## API Endpoints
### Authentication Routes
| Method | Endpoint        | Description        |
|--------|----------------|--------------------|
| POST   | /api/auth/register | Register a new user |
| POST   | /api/auth/login    | Log in an existing user |
| GET    | /api/auth/user     | Get current user (protected) |

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Added new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is **open-source** and available under the MIT License.

