Create the Database Table

CREATE DATABASE labexam;
USE labexam;

CREATE TABLE books (
    book_id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255),
    author VARCHAR(255),
    genre VARCHAR(100),
    price DOUBLE,
    published_year INT
);

INSERT INTO books (title, author, genre, price, published_year) VALUES
('Book 1', 'Author 1', 'Fiction', 450.00, 2015),
('Book 2', 'Author 2', 'Science', 550.00, 2018),
('Book 3', 'Author 3', 'History', 300.00, 2020);


OUTPUT

  "title": "Updated Book Title",
  "author": "Updated Author",
  "genre": "Updated Genre",
  "price": 500.0,
  "publishedYear": 2022
