# Library Management System (C++)

A simple **console-based Library Management System** implemented in C++ using Object-Oriented Programming (OOP) concepts.

## Overview

This project simulates a basic library system where registered users can:
- Log in with a predefined name and ID
- Add new books
- View all books
- Search for a book by ID
- Sort books by ID
- Exit the program

The system supports up to **100 books** and uses **bubble sort** to organize books by their ID.

---

## Features

| Feature              | Description |
|----------------------|-----------|
| **User Login**       | Validates user with name & ID from a hardcoded list |
| **Add Book**         | Add book title, author, and unique ID |
| **Display Books**    | Shows all added books with details |
| **Search by ID**     | Find a specific book using its ID |
| **Sort by ID**       | Sorts all books in ascending order by ID |
| **Recursive Retry**  | Allows retry on failed login or search |

---

## How to Run

1. Compile the code using a C++ compiler:
   ```bash
   g++ library.cpp -o library
