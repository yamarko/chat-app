# Fullstack Chat-App

A fullstack chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) with real-time messaging, automatic replies, and user notifications.

Deployed on Render. You can access it here: [link](https://chat-app-65ee.onrender.com).

## Tech Stack

### MERN:

- **MongoDB** - Database to store chat data and user information.
- **Express.js** - Web framework to build the backend API.
- **React.js** - Frontend library for building the user interface.
- **Node.js** - JavaScript runtime to power the server-side code.

### Additional Libraries:

- **Axios** - For making HTTP requests to the backend.
- **Zustand** - State management for React.
- **Zenquotes.io** - Quotes API (used instead of quotable.io).
- **React Hot Toast** - For user-friendly notifications.
- **React Router** - For routing and navigation within the app.
- **Multi Avatar** - For displaying multiple avatars in the chat.

## Completed tasks

### Main tasks

- **Page visualization** (my interpretation).
- **3 predefined chats**.
- **Create new chat** (dialog window with the first and last names, the 
both are required). 
- **Update existing chat** (first and last names).
- **Remove existing chat**.
- **Send message** (auto response with **Zenquotes** in 3 sec).
- **Show toast notification with new message**.
- **Chat search** (by first and last names).

### Additional tasks

- **Confirmation before removing the chat**.

## Getting Started

### Configure the .env file

```js
MONGODB_URI=...
PORT=5005

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```