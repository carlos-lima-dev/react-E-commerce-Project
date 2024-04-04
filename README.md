# React Final Project Edit

This repository contains the source code for the final project, which consists of a backend and a frontend developed in Node.js and React.

## Getting Started

### Prerequisites

Before you begin, make sure you have Node.js installed on your machine. You can download and install it from the [official Node.js website](https://nodejs.org/).

### Backend Configuration

1. Navigate to the backend directory:

   ```bash
   cd backend
   cd server
   ```

2. Copy the `.env` file provided via private message and paste it into this directory. This file contains sensitive environment variables and should be kept secure.

3. Install backend dependencies:

   ```bash
   npm install
   ```

4. Start the backend server in development mode:
   ```bash
   npm run dev
   ```

### Frontend Configuration

1. Navigate to the frontend directory:

   ```bash
   cd frontend
   ```

2. Install frontend dependencies:

   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm run dev
   ```

### Important Notes

- In the project, you can also use the route /admin to log in to the /dashboard. Only users with the role ADMIN will be allowed to access /dashboard. To access the dashboard, users must first sign in to the page and then log in as an admin.

- FIGMA - https://www.figma.com/file/W0O15M7f4XyaroPILTqKtQ/3legant-E-Commerce-UI-Design-Template-(Community)-(Copy)-(Copy)?node-id=3%3A674&mode=dev

- Ensure that the environment variables contained in the `.env` file are configured correctly before starting the backend server. These variables are essential for the proper execution of the application.
- Avoid versioning the `.env` file in Git. Make sure to add it to the `.gitignore` file to prevent it from being included in commits.
