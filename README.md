# laravel-project-testing

This is a Laravel project for testing purposes.

## Features

*   **Authentication:** Secure user authentication and authorization.
*   **Account Management:** Functionality for creating, reading, updating, and deleting user accounts.
*   **Simple, fast routing engine.**
*   **Powerful dependency injection container.**
*   **Multiple back-ends for session and cache storage.**
*   **Expressive, intuitive database ORM.**
*   **Database agnostic schema migrations.**
*   **Robust background job processing.**
*   **Real-time event broadcasting.**

## Technologies Used

*   Laravel
*   PHP
*   Composer
*   Vite

## Getting Started

### Prerequisites

*   PHP 8.1 or higher
*   Composer
*   Node.js
*   NPM

### Installation

1.  Clone the repository:
    ```bash
    git clone https://github.com/toufikforyou/laravel-project-testing.git
    ```
2.  Install dependencies:
    ```bash
    composer install
    ```
3.  Create a copy of your .env file
    ```bash
    cp .env.example .env
    ```
4.  Generate an app encryption key
    ```bash
    php artisan key:generate
    ```
5. Run the database migrations
    ```bash
    php artisan migrate
    ```
6. Install npm dependencies
    ```bash
    npm install
    ```
7. Start the development server
    ```bash
    npm run dev
    ```

## Contributing

We welcome contributions from the community. Please read our [contributing guidelines](docs/contributing.md) to get started. We also have a [Code of Conduct](docs/CODE_OF_CONDUCT.md) that we expect all contributors to adhere to.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.