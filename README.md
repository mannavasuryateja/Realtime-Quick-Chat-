# QuickChat – Real-Time Chat Application

A real-time communication web application developed independently using the MERN stack. QuickChat enables users to communicate through instant messaging with a responsive and interactive user interface.

## Project Overview

QuickChat is a full-stack chat application designed to provide real-time communication between users. It uses Socket.io to establish real-time connections and exchange messages, while MongoDB manages application data.

This project was developed independently as part of my practical learning experience in full-stack web development.

## Key Features

- **User Authentication:** User registration and login functionality.
- **Real-Time Messaging:** Instant message exchange using Socket.io.
- **Responsive Interface:** Interactive user interface developed using React.js and CSS Grid.
- **Message Storage:** MongoDB integration for storing user information and message histories.
- **Client-Server Communication:** REST API integration between frontend and backend.

## Technology Stack

| Category | Technologies |
|---|---|
| Frontend | React.js, JavaScript, CSS |
| Backend | Node.js, Express.js |
| Real-Time Communication | Socket.io |
| Database | MongoDB |
| Architecture | MERN Stack |

## Application Architecture

The application follows a client-server architecture.

1. **Frontend:** React.js provides the user interface and handles user interactions.
2. **Backend:** Node.js and Express.js handle API requests and application logic.
3. **Real-Time Communication:** Socket.io enables real-time message exchange between connected users.
4. **Database:** MongoDB stores application data and message histories.

## Project Structure

```text
Realtime-Quick-Chat/
│
├── client/
│   └── Frontend application
│
├── Server.zip
│   └── Backend application source
│
└── README.md
```

## Installation and Setup

### Prerequisites

- Node.js and npm
- MongoDB
- Git

### 1. Clone the repository

```bash
git clone https://github.com/mannavasuryateja/Realtime-Quick-Chat-.git
```

### 2. Navigate to the project

```bash
cd Realtime-Quick-Chat-
```

### 3. Set up the frontend

```bash
cd client
npm install
```

### 4. Set up the backend

Extract `Server.zip` and navigate to the extracted server directory.

```bash
npm install
```

### 5. Configure environment variables

Configure the MongoDB connection string and other required environment variables according to the backend configuration.

### 6. Run the application

Start the frontend and backend using the development scripts defined in their respective `package.json` files.

