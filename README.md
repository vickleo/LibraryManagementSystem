# Library Management System

## Overview
The Library Management System is a Java-based application designed to efficiently manage books and library users. The system supports essential operations like adding, removing, searching, and listing books. Additionally, it includes user authentication and a fine calculation system for overdue book returns.

## Features

1. **Book Management:**
   - Add new books to the library.
   - Remove books from the library.
   - Search for books by title.
   - List all available books in the library.

2. **User Management:**
   - Add new users to the system.
   - Authenticate users by username and password.

3. **Fine Calculation System:**
   - Calculate fines for overdue book returns based on a daily fine rate.

4. **Persistence:**
   - Save the library’s state (books and users) to a file upon exit.
   - Load the library’s state from a file upon start.

## How to Use

1. **Clone the Repository:**
   - Clone the repository to your local machine using the following command:
     ```bash
     git clone <repository_url>
     ```

2. **Compile and Run:**
   - Navigate to the project directory and compile the `Library.java` file using your preferred Java IDE or command line.
   - Run the `Library.java` file to start the Library Management System.

3. **Commands:**
   - **ADD:** Add a new book to the library.
   - **REMOVE:** Remove a book by title.
   - **SEARCH:** Search for a book by title.
   - **LIST:** List all books in the library.
   - **ADDUSER:** Add a new user to the system.
   - **AUTHENTICATE:** Authenticate a user by username and password.
   - **FINE:** Calculate the fine for an overdue book.
   - **EXIT:** Save the current state and exit the system.

## Dependencies
- Java Development Kit (JDK) 8 or higher.

## Version Control
This project uses Git for version control. Ensure that each commit is descriptive and accurately reflects the changes made in the project.

## Authors
[Xiangshuai Liu]

## Contact Information
For any questions, please reach out to [xiangshuailiu2026@u.northwestern.edu].
