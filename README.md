

# Chat Application

This is a simple chat application built using Node.js for the backend and Angular for the frontend. It allows users to sign up, log in, and exchange messages in different chat rooms.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration and authentication
- Real-time chat in different rooms
- History of messages in each chat room
- User typing indicator
- User join/leave notifications

## Installation

### Backend (Node.js)

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the backend folder:

   ```bash
   cd chat-frontend
   ```

3. Install the required Node.js packages:

   ```bash
   npm install
   ```

4. Set up the MongoDB database by providing the connection URL in `config/db.js`.

5. Start the Node.js server:

   ```bash
   npm start
   ```

The backend server should now be running on port 3000.

### Frontend (Angular)

1. Navigate to the frontend folder:

   ```bash
   cd chat-frontend
   ```

2. Install the required Angular packages:

   ```bash
   npm install
   ```

3. Start the Angular development server:

   ```bash
   ng serve
   ```

The frontend should be accessible at `http://localhost:4200`.

## Usage

1. Sign up for an account.
2. Log in with your credentials.
3. Join a chat room or create your own.
4. Start sending and receiving messages in real-time.

## Folder Structure

- `backend`: Contains the Node.js backend code.
- `frontend`: Contains the Angular frontend code.


