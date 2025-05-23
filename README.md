📝 Description
Secrets is a secure and anonymous secret sharing web application that allows users to share their thoughts without revealing their identity. Built with Node.js, Express, and MongoDB, Whisper provides a safe space for people to express themselves freely.
✨ Features

🔐 Secure user authentication
🔑 Multiple authentication methods:

Email/password registration
Google OAuth 2.0 integration


📱 Responsive design for all devices
📝 Submit and view secrets anonymously
🛡️ Session-based security
👤 User accounts for managing your shared secrets

🛠️ Technologies Used

Backend: Node.js, Express.js
Database: MongoDB with Mongoose
Authentication: Passport.js, Google OAuth 2.0
View Engine: EJS
Styling: CSS (likely Bootstrap, based on standard implementations)
Session Management: express-session

🚀 Installation

Clone the repository:
bashgit clone https://github.com/Youssef19110/secrets.git
cd secrets

Install dependencies:
bashnpm install

Create a .env file in the root directory with the following variables:
CLIENT_ID=your_google_oauth_client_id
CLIENT_SECRET=your_google_oauth_client_secret

Make sure MongoDB is installed and running on your system.
Start the application:
bashnode app.js

Open your browser and navigate to http://localhost:3000

📋 Usage

Register a new account or login with Google
Navigate to the "Submit" page to share your secret
View all anonymous secrets on the "Secrets" page
Logout when finished

🔒 Security Notes

The application uses Passport.js for secure authentication
Passwords are salted and hashed using industry standards
Sessions are secured with custom secret keys
Google OAuth provides an additional layer of security

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

Fork the repository
Create your feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add some amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
🙏 Acknowledgements

Express.js
MongoDB
Passport.js
EJS
Google OAuth 2.0


Made with ❤️ by Youssef
