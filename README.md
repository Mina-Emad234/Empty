# Empty Project

## Project Explanation and Description

Empty is a Laravel-based project template for building scalable web applications. This repository serves as a foundation for PHP development with a focus on clean architecture and best practices.

## Features and Technologies

### Technologies:
- **Backend Framework**: Laravel
- **Language**: PHP
- **Architecture Pattern**: MVC (Model-View-Controller)

### Features:
- RESTful API structure
- Database-agnostic schema migrations
- Built-in authentication system
- Eloquent ORM for database operations
- Powerful routing engine
- Dependency injection container

## How to Run It

### Prerequisites
- PHP 8.0 or higher
- Composer
- MySQL or any supported database
- Git

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Mina-Emad234/Empty.git
   cd Empty
   ```

2. **Install Dependencies**
   ```bash
   composer install
   ```

3. **Environment Configuration**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Configure Database**
   - Edit `.env` file and add your database credentials
   ```
   DB_CONNECTION=mysql
   DB_HOST=127.0.0.1
   DB_PORT=3306
   DB_DATABASE=empty_db
   DB_USERNAME=root
   DB_PASSWORD=
   ```

5. **Run Migrations**
   ```bash
   php artisan migrate
   ```

6. **Start Development Server**
   ```bash
   php artisan serve
   ```
   The application will be accessible at `http://localhost:8000`

### Additional Commands
- Create new migration: `php artisan make:migration create_table_name`
- Create new model: `php artisan make:model ModelName`
- Create new controller: `php artisan make:controller ControllerName`

---

For more information, visit [Laravel Documentation](https://laravel.com/docs)
