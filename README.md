# Laravel Multiple Authentication
A simple implementation of multiple authentication in Laravel.

To follow along, this application has been documented as an article on Pusher blog. You can read about it [here](https://pusher.com/tutorials/multiple-authentication-guards-laravel)

## Set up
To set up this project, first clone the repositiory
```bash
$ git clone https://github.com/fisayoafolayan/laravel-multiple-auth.git
```

Change your working directory into the project directory
```bash
$ cd laravel-multiple-auth
```

Then install dependencies using [Composer](https://getcomposer.org/doc/00-intro.md)
```bash
$ composer install
```

Copy `.env.example` to `.env`
```bash
$ cp .env.example .env
```

Create the database file
```bash
$ touch database/database.sqlite
```

## Run
Run the application with the following command
```bash
$ php artisan serve
```

Remember to visit `http://localhost:8000/register/writer` and `http://localhost:8000/register/admin` to register writers and admins respectively. Then visit `http://localhost:8000/login/writer` and `http://localhost:8000/login/admin` to login the writers and admins respectively.

## Built With
[Laravel](https://laravel.com/) - The PHP Framework For Web Artisans.

[SQLite](https://en.wikipedia.org/wiki/SQLite) - A relational database management system.
