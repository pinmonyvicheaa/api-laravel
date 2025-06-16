<p align="center"><a href="#" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# Laravel E-Commerce API

A backend API for an e-commerce platform built with Laravel. It handles products, categories, login, register ..etc. Designed to serve mobile or web frontends with secure and scalable RESTful endpoints.

# Installation:

Step 1: Clone the Repository
```
git clone https://github.com/pinmonyvicheaa/ecommerce-laravel-api.git
cd ecommerce-laravel-api
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

Step 7: (Optional) Seed the Database

- If you have seeders:
```
php artisan db:seed
```

Step 8: Serve the Application

- Start the Laravel development server:
```
php artisan serve
```

- Now it should be running at:
```
http://127.0.0.1:8000
```

# Example Postman Test

- To test the API (e.g. product list):
```
GET http://127.0.0.1:8000/api/products
```
