# Simple Auth REST API

A secure authentication REST API built with Node.js and Express.js

## Tech Stack
- Node.js
- Express.js
- JWT (JSON Web Tokens)
- bcrypt.js

## Features
- User Registration with password hashing
- User Login with JWT token
- Logout with token blacklist

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /register | Register new user |
| POST | /login | Login and get token |
| POST | /logout | Logout user |

## How to Run

1. Clone the repo
2. Run `npm install`
3. Create `.env` file with `PORT=5000` and `JWT_SECRET=yoursecret`
4. Run `npm run dev`
5. Test with Thunder Client or Postman

## Author
SriMithra - Beginner Full Stack Developer
