[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19831684&assignment_repo_type=AssignmentRepo)
# MERN Stack Integration Assignment

This assignment focuses on building a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that demonstrates seamless integration between front-end and back-end components.

## Assignment Overview

You will build a blog application with the following features:
1. RESTful API with Express.js and MongoDB
2. React front-end with component architecture
3. Full CRUD functionality for blog posts
4. User authentication and authorization
5. Advanced features like image uploads and comments

## Project Structure

cd into the midecare folder

```
medicare/
├── client/                 # React front-end
│   ├── public/             # Static files
│   ├── src/                # React source code
│   │   ├── components/     # Reusable components
│   │   ├── pages/          # Page components
│   │   ├── hooks/          # Custom React hooks
│   │   ├── services/       # API services
│   │   ├── context/        # React context providers
│   │   └── App.jsx         # Main application component
│   └── package.json        # Client dependencies
├── server/                 # Express.js back-end
│   ├── config/             # Configuration files
│   ├── controllers/        # Route controllers
│   ├── models/             # Mongoose models
│   ├── routes/             # API routes
│   ├── middleware/         # Custom middleware
│   ├── utils/              # Utility functions
│   ├── server.js           # Main server file
│   └── package.json        # Server dependencies
└── README.md               # Project documentation
```

## Getting Started

1. Accept the GitHub Classroom assignment invitation
2. Clone your personal repository that was created by GitHub Classroom
3. Follow the setup instructions in the `Week4-Assignment.md` file
4. Complete the tasks outlined in the assignment

## Files Included

- `Week4-Assignment.md`: Detailed assignment instructions
- Starter code for both client and server:
  - Basic project structure
  - Configuration files
  - Sample models and components

## Requirements

- Node.js (v18 or higher)
- MongoDB (local installation or Atlas account)
- npm or yarn
- Git

## Submission

Your work will be automatically submitted when you push to your GitHub Classroom repository. Make sure to:

1. Complete both the client and server portions of the application
2. Implement all required API endpoints
3. Create the necessary React components and hooks
4. Document your API and setup process in the README.md
5. Include screenshots of your working application

## Resources

- [MongoDB Documentation](https://docs.mongodb.com/)
- [Express.js Documentation](https://expressjs.com/)
- [React Documentation](https://react.dev/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Mongoose Documentation](https://mongoosejs.com/docs/) 





# 🔄 Week 4: Deep Dive into MERN Stack Integration

## 🚀 Objective
Build a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that demonstrates seamless integration between front-end and back-end components, including database operations, API communication, and state management.

## 📂 Tasks

### Task 1: Project Setup
- Set up a project with a clear directory structure for both client and server
- Configure MongoDB connection using Mongoose
- Set up Express.js server with necessary middleware
- Create a React front-end using Vite and configure proxy for API calls
- Implement environment variables for configuration management

### Task 2: Back-End Development
- Design and implement a RESTful API for a blog application with the following endpoints:
  - `GET /api/posts`: Get all blog posts
  - `GET /api/posts/:id`: Get a specific blog post
  - `POST /api/posts`: Create a new blog post
  - `PUT /api/posts/:id`: Update an existing blog post
  - `DELETE /api/posts/:id`: Delete a blog post
  - `GET /api/categories`: Get all categories
  - `POST /api/categories`: Create a new category
- Create Mongoose models for `Post` and `Category` with proper relationships
- Implement input validation using a library like Joi or express-validator
- Add error handling middleware for API routes

### Task 3: Front-End Development
- Create React components for:
  - Post list view
  - Single post view
  - Create/edit post form
  - Navigation and layout
- Implement React Router for navigation between different views
- Use React hooks for state management (useState, useEffect, useContext)
- Create a custom hook for API calls

### Task 4: Integration and Data Flow
- Implement API service in React to communicate with the back-end
- Set up state management for posts and categories
- Create forms with proper validation for creating and editing posts
- Implement optimistic UI updates for better user experience
- Handle loading and error states for API calls

### Task 5: Advanced Features
- Add user authentication (registration, login, protected routes)
- Implement image uploads for blog post featured images
- Add pagination for the post list
- Implement searching and filtering functionality
- Add comments feature for blog posts

## 🧪 Expected Outcome
- A fully functional MERN stack blog application
- Proper integration between MongoDB, Express.js, React.js, and Node.js
- Clean code organization with separation of concerns
- Responsive UI with good user experience
- Implementation of at least one advanced feature

## 🛠️ Setup
1. Make sure you have Node.js (v18+) and MongoDB installed
2. Clone the starter code repository
3. Install server dependencies:
   ```
   cd server
   npm install
   ```
4. Install client dependencies:
   ```
   cd client
   npm install
   ```
5. Set up environment variables as described in the `.env.example` files
6. Start the development servers:
   ```
   # In the server directory
   npm run dev
   
   # In the client directory
   npm run dev
   ```

## ✅ Submission Instructions
1. Accept the GitHub Classroom assignment invitation
2. Clone your personal repository that was created by GitHub Classroom
3. Complete all the tasks in the assignment
4. Commit and push your code regularly to show progress
5. Include in your repository:
   - Complete client and server code
   - `.env.example` files for both client and server
   - A comprehensive README.md with:
     - Project overview
     - Setup instructions
     - API documentation
     - Features implemented
     - Screenshots of the application
6. Your submission will be automatically graded based on the criteria in the autograding configuration
7. The instructor will review your submission after the autograding is complete 