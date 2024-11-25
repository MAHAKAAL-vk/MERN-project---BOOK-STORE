# Full Stack Book Store App Using MERN

This project is a comprehensive full stack MERN (MongoDB, Express, React, Node.js) stack bookstore website. The project covers both frontend and backend development from the ground up.

## Team Members
1. Hari Prasath S
2. Vikash Kushwaha
3. Jaya Arayan J
4. Bhuvaneshwaran P
5. Sriganth S

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
This project is a full stack bookstore application built using the MERN stack. It allows users to browse, search, and purchase books. The application includes user authentication, book management, and order processing functionalities.

## Features
- User authentication (sign up, login, logout)
- Browse and search for books
- Add books to the cart
- Place orders
- Admin panel for managing books and orders
- Responsive design

## Technologies Used
- **Frontend**: React, Redux, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Other Tools**: Axios, Mongoose

## Installation
To get started with the project, follow these steps:

# 1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/bookstore-app.git
   cd bookstore-app
   ```
# 2. **Install dependencies**:
**Install backend dependencies**
   ```
   cd backend
   npm install
   ```
**Install frontend dependencies**
   ```
   cd ../frontend
   npm install
   ```
# 3. **Set up environment variables:** Create a .env file in the backend directory and add the following **Environment variables**:

   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
   
# 4. **Run the application:**

**Run backend server**
   ```
   cd backend
   npm start
   ```
**Run frontend server**
   ```
   cd ../frontend
   npm start
   ```
## Usage
Once the application is running, you can access it at ```http://localhost:3000```. You can sign up as a new user, browse books, add them to your cart, and place orders. Admin users can manage books and orders through the admin panel.

## Contributing
Contributions are welcome! If you would like to contribute to this project, please follow these steps:

1. Fork the repository.

2. Create a new branch (```git checkout -b feature/your-feature```).

3. Make your changes and commit them (```git commit -m 'Add some feature'```).

4. Push to the branch (```git push origin feature/your-feature```).

5. Open a pull request.

## Acknowledgements
- This project was inspired by the YouTube tutorial by freeCodeCamp.org.

- Special thanks to the open-source community for providing the tools and libraries used in this project.
