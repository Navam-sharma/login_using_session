# login_using_session

# Session-based Authentication Project

This project demonstrates a simple login/logout system using sessions and cookies for authentication. Users can register, login, and logout securely using session-based authentication.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
  
   git clone https://github.com/Navam-sharma/login_using_session.git

2. **Navigate to the project directory:**

   cd login_using_session

3. **Install dependencies:**

 npm install express express-session mongoose bcryptjs ejs

4. **Set up MongoDB:**

   - Make sure MongoDB is installed and running on your system.
   - Create a database named `login_using_session` or adjust the MongoDB connection URL in `config/db.js` as needed.

5. **Start the server:**

   ```bash
   node server.js
   ```

6. **Access the application:**

   Open your web browser and navigate to `http://localhost:3000` to view the application.

## Usage

- **Register:** Navigate to `/register` to create a new user account.
- **Login:** Navigate to `/login` to enter your credentials and log in.
- **Logout:** Click the "Logout" button on the home page (`/`) to log out.

## Dependencies

- [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [Express Session](https://www.npmjs.com/package/express-session): Session middleware for Express.
- [Mongoose](https://mongoosejs.com/): Elegant MongoDB object modeling for Node.js.
- [bcryptjs](https://www.npmjs.com/package/bcryptjs): Library for hashing passwords.
- [EJS](https://ejs.co/): Embedded JavaScript templating.


### Notes:

- Ensure MongoDB is running and accessible.
- Modify routes and views (`views/`) as per your project requirements.
- Customize session configurations (`server.js`) as needed for production environments.

This README file provides clear instructions for downloading, installing dependencies, setting up MongoDB, starting the server, and accessing the application. It also outlines basic usage and dependencies used in the project. Adjust the instructions and details according to any specific configurations or additional features your project may have.
