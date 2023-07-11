<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# Database

php artisan make:migration create_products_table

-   rollback
    php artisan migrate:rollback --step=
-   Update
    php artisan make:migration update_name_column_users_table --table=users

refresh -> rollback -> chay lai migration
fresh -> drop -> chay migration
reset -> rollback

# Seeder

Tạo seeder : php artisan make:seeder UserSeeder
Chạy seeder :

-   php artisan db:seed

-   php artisan db:seed --class=UserSeeder trỏ đến seeder muốn chạy

Install ->
Công cụ debug

-   composer require barryvdh/laravel-debugbar --dev
-   postman
-   composer require laravel/telescope
    https://laravel.com/docs/10.x/telescope#main-content
