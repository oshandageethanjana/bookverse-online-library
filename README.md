# BookVerse

BookVerse is a responsive web-based book discovery and library management system built with HTML, JavaScript, PHP, and MySQL. The system allows users to browse books, fetch book data, manage favorites, and use basic authentication features through a simple and user-friendly interface.

## Project Overview

BookVerse is designed as a modern online book platform where users can explore books and save their favorite selections. The project includes a frontend interface, backend PHP endpoints, database integration, and PWA support through a web manifest file.

## Key Features

- Responsive book browsing interface
- Book data fetching functionality
- User authentication system
- Favorite books management
- MySQL database integration
- PHP backend API handling
- Proxy support for external requests
- Progressive Web App support using `manifest.json`
- Clean and organized project structure

## Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- MySQL
- XAMPP / Apache Server
- JSON
- Progressive Web App Manifest

## Project Structure

```bash
BookVerse/
├── index.html          # Main user interface
├── script.js           # Frontend logic and interactions
├── db_connect.php      # Database connection configuration
├── auth.php            # User authentication handling
├── fetch_books.php     # Fetch books from API or backend source
├── get_books.php       # Retrieve book data from the system
├── favorites.php       # Add, remove, and manage favorite books
├── proxy.php           # Proxy handler for API requests
├── database.sql        # MySQL database structure
└── manifest.json       # PWA configuration
```

## Installation Guide

### 1. Clone the repository

```bash
git clone https://github.com/your-username/bookverse-online-library.git
```

### 2. Move the project to XAMPP

Copy the project folder into the XAMPP `htdocs` directory:

```bash
C:/xampp/htdocs/bookverse-online-library
```

### 3. Start Apache and MySQL

Open XAMPP Control Panel and start:

```bash
Apache
MySQL
```

### 4. Import the database

1. Open phpMyAdmin.
2. Create a new database.
3. Import the `database.sql` file.
4. Update the database name, username, and password inside `db_connect.php` if needed.

### 5. Run the project

Open the browser and visit:

```bash
http://localhost/bookverse-online-library/
```

## Database Configuration

Update `db_connect.php` according to your local environment:

```php
$host = "localhost";
$username = "root";
$password = "";
$database = "your_database_name";
```

## Main Functional Modules

### Authentication

The `auth.php` file handles user login, registration, and authentication-related backend logic.

### Book Fetching

The `fetch_books.php` and `get_books.php` files are used to load and retrieve book data for the application.

### Favorites

The `favorites.php` file allows users to save, view, and manage their favorite books.

### Proxy Handling

The `proxy.php` file helps manage external API requests and avoid common browser-side request issues.

## Future Improvements

- Add an admin dashboard for book management
- Add advanced search and category filters
- Add user profile management
- Add book reviews and ratings
- Improve SEO metadata
- Add deployment support for a live server

## Author

Developed by Oshanda Geethanjana.

## License

This project is open-source and available for educational and personal portfolio use.
