# Real-Time Chat Video

A real-time video and chat application that allows users to connect via video calls and send instant messages. Built using WebRTC, Socket.IO, React, and modern web technologies.

## Project Structure

The project is divided into two main directories:

- **Server**: Contains the backend code using Node.js and Express.
- **Client**: Contains the frontend code using React and Vite.

## Features

- **Real-Time Video Call**: Peer-to-peer video calling with WebRTC.
- **Instant Messaging**: Real-time chat functionality using Socket.IO.
- **Multiple Rooms**: Ability to join or create multiple chat rooms.
- **Responsive Design**: Optimized for both mobile and desktop devices.
- **User Authentication**: Sign up and log in to start chatting and video calling.

## Demo

A live demo of the application is available [here](https://example.com).

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/real-time-chat-video.git
   cd real-time-chat-video
   ```

2. **Navigate to the server directory**:
   ```bash
   cd server
   ```

3. **Install server dependencies**:
   ```bash
   npm install
   ```

4. **Create a .env file in the root directory of 'server' to store your environment variables:**

5. **Add the following variables to the .env file**:
   ```bash
   PORT=8000
   MONGO_URL=your_mongo_url
   JWT_SECRET=your_jwt_secret
   ```

6. **Run the server**:
   ```bash
   npm run dev
   ```

7. **Navigate to the client directory**:
   ```bash
   cd ../client
   ```

8. **Install client dependencies**:
   ```bash
   npm install
   ```

9. **Run the client**:
   ```bash
   npm run dev
   ```

This will start the client at http://localhost:3000