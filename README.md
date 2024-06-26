﻿# Customer Management System (CMS)

## Overview

The Customer Management System (CMS) is a full-stack web application that allows users to perform CRUD (Create, Read, Update, Delete) operations on customer records. The backend is built with Node.js and Express, connected to a MongoDB database. The frontend is a React application.

## Features
- Add, update, delete, and list customers
- Search functionality
- Protected routes for managing customer data
- Responsive design

## Technologies Used

### Backend
- Node.js
- Express
- MongoDB
- Mongoose

### Frontend
- React
- Axios
- React Router
- React Toastify for notifications
- CSS

### Search
- Search is implemented only in frontend.

### Db config
- Create a .env file in the root and set the connection string eg: MONGO_URI='your connection string'

## Getting Started

### Clone the repository
```bash
https://github.com/hariharanks/CMS.git
cd cms

npm i

Running MongoDB
mongod

Running Backend
node server.js

Running frontend
npm start
