<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Laravel RESTful API Project

## About This Project

This project is a RESTful API built with Laravel and SQLite for easy access and management of data. It provides a robust foundation for building scalable and maintainable web applications.

## Features

- **Laravel Framework**: Utilizes the powerful and flexible Laravel framework.
- **SQLite Database**: Simplifies database setup and management with SQLite.
- **RESTful API**: Provides a clean and consistent interface for interacting with data.

## Getting Started

### Prerequisites

- PHP 7.4 or higher
- Composer
- SQLite

### Installation

1. **Clone the repository**:
    ```sh
    git clone (https://github.com/zerakjamil/restfull-task-api.git)
    cd restfull-task-api
    ```

2. **Install dependencies**:
    ```sh
    composer install
    ```

3. **Set up environment variables**:
    - Copy the `.env.example` file to `.env`:
        ```sh
        cp .env.example .env
        ```
    - Update the `.env` file with your database configuration. For SQLite, you can leave the default settings.

4. **Run migrations and seed the database**:
    ```sh
    php artisan migrate --seed
    ```

5. **Start the development server**:
    ```sh
    php artisan serve
    ```

## Testing the API

To test the API endpoints, you can use the provided Postman collection. Import the following link into your Postman application:

[Postman Collection](https://api.postman.com/collections/28087875-0f836d0b-0a4a-4b52-b501-06d67d0e793d?access_key=PMAT-01HZPSY6V9H23H52B4SHPTB739)
