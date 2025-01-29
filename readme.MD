# My Library Project  

My Library Project is a simple web application built with **Flask** and **SQLAlchemy** that allows users to manage a personal book collection. With this application, users can add books with their title, author, and rating, view all saved books, update ratings, and delete books from the collection.  

This project is designed as an introduction to Flask and basic database management with **SQLite**.  

---

## Technologies Used  

This project is built using the following technologies:  

- **Python** – Core programming language  
- **Flask** – Web framework  
- **Flask-SQLAlchemy** – ORM for database interactions  
- **SQLite** – Lightweight database  
- **HTML + Jinja2** – Template rendering for dynamic web pages  

---

## Features  

The application includes the following features:  

- **Add new books** – Enter book details including title, author, and rating  
- **View all books** – Display a list of all saved books in the database  
- **Edit book rating** – Update the rating of any book in the collection  
- **Delete books** – Remove books from the collection permanently


---

## Project Structure  

```
my-library-project/
│── templates/        # HTML templates for rendering pages  
│   ├── index.html    # Homepage displaying all books  
│   ├── add.html      # Page for adding new books  
│   ├── edit.html     # Page for editing book ratings  
│── main.py           # Flask application  
│── README.md         # Project documentation  
│── all_books.db      # SQLite database file (created automatically)  
```

---

## How the Application Works  

1. **Homepage**
   - Displays a list of all books stored in the database  
   - Provides options to edit or delete books  

2. **Add a New Book**  
   - Users can submit a form to add a new book with its title, author, and rating  

3. **Edit a Book’s Rating**  
   - Allows users to modify the rating of a selected book  

4. **Delete a Book**  
   - Removes a book from the database permanently  

---
