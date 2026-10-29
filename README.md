# Library Management System (Python + SQLite)

A beginner-friendly, menu-based Library Management System built using Python and SQLite. This is suitable for learning and as a basic college project.

## Features

- Add books with title, author, and quantity
- View all books
- Search by title or author
- Issue a book to a student
- Return an issued book
- View currently issued books
- Automatically creates the SQLite database and tables

## Requirements

- Python 3.8 or newer recommended
- No external Python packages required
- No XAMPP or internet connection required

## Project structure

```text
LibraryManagementSystem/
├── main.py
└── README.md
```

When the program runs for the first time, it creates `library.db` automatically in the same folder.

## How to run

1. Install Python from https://www.python.org/downloads/ if it is not installed.
2. Download or clone this repository.
3. Open a terminal or Command Prompt inside the project folder.
4. Run:

   ```bash
   python main.py
   ```

   On some Windows systems, use:

   ```bash
   py main.py
   ```

5. Select an option from the menu.

## How to use

1. Choose **Add Book** and enter the title, author, and quantity.
2. Choose **View All Books** to check available books.
3. Choose **Issue Book**, enter the Book ID and student name.
4. Choose **View Issued Books** to see books that have not been returned.
5. Choose **Return Book** and enter the Issue ID.
6. Choose **Exit** to close the program.

## Database

SQLite is included with standard Python installations. The program uses two tables:

- `books`: stores book title, author, and available quantity.
- `issued_books`: stores the book, student name, issue date, and return date.

The `library.db` file contains your saved data. Keep it if you want to preserve the records. Do not upload real students' personal data to a public repository.

## GitHub upload steps (website method)

1. Sign in at https://github.com/
2. Click **+** → **New repository**.
3. Enter repository name: `LibraryManagementSystem`.
4. Add a short description, such as `Beginner Python Library Management System using SQLite`.
5. Choose **Public** or **Private**, then click **Create repository**.
6. Click **Add file** → **Upload files**.
7. Upload `main.py` and `README.md`, then click **Commit changes**.

## Possible future improvements

- Update and delete books
- Student records
- Due dates and late-return fine
- Graphical interface using Tkinter
- Login for librarian/admin

## Learning topics

Python functions, loops, conditionals, exception handling, SQL queries, SQLite, and CRUD operations.

## License

You may use and modify this project for learning and college practice.
