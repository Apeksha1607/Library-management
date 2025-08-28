

# Book Management System in C

A simple console-based Book Management System implemented in C, allowing you to add, search, update, delete, and display book records in memory.

---

## Features

* Add new books with ID, title, author, and price
* Search for a book by its ID
* Update book details by ID
* Delete a book by ID
* Display all stored books
* Interactive menu-driven interface

---

## How to Run

1. Download or clone the repository containing `book_management.c`.

2. Compile the source code using a C compiler (e.g., GCC):

   ```bash
   gcc book_management.c -o book_management
   ```

3. Run the executable:

   ```bash
   ./book_management
   ```

4. Use the menu options to manage books.

---

## Limitations

* This version stores data only in memory and does **not** persist data between runs.
* Maximum number of books is fixed to 100 (`MAX_BOOKS`).

---

## Sample Usage

```
Book Management System (No File Handling)
1. Add Book
2. Search Book
3. Update Book
4. Delete Book
5. Display All Books
0. Exit
Enter your choice: 1
Enter Book ID: 101
Enter Book Title: The Great Gatsby
Enter Book Author: F. Scott Fitzgerald
Enter Book Price: 12.99
Book added successfully!

Enter your choice: 5

--- All Books ---
ID: 101, Title: The Great Gatsby, Author: F. Scott Fitzgerald, Price: 12.99
-------------------

Enter your choice: 0
Exiting program.
```

---

## Future Enhancements

* Add file handling to save and load book data persistently
* Implement sorting and filtering of books
* Add user authentication for administrative operations

---


