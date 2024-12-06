
# Library API

>## Overview
>
>The Library API is a PHP-based application designed to manage a library system. Built using the Slim framework, the API provides endpoints for managing library resources such as books, users, and transactions. This project follows a modular and scalable architecture and includes JWT-based authentication for secure access.

## Features

- **User Management**: Add, update, and delete users.
- **Book Management**: CRUD operations for library books.
- **Transactions**: Manage borrowing and returning of books.
- **Secure Access**: JSON Web Token (JWT) authentication.
- **Modular Design**: Easily extendable and maintainable codebase.

## Prerequisites

- PHP >= 7.4
- Composer (Dependency Manager)
- MySQL or compatible database
- Web server (e.g., Apache or Nginx)

## Installation

1. **Clone the Repository**:
    ```bash
    git clone <repository_url>
    cd <repository_directory>
    ```

2. **Install Dependencies**:
    Use Composer to install the required PHP packages:
    ```bash
    composer install
    ```

3. **Setup the Database**:
    - Import the SQL schema located in `Lib-API/library (1).sql` into your MySQL database.
    - Configure database credentials in the application.

4. **Configure the Application**:
    - Update the `index.php` or relevant configuration files with your environment-specific settings, including database credentials and JWT secrets.

5. **Run the Application**:
    - Use PHP's built-in server for development:
      ```bash
      php -S localhost:8000 -t public
      ```
    - Alternatively, configure your web server (e.g., Apache or Nginx) to serve the `public` directory.

## Project Structure

- **`public/`**: Entry point for the application.
- **`src/`**: Core application files, including routes, controllers, and middleware.
- **`vendor/`**: Dependencies installed via Composer.
- **`library (1).sql`**: SQL script for database schema.

## Dependencies

The project uses the following key dependencies:

- [Slim Framework](https://www.slimframework.com/): Lightweight framework for building APIs.
- [Firebase PHP-JWT](https://github.com/firebase/php-jwt): Library for handling JWT authentication.
- [FastRoute](https://github.com/nikic/FastRoute): High-performance routing library.

## Usage

- Access the API via `http://localhost:8000` (or your configured domain).
- Use tools like Postman or cURL to interact with the API.
- Include the JWT token in the Authorization header for protected endpoints.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request with a detailed description of your changes.

*## License*

*This project is licensed under the MIT License. See the `LICENSE` file for details.*

## Contact

For issues or inquiries, feel free to reach out via email (Brianraquepo303@gmail.com).
