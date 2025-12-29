### Exercise Tracker (React, Express, Mongoose)

## Overview
- This application is developed to track personal workouts as a full-stack solution, with data stored persistently in MongoDB. 
- **React** is used for the user interface, **Mongoose** handles database interactions at the model level, and **Express** manages backend client requests.


## Frontend
- **React** handles the SPA, creating the UI, handling page navigation, etc. 
- Acts as the view, dynamically displaying the exercise documents retrieved from Mongoose, and calling controller methods to add, delete, or update user data.

## Backend
- **Express** acts as the controller, processing requests, sending responses, validating inputs, and interacting directly with Mongoose.
-  **Mongoose** is used as the model, defining schemas and performing CRUD operations on MongoDB documents.
- **Node** hosts both the frontend and backend locally, and handles server tasks.


## Setup Instructions
- To run the application, you must add your own connection string in the configuration file, `./backend/.env`.