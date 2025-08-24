# Books Directory CRUD App

A simple full-stack CRUD application to manage a collection of books using Node.js, Express, MongoDB, and a basic frontend.

## Features

- Create, Read, Update, and Delete (CRUD) book records
- RESTful API endpoints built with Express and Mongoose
- Persistent storage with MongoDB
- Frontend interface to add, edit, delete, and search books
- Responsive design with a dark theme and green-blue gradient accents
- Search books by title or author dynamically

## Technologies Used

- Node.js
- Express.js
- MongoDB & Mongoose
- HTML, CSS, JavaScript (Vanilla)
- Nodemon (for development)

## Project Structure

- `index.js`: Main server file defining API routes and MongoDB connection
- `models/Book.js`: Mongoose schema and model for book documents
- `public/`: Contains frontend static files
  - `index.html`: Frontend user interface
  - `styles.css`: CSS styling for frontend

## API Endpoints

| Method | Endpoint       | Description                |
|--------|----------------|----------------------------|
| GET    | /books         | Get all books              |
| GET    | /books/:id     | Get book by ID             |
| POST   | /books         | Add a new book             |
| PUT    | /books/:id     | Update a book by ID        |
| DELETE | /books/:id     | Delete a book by ID        |

## Usage

On the frontend at `http://localhost:3000/`, you can:

- Add a new book using the form
- View the list of all books
- Search books by title or author dynamically
- Edit or delete existing books

