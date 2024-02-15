# Library Management System

This is a simple Library Management System implemented in C++ using MySQL database. The system allows administrators to manage books and students, while users can borrow books.

## Prerequisites

- Vs Code/ Dev C++
- MySQL server installed locally
- MySQL Connector/C++ library

## Installation and Setup

1. Install MySQL server on your local machine.
2. Install MySQL Connector/C++ library.
3. Compile the source code using a C++ compiler.
4. Run the compiled executable file.

## Usage

1. Upon launching the application, you will be prompted to choose between Administration and User mode.
2. In Administration mode, you can add books and students to the library database.
3. In User mode, you can search for books and borrow them if available.
4. Exit the application by selecting the 'Exit' option.

## Code Structure

- The `main` function is the entry point of the program.
- `admin`, `display`, `book`, and `user` functions handle various functionalities of the system.
- The `Student` and `Library` classes represent entities in the system.

### Implemented OOP Concepts

- **Encapsulation**: Data members of `Student` and `Library` classes are encapsulated using private access specifiers. Methods are provided for interacting with these data members.
- **Abstraction**: The `Student` and `Library` classes abstract the details of their internal implementation from the rest of the program.
- **Inheritance**: Although not explicitly demonstrated in this version, future enhancements could introduce inheritance, such as creating specialized types of library items.
- **Polymorphism**: While not explicitly demonstrated in this version, polymorphism could be used in future versions to provide different behaviors for various types of library items or users.

## Configuration

- Modify the database connection parameters (`HOST`, `USER`, `PW`, `DB`) according to your MySQL server configuration.
- Ensure that the MySQL server is running before launching the application.

Feel free to contribute to the project by submitting pull requests or reporting issues. Thank you for using our Library Management System!
