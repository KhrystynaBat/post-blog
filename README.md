# Post Blog Project

## Overview

"Post Blog" is a blog management system developed using Node.js with Express and MongoDB. It allows users to create, edit, and view blog posts.

## Technologies

- **Node.js:** A JavaScript runtime for building server-side applications.
- **Express.js:** A web application framework for Node.js.
- **MongoDB:** A NoSQL database for storing data.
- **EJS:** A templating language for generating HTML markup with JavaScript.
- **Mongoose:** An Object Data Modeling (ODM) library for MongoDB and Node.js.
- **Method-Override:** A middleware used to enable HTTP verb such as PUT or DELETE in places where the client doesn't support it.

## Setup

### Environment Setup

1. Ensure that Node.js and MongoDB are installed on your system.

### Dependencies

1. Run `npm install` to install all required packages including Express, Mongoose, and others.

### Environment Variables

1. Create a `.env` file in the project root directory.
2. Set `MONGO_URL` for your MongoDB connection.
3. Optionally, set `PORT` for the server port (e.g., 3000).

## Running the Application

1. Clone or download the project from GitHub to your local machine.
2. Install Node.js if it's not already installed.
3. Open the command line and navigate to the project directory.
4. Run `npm install` to install all required dependencies.
5. Set up your own MongoDB database and obtain the connection string.
6. Add your MongoDB connection string as `MONGO_URL` in the `.env` file. Optionally, specify a `PORT` variable.
7. Start the application by typing `npm run dev` in the command line.
8. Open a web browser and visit `localhost:3000` (or the port you specified) to use the application.
