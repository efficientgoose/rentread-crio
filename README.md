## Overview

A RESTful API service built using Spring Boot to manage an online Book Rental System while using MySQL to persist the data.

## Features

- **Authentication and Authorization**:
  - Implemented using Basic Auth with two roles: USER and ADMIN.
- **User Management**:
  - User registration with email, password (encrypted using BCrypt), first name, last name, and role (defaulted to "USER" if not specified).
  - User login using email and password.
- **Book Management**:
  - Store and manage book details such as title, author, genre, and availability status.
  - Browse all available books (accessible to any user).
  - Create, update and delete books (accessible only to the administrator).
- **Rental Management**:
  - Rent books with validation to limit users to a maximum of two active rentals.
  - Return rented books.

