<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# Laravel E-Commerce API

A backend API for an e-commerce platform built with Laravel. It handles products, categories, login, register ..etc. Designed to serve mobile or web frontends with secure and scalable RESTful endpoints.

# Installation:

Step 1: Clone the Repository
```
git clone https://github.com/pinmonyvicheaa/api-laravel.git
cd api-laravel
```

Step 2: Install Dependencies
```
composer install
```

Step 3: Copy .env File
```
cp .env.example .env
```

Step 4: Set Your Environment Variables

- Edit .env file and set your database credentials:
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_database_name
DB_USERNAME=your_db_user
DB_PASSWORD=your_db_password
```

Step 5: Generate Application Key
```
php artisan key:generate
```

Step 6: Run Migrations

- This will create the necessary tables in your database:
```
php artisan migrate
```
- (Optional) Seed the Database [If you have seeders]:
 ```
php artisan migrate --seed
```
