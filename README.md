# Customer Management Application

A full-stack web application for managing customer information and their addresses. This project consists of a React frontend client and a Node.js/Express backend server with SQLite database.

## Project Structure

```
customer-management-app/
├── client/             # React frontend application
├── server/             # Node.js/Express backend server
├── index.js            # Root project file
└── package.json        # Root project configuration
```

## Features

- Customer information management (create, read, update, delete)
- Multiple address management for each customer
- Search and filter functionality
- Responsive user interface
- RESTful API endpoints
- SQLite database for data persistence

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository
2. Install dependencies for the root project:
   ```
   npm install
   ```
3. Install dependencies for the client:
   ```
   cd client
   npm install
   ```
4. Install dependencies for the server:
   ```
   cd server
   npm install
   ```

## Running the Application

### Development Mode

To run both client and server concurrently:

```
npm run dev
```

This will start:
- React client on http://localhost:3000
- Express server on http://localhost:5000

### Running Separately

To run only the client:
```
npm run client
```

To run only the server:
```
npm run server
```

## API Documentation

The API endpoints are available at http://localhost:5000/api

For detailed API documentation, please refer to the [server README](./server/README.md).

## Client Application

For details about the client application, please refer to the [client README](./client/README.md).

## License

MIT