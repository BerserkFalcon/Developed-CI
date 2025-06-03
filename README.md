# Coding Quiz

## Overview
The Coding Quiz is a full-stack web application designed to test users' knowledge of programming concepts. It features a React-based frontend, a Node.js/Express backend, and MongoDB for data storage. The application allows users to take quizzes, view their scores, and retake quizzes.

## Features
- **Frontend**: Built with React and Vite for a fast and modern user experience.
- **Backend**: Powered by Express.js and MongoDB for robust data handling.
- **Database**: MongoDB stores quiz questions and user data.
- **Testing**: Includes Cypress for end-to-end and component testing.
- **Development Tools**: TypeScript for type safety and Vitest for unit testing.

## Prerequisites
- Node.js (v16 or later)
- MongoDB (running locally or accessible via a URI)

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install dependencies for both the server and client:
   ```bash
   npm install
   ```

## Usage
### Development
To start the development environment:
```bash
npm run develop
```
This will concurrently run the server and client in watch mode.

### Seeding the Database
To populate the database with sample quiz questions:
```bash
npm run seed
```

### Running Tests
- Run all tests:
  ```bash
  npm test
  ```
- Open the Cypress GUI for interactive testing:
  ```bash
  npm run test-gui
  ```

### Building for Production
To build the application for production:
```bash
npm run build
```



## Environment Variables
Create a `.env` file in the `server` directory with the following content:
```
MONGODB_URI='mongodb://127.0.0.1:27017/techquiz'
```
