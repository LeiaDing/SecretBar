

Authentication Secrets

A web application that allows users to anonymously share secrets. Built with Node.js, Express, and MongoDB.

Features
- User authentication with local strategy (username/password)
- Google OAuth 2.0 integration for social login
- Session management with Passport.js
- Secure secret sharing functionality
- Responsive Bootstrap UI

Technologies Used
- Express.js for server and routing
- MongoDB with Mongoose for data storage
- EJS for view templating
- Passport.js for authentication
- Bootstrap for styling

Getting Started

1. Install dependencies:
npm install


2. Create a .env file with your Google OAuth credentials:

CLIENT_ID=your_google_client_id
CLIENT_SECRET=your_google_client_secret


3. Start MongoDB server

4. Run the application:

node app.js


