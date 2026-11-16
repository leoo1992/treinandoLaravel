# Laravel Practice

A study project based on the Laravel 8 application skeleton, with initial authentication through Laravel Breeze and routes for the home page and authenticated dashboard. The current code retains the framework's starter structure.

## Stack
- PHP 7.3+ / 8.x
- Laravel 8
- Laravel Breeze and Sanctum
- Composer

## Run

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan serve
```

Configure the database in `.env` before running migrations.
