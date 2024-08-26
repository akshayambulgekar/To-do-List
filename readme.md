# To-Do List Application

A simple RESTful API for a To-Do list application built using Node.js, Express, and MongoDB.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [API Endpoints](#api-endpoints)
  

## Introduction

This project is a basic To-Do list application that allows users to perform CRUD (Create, Read, Update, Delete) operations on tasks. It is designed to demonstrate how to create a RESTful API using Node.js, Express, and MongoDB.

## Features

- Create a new task
- Retrieve all tasks
- Retrieve a single task by its ID
- Update an existing task
- Delete a task

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose (ODM for MongoDB)
- dotenv (for environment variable management)

## Installation

### Prerequisites

Before you begin, ensure you have the following installed on your system:

- Node.js (v12 or higher)
- npm (Node Package Manager)
- MongoDB (either local installation or use MongoDB Atlas for cloud-based MongoDB)

### Steps to Set Up the Project

1. **Clone the Repository**

   ```bash
   git clone https://github.com/akshayambulgekar/To-do-List.git
   cd todo-list-app

2. **Install Dependencies**
   ```bash
      npm install

3. **Set Up Environment Variables**
   Create a .env file in the root directory of the project and add the following environment variable:
   ```bash
   MONGODB_URI=mongodb://localhost:27017/todo-list-app
   PORT=3000

4. **Ensure MongoDB is Running**
   For a local MongoDB installation, ensure the MongoDB service is running. Open a terminal and start the MongoDB server:
   ```bash
      mongod

5. **Running the Application**
   To start the application, run:
   ```bash
      npm start
  
  Or, if you prefer using nodemon for development (auto-restarts the server on changes):
  
     npm run dev


6. **API Endpoints**
   Here are the available API endpoints:
   - GET /api/tasks: Retrieve a list of all tasks.
   - GET /api/tasks/: Retrieve a single task by its ID.
   - POST /api/tasks: Create a new task.
   - PUT /api/tasks/: Update an existing task.
   - DELETE /api/tasks/: Delete a task.
