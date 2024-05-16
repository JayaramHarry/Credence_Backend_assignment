# Backend Assignment

This is a Node.js backend application for managing a collection of books using a REST API. It allows users to perform CRUD (Create, Read, Update, Delete) operations on the book data stored in a MongoDB database.

## Features

- RESTful API for managing books
- Create, Read, Update, and Delete operations
- MongoDB database integration
- Express.js for routing
- Mongoose for MongoDB object modeling

## Requirements

- Node.js
- MongoDB

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/JayaramHarry/Credence_Backend_assignment
   ```

2. Navigate to the project directory:

   ```bash
   cd Credence_Backend-assignment
   ```

3. Install dependencies:

   ```bash
   npm install
   npm init -y
   ```

4. Set up MongoDB:
   - Install MongoDB on your local machine or use a cloud-hosted MongoDB service like MongoDB Atlas.
   - Update the MongoDB connection string in `server.js` to point to your MongoDB instance.

5. Start the server:

   ```bash
   node server.js
   ```

6. The server should now be running locally on port 3000 by default.

## Usage

You can interact with the API using tools like Postman or curl. Here are some example API endpoints:

- `POST /books`: Create a new book.
- `GET /books`: Retrieve all books.
- `GET /books/:id`: Retrieve a specific book by ID.
- `PUT /books/:id`: Update a specific book by ID.
- `DELETE /books/:id`: Delete a specific book by ID.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, feel free to open an issue or submit a pull request.

