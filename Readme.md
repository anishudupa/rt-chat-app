# Fullstack Real-Time Chat App

This is a real-time chat application built using **Express** and **Socket.io** for the backend, and a simple frontend to interact with it. The app allows users to join rooms, send messages, and view the activity of other users in real-time.

## Features

- **Real-time messaging**: Users can send and receive messages instantly.
- **Room management**: Users can join specific chat rooms and interact with others in the same room.
- **User presence**: The app tracks when users join or leave a room, updating other users accordingly.
- **Admin notifications**: The app sends system messages when users join/leave rooms and other activities.
- **Live user list**: Users in a room are updated in real-time.

## Technologies

- **Backend**:
  - Express: Web framework for Node.js.
  - Socket.io: Real-time bidirectional event-based communication.
- **Frontend**:
  - HTML, CSS, JavaScript (with Socket.io client).

## Getting Started

To run the chat app locally, follow the steps below:

### Prerequisites

- Node.js (with `npm` or `yarn`)
- A modern browser

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/chat-app.git
   cd server
   npm run start
   ```
