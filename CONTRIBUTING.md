
# Contribution Guidelines for MindPalace

Welcome to the **MindPalace** project! This document outlines the guidelines for contributing to this project. As a solo developer, these guidelines will help you stay organized and maintain a high standard of code quality.

## Project Overview
**MindPalace** is a memory enhancement tool that utilizes the memory palace technique to help users visualize, memorize, and recall information. The project uses the following technologies:
- **Frontend**: React.js
- **Backend**: Node.js with Express
- **Database**: MongoDB
- **3D Visualization**: Three.js or Babylon.js
- **Authentication**: JWT (JSON Web Tokens)
- **Version Control and Project Management**: GitHub Projects and Boards

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Node.js
- npm (Node Package Manager)
- MongoDB
- Git

### Setting Up the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/mindpalace.git
   cd mindpalace
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   Create a `.env` file in the root directory and add the following:
   ```env
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the development server**:
   ```bash
   npm run dev
   ```

## Project Structure
- **Frontend**: Located in the `client` directory.
- **Backend**: Located in the `server` directory.
- **3D Visualization**: Integrated within the frontend using Three.js or Babylon.js.
- **Authentication**: Implemented using JWT in the backend.

## Contribution Workflow

### 1. Create Issues
Use GitHub Issues to track tasks and bugs. Create an issue for each task or bug before starting work on it.

### 2. Branch Naming
Use the following naming conventions for branches:
- `feature/feature-name` for new features
- `bugfix/bug-description` for bug fixes
- `chore/task-name` for maintenance tasks

### 3. Commit Messages
Write clear and concise commit messages. Follow the convention:
- `feat: description` for new features
- `fix: description` for bug fixes
- `chore: description` for maintenance tasks

### 4. Pull Requests
Even though you are working solo, use pull requests to merge changes. This helps maintain a clear history of changes and allows for code review.

### 5. Code Quality
- Follow the coding standards and best practices for JavaScript, React.js, and Node.js.
- Use ESLint for linting and Prettier for code formatting.
- Write unit tests for critical parts of the application.

### 6. Documentation
- Update the README.md file with any new features or changes.
- Document your code with comments where necessary.

## Project Management
Use GitHub Projects and Boards to manage tasks and track progress. Create a project board with columns such as "To Do," "In Progress," and "Done" to visualize your workflow.

## Communication
As a solo developer, it's essential to keep detailed notes and documentation. Use the GitHub Wiki or a dedicated documentation tool to keep track of your project's progress, decisions, and any challenges you encounter.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.


Source: Conversation with Copilot, 8/9/2024
(1) Node.js + Express + MongoDB example: MERN stack CRUD App - BezKoder. https://www.bezkoder.com/react-node-express-mongodb-mern-stack/.
(2) GitHub - bezkoder/node-express-mongodb: Node.js Restful CRUD API with .... https://github.com/bezkoder/node-express-mongodb.
(3) The ULTIMATE MERN Stack Complete Guide (MongoDB, Express, React, Node.js). https://www.mongodb.com/developer/videos/the-ultimate-mern-stack-complete-guide-mongodb-express-react-node-js-/.
(4) Create a Modern Ecommerce Project with React, NodeJS, Express.js,. https://medium.com/@irenemmassyy/create-a-modern-ecommerce-project-with-react-nodejs-express-js-b6a13cd1f9ca.
(5) This tutorial is a continuation of my node js react project ... - GitHub. https://github.com/codrkai/node_react_mongodb_tutorial.
(6) undefined. https://mdb.link/mern-4nKWREmCvsE.
(7) undefined. https://mdb.link/free-4nKWREmCvsE.
(8) undefined. https://github.com/mongodb-developer/mern-stack-example.
