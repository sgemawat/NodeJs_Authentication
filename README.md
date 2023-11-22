# Node.js Authentication System

This project is a complete authentication system that can be used as a starter code for creating any new application. <a href="https://vast-pear-squirrel-sari.cyclic.app/" target="_blank">LIVE</a>

- Sign up with email
- Sign in
- Sign out
- Reset password after sign in
- [Bonus Feature] Forgot password (reset password link)

The password stored in the database is encrypted using hashing.

## Technologies Used

- Node.js
- Express.js
- Passport.js
- JSON Web Tokens (JWT)
- EJS (Embedded JavaScript) templating engine
- MongoDB (NoSQL database)
- Next.js (optional, for server-side rendered React application)
- Bootstrap (optional, for CSS styling)


## Installation and Setup

1. Clone the repository:
2. Install dependencies:
3. Set up MongoDB:
   - Install MongoDB if you haven't.
   - Create a new MongoDB database for this project.
4. Configure environment variables: 
5. Run the application:
   - npm start.
6. Open your web browser and go to `http://localhost:3000` to access the application.

## Features and Usage

- **Register:** Visit the `/register` route to create a new account using your email and password.

- **Login:** Access the `/login` route to log in with your registered email and password.

- **Log Out:** Click on the "Sign Out" button in the `/home` page to log out of the session.

- **Reset Password:** Once logged in, navigate to `forgot` to reset your password.

## Additional Notes

- The password stored in the database is securely encrypted using hashing algorithms.

- The application uses JSON Web Tokens (JWT) for session management.





