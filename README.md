# Book and Movie Search API

This is a simple Express.js API that provides endpoints to search for books and movies. It allows users to filter results based on various criteria such as name, author, category (for books), director, and genre (for movies).

## Installation

1. Clone this repository:

   ```bash
   git clone <repository-url>
cd <project-directory>

npm install

npm start

# Endpoints

## GET /books

- **Query Parameters:**
  - `name`: Filter books by name
  - `author`: Filter books by author
  - `category`: Filter books by category

## GET /movies

- **Query Parameters:**
  - `name`: Filter movies by name
  - `director`: Filter movies by director
  - `genre`: Filter movies by genre


## Example 

## Books
curl http://localhost:8090/books?author=Harper%20Lee

## Movies 
curl http://localhost:8090/movies?director=Christopher%20Nolan
