# Laravel Notes Application

<p align="center">
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" alt="Laravel Logo" width="400">
    </a>
</p>

## Overview
The Laravel Notes Application is a simple yet powerful web application built using the Laravel framework. It allows users to create, read, update, and delete notes efficiently. This application serves as a great starting point for anyone looking to learn Laravel or build a note-taking application.

## Features
- **CRUD Functionality**: Create, read, update, and delete notes with ease.
- **User-Friendly Interface**: A clean and intuitive user interface built with Bootstrap.
- **Routing**: Utilizes Laravel's routing capabilities to manage different views and actions.
- **Validation**: Implements request validation to ensure data integrity.
- **Database Migrations**: Uses Laravel migrations to manage database schema changes.
- **Environment Configuration**: Easy setup with environment variables for configuration.

## Requirements
- **PHP Version**: ^8.2
- **Laravel Framework**: ^12.0
- **Database**: MySQL or SQLite (configured in the `.env` file)

## Installation
Follow these steps to set up the application on your local machine:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/angie-kinya/laravel-notes.git
   cd my-laravel-app
   ```

2. **Install Dependencies**:
   Run the following command to install the required PHP packages:
   ```bash
   composer install
   ```

3. **Set Up Environment Variables**:
   Copy the example environment file and configure your settings:
   ```bash
   cp .env.example .env
   ```

4. **Generate Application Key**:
   Generate a unique application key:
   ```bash
   php artisan key:generate
   ```

5. **Run Migrations**:
   Set up the database by running the migrations:
   ```bash
   php artisan migrate
   ```

6. **Start the Development Server**:
   Launch the application using the built-in server:
   ```bash
   php artisan serve
   ```

7. **Access the Application**:
   Open your web browser and navigate to `http://127.0.0.1:8000`.

## Usage
Once the application is running, you can:
- **Create a Note**: Navigate to the "Create Note" button and fill out the form on a new page.
- **View Notes**: Access the "Notes" page to see all your notes either separately or in a list.
- **Edit a Note**: Click on a note to edit its content.
- **Delete a Note**: Remove a note from the list when it's no longer needed.

## Directory Structure
- **app/**: Contains the application logic, including models and controllers.
- **resources/**: Contains views (including Blade layouts) and assets (CSS, JavaScript).
- **routes/**: Defines the application's routes.
- **database/**: Contains migrations and seeders for database management.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- [Laravel](https://laravel.com) for providing a robust framework.
- [Bootstrap](https://getbootstrap.com) for the responsive design components.
