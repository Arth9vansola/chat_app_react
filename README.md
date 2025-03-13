# chat-app-react

# Real-Time Chat Application

This project is a real-time chat application designed to provide seamless communication between users. Built with modern web technologies, it features a responsive front end and a robust back end to handle real-time interactions efficiently.

## Features
- **Real-Time Messaging**: Instant communication using WebSockets.
- **User Authentication**: Secure login and registration.
- **Responsive Design**: Optimized for mobile and desktop devices.
- **Scalable Backend**: Handles multiple concurrent users.

## Tech Stack
### Frontend
- **React.js**: For building a dynamic and responsive user interface.

### Backend
- **Node.js**: Handles server-side logic and API endpoints.
- **Socket.io**: Enables real-time, bidirectional communication.
- **MongoDB**: Stores user data and chat messages.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/real-time-chat-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd real-time-chat-app
   ```

3. Install dependencies:
   - For the frontend:
     ```bash
     cd public
     yarn install
     ```
   - For the backend:
     ```bash
     cd server
     yarn install
     ```

4. Configure environment variables:
   - Create a `.env` file in the `server` directory with the following:
     ```env
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_jwt_secret
     ```

5. Run the application:
   - Start the backend server:
     ```bash
     cd server
     yarn start
     ```
   - Start the frontend:
     ```bash
     cd public
     yarn start
     ```

6. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## Folder Structure
```
real-time-chat-app/
├── client/         # Frontend code (React.js)
├── server/         # Backend code (Node.js, Socket.io, MongoDB)
└── README.md       # Project documentation
```

## Key Scripts
- **Frontend**:
  - `yarn start`: Runs the React development server.
  - `yarn build`: Builds the app for production.
- **Backend**:
  - `yarn start`: Starts the Node.js server.

## Future Enhancements
- Add support for group chats.
- Implement message notifications.
- Enhance security features.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
