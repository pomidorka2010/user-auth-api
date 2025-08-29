# User Auth API

## Description
This project is a small-scale user authentication API that allows users to register, log in, and manage JSON Web Tokens (JWT) for secure authentication. It is built using Node.js and Express, making it easy to integrate with various front-end applications.

## Features
- User registration with hashed passwords using bcrypt
- User login with token generation using JWT
- Middleware for protected routes
- Basic in-memory data storage (can be easily replaced with a database)

## Getting Started
1. Clone the repository: `git clone https://github.com/yourusername/user-auth-api`
2. Navigate to the directory: `cd user-auth-api`
3. Install dependencies: `npm install`
4. Start the server: `npm start`
5. Use tools like Postman to test the API endpoints.

## Endpoints
- `POST /register`: Register a new user
- `POST /login`: Login an existing user
- `GET /protected`: Access protected route (requires token)

## Technologies Used
- Node.js
- Express
- JWT
- bcrypt

## Contributing
Feel free to fork the repository and submit pull requests for improvements!

## License
This project is licensed under the MIT License.
