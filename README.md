# CAPTCHA Authentication System

A modern CAPTCHA authentication system built with React and Node.js, featuring user registration, login functionality, and logging of authentication attempts to MongoDB. This project provides a comprehensive solution for secure user authentication with CAPTCHA verification.

## Features

- **User Registration**: Sign up with username and password.
- **User Login**: Secure login with username, password, and CAPTCHA.
- **CAPTCHA Verification**: Integrate CAPTCHA for enhanced security.
- **Logging Attempts**: Log all authentication attempts to MongoDB.
- **Home Page**: Post-login page with dynamic content and logout functionality.

## Technologies Used

- **Frontend**:

  - React
  - Axios
  - Material-UI

- **Backend**:
  - Node.js
  - Express
  - MongoDB
  - Mongoose
  - CAPTCHA Service

## Installation

### Prerequisites

- Node.js and npm installed
- MongoDB instance running

### Clone the Repository

```bash
git clone https://github.com/your-username/captcha-authentication-system.git
cd captcha-authentication-system
```

### Setup Backend

1. Navigate to the `server` directory:

   ```bash
   cd server
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Configure your MongoDB connection in `server/config/config.js`:

   ```javascript
   module.exports = {
     mongoURI: "mongodb://localhost:27017/your-database",
   };
   ```

4. Start the server:

   ```bash
   node server.js
   ```

### Setup Frontend

1. Navigate to the `client` directory:

   ```bash
   cd client
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the React app:

   ```bash
   npm start
   ```

## Usage

1. **Register**: Navigate to the registration page, fill out the form, complete the CAPTCHA, and submit to create a new account.

2. **Login**: Navigate to the login page, enter your credentials, solve the CAPTCHA, and submit to log in.

3. **Home Page**: After logging in, you'll be redirected to the home page where you can interact with the dynamic content and log out.

## Configuration

- **CAPTCHA Service**: Replace the CAPTCHA API keys in `server/utils/captcha.js` with your own.

## Troubleshooting

- Ensure MongoDB is running and accessible.
- Verify that the correct MongoDB URI is configured.
- Check for any CORS issues if the frontend cannot communicate with the backend.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [Express](https://expressjs.com/)
- [MongoDB](https://www.mongodb.com/)
- [Mongoose](https://mongoosejs.com/)
- [Material-UI](https://mui.com/)
