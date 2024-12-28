# SocialSync

A real-time chatting application with authentication, authorization, and global state management.

## Tech Stack

- **Frontend**: ReactJS, TailwindCSS, DaisyUI
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Real-time**: Socket.io
- **State Management**: Zustand
- **Authentication**: JWT (JSON Web Token)

## Features

- 🌟 **Authentication & Authorization**: Secure login and signup with JWT.
- 👾 **Real-time Messaging**: Instant messaging between users using Socket.io.
- 🚀 **Online User Status**: Track and display the status of online users.
- 👌 **Global State Management**: Manage application state globally using Zustand.
- 🐞 **Error Handling**: Graceful error handling on both the client and server sides.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sarthakkashyapp/SocialSync.git

2. Navigate to the project folder:

   ```bash
   cd SocialSync

3. Install dependencies for both the frontend and backend:   

   Backend and frontend :

    ```bash
   cd backend
   npm install
   
   cd frontend
   npm install

4. Create a .env file in the root directory and add the required environment variables for MongoDB, JWT secret, and any other credentials.

5. Run the development server:

   Backend and Frontend:
   
   ```bash
   cd backend
   npm run dev

   cd frontend
   npm run dev
6. Open http://localhost:5001 in your browser to start using the app.

## Usage

   1. Register or log in using your credentials.
   2. Once logged in, you'll be able to see real-time messages from other users.
   3. Track the online status of users in the chat

## Contributing

   1. Fork this repository.
   2. Create your feature branch (git checkout -b feature-name).
   3. Commit your changes (git commit -am 'Add new feature').
   4. Push to the branch (git push origin feature-name).
   5. Create a new Pull Request.
   Please make sure to follow the coding standards and write tests for your code where applicable.

## License

   This project is licensed under the MIT License - see the LICENSE file for details.
