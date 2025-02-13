<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel-API-CRUD-With-Authentication

User authentication (Registration, Login, Logout) example of Laravel API using Sanctum.

## Setup

### Step 1:

Clone the repository in your local directory

```
git clone https://github.com/OmonovSardorbek/Laravel-API-CRUD-With-Authentication.git
```

### Step 2:

Create .env file in your project root directory and copy all lines of codes from .env.example to .env.

Change following database and SMTP credentials according to your local MySQL or SQLite database.

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your_db_name
DB_USERNAME=root
DB_PASSWORD=
```


```
MAIL_MAILER=log
MAIL_HOST=127.0.0.1
MAIL_PORT=2525
MAIL_USERNAME=your_username
MAIL_PASSWORD=your_password
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS="hello@example.com"
MAIL_FROM_NAME="${APP_NAME}"
```


### Step 3:

Install composer dependencies

```
composer install
```

### Step 4:

Generate App_key for the Laravel Api

```
php artisan key:generate
```

### Step 5:

Migrate database

```
php artisan migrate
```

### Step 6:

Run the API

```
php artisan serve
```

### Step 7:

Use Postman to test the API for the register, login and logout process. The working API routes are:

Register

```
http://127.0.0.1:8000/api/register
```

Login

```
http://127.0.0.1:8000/api/login
```

Logout

```
http://127.0.0.1:8000/api/logout
```
![1](https://github.com/user-attachments/assets/d4ab92f5-25ad-4783-9696-ba69b743513e)
![2](https://github.com/user-attachments/assets/23b92c7e-269d-4175-ae81-a76f09b66cdf)
![3](https://github.com/user-attachments/assets/a25a2b8e-b720-47d6-b882-1446dab7851f)

