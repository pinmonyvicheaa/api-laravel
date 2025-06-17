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

Step 9: Link Images
```
php artisan storage:link
```

- Now it should be running at:
```
http://127.0.0.1:8000
```

# Example Postman Test

- To test the API (e.g. login):
```
GET http://127.0.0.1:8000/api/login
```

- To test the API (e.g. add categories list):
```
POST http://127.0.0.1:8000/api/categories
```
++ Headers:
```
Key: Accept | Value: application/json
Key: Authorization | Bearer <Token> [Take from login]
```
