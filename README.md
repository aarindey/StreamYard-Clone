# Browser-based Live Stream Application

This application utilizes RTMP streaming and is designed to run as a Dockerized container. It leverages Express server for backend operations, Ffmpeg for video streaming, and socket.io for real-time communication over TCP connection.

## Features

- Browser-based live streaming using RTMP protocol.
- Utilizes Express server for handling backend operations.
- Incorporates Ffmpeg for video streaming functionality.
- Implements Docker to run the application in a containerized environment.
- Utilizes socket.io for real-time communication between server and clients.

## Project Structure

The project follows a simple structure:

.
├── public # Contains HTML and JavaScript files for frontend
│ ├── index.html # Main HTML file for the frontend
│ └── script.js # JavaScript file for frontend functionality
├── index.js # Backend server code
└── Dockerfile # Dockerfile for containerization

bash
Copy code

## Setup and Running

Clone the repository:
```
git clone <repository_url>
```

Navigate to the project directory:
```
cd <project_directory>
```

Install dependencies:
```
npm install
```

Run the application using Docker Compose:
```
docker-compose up
```

This will start the application in a containerized environment.

Dependencies
Express
Nodemon
Socket.io

Note
To avoid the hassle of installing Ffmpeg library locally, the application is containerized using Docker, ensuring seamless deployment and execution without the need for manual library installations.
