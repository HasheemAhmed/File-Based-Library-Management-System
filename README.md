

# 📚 Files Based Library Management System 📚

## Overview

This project implements a simple Library Management System using Python and file handling. It supports basic functionalities such as adding books, genres, and users, borrowing and returning books, and viewing the current status of books and users. The system uses text files to store all the data, ensuring persistence even after the program is closed.

## Features

- 📖 **Add Books**: Add new books with unique IDs, titles, authors, and genres.
- 📂 **Add Genres**: Add new genres to categorize books.
- 👤 **Add Users**: Add new users with unique IDs, names, emails, and phone numbers.
- 📚 **View Books**: Display all books in the library with their details.
- 🗂️ **View Genres**: Display all available genres.
- 👥 **View Users**: Display all registered users with their details.
- 🔍 **View Books Using Filter**: Filter and view books based on genre, author, or availability.
- 📅 **Borrow Book**: Borrow a book by specifying the user ID and the number of days for borrowing.
- 📦 **Return Book**: Return a borrowed book using the transaction ID.
- 📝 **View Borrowed Books**: View all transactions, including borrowed books and their return dates.

## File Structure 📁

- **Books.txt**: Stores book details in the format `BookId,Title,Author,Genre,Availability`.
- **Genre.txt**: Stores the list of genres.
- **Users.txt**: Stores user details in the format `UserId,Name,Email,Phone`.
- **Transaction.txt**: Stores transaction details in the format `TransactionId,BookId,UserId,BorrowDate,ReturnDate`.
- **BookIds.txt**: Stores the IDs of all books to ensure uniqueness.
- **UsersIds.txt**: Stores the IDs of all users to ensure uniqueness.
- **TransIds.txt**: Stores the IDs of all transactions to ensure uniqueness.

## How to Run 🚀

1. Ensure you have Python installed on your system.
2. Download or clone the repository.
3. Navigate to the project directory.


## Usage 🛠️

Upon running the script, you will be presented with a menu of options:

```plaintext
1. Add a Book
2. Add Genre
3. Add User
4. View Books
5. View Genre
6. View Users
7. View Books Using Filter
8. Borrow Book
9. View Borrow Books
10. Return a Book
11. Exit
```

Follow the prompts to interact with the system. Below are some examples of how to use the system:

### Adding a Book 📖

- Select option `1`.
- Enter a unique book ID.
- Enter the book title.
- Enter the book author.
- Select a genre from the available genres.

### Adding a Genre 📂

- Select option `2`.
- Enter the genre name.

### Adding a User 👤

- Select option `3`.
- Enter a unique user ID.
- Enter the user name.
- Enter a valid email address.
- Enter a valid phone number.

### Borrowing a Book 📅

- Select option `8`.
- Enter a unique transaction ID.
- Enter the book ID you want to borrow.
- Enter the user ID borrowing the book.
- Enter the number of days for borrowing.

### Returning a Book 📦

- Select option `10`.
- Enter the transaction ID for the borrowed book.

### Viewing Books Using Filter 🔍

- Select option `7`.
- Choose to filter by genre, author, or availability.

## Note 📝

- Ensure to enter valid inputs as per the prompts.
- The system will handle invalid inputs and provide appropriate error messages.
- Data persistence is maintained using text files, ensuring that data is not lost between sessions.

## License 📄

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

Hasheem Ahmed
