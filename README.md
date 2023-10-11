# Blog-Site-Backend-

This repository contains the backend code for a simple blog website that allows users to signup, login, write blogs, edit their blogs, and delete them. The application is built using a REST API architecture and MongoDB as the database.

Table of Contents :-

Technologies Used
Getting Started
Prerequisites
Usage
Authentication
Blog Operations
API Endpoints
Contributing

Technologies Used :-

Node.js: The server-side runtime environment.
Express.js: A web application framework for Node.js.
MongoDB: A NoSQL database for storing user data and blog posts.
Mongoose: An ODM (Object Data Modeling) library for MongoDB.
REST API: For handling client-server communication.
JWT (JSON Web Tokens): For user authentication and authorization.

Getting Started
Prerequisites:-

Node.js installed on your system.
MongoDB database up and running.
An understanding of RESTful API concepts.

Clone this repository:

bash
Copy code
git clone https://github.com/your-username/blog-website-backend.git
cd blog-website-backend
Install the dependencies:


Usage
Authentication :-
Users can sign up for an account and log in to access their accounts.
Authentication is based on JWT tokens. Users receive a token upon successful login, which is required to access protected routes.

Blog Operations :-
Authenticated users can create, read, update, and delete their blog posts.
Blogs are stored in the MongoDB database.

API Endpoints:-
POST /api/signup: Create a new user account.
POST /api/login: Authenticate and receive a JWT token.
GET /api/blogs: Retrieve a list of blogs.
GET /api/blogs/:id: Retrieve a specific blog by ID.
POST /api/blogs: Create a new blog.
PUT /api/blogs/:id: Update a specific blog by ID.
DELETE /api/blogs/:id: Delete a specific blog by ID.
For more details on the API endpoints and request/response formats, please refer to the API documentation or the source code.
