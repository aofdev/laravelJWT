# Laravel JSON Web Token Example

> Laravel 5.4 API with JWT project

# Setup

``` bash

#1 install composer dependencies 
composer install

#2 copy .env.example to .env
cp .env.example .env
(change the config in .env to match your environment settings( database username, password and database name ))

#3 Generating a New Application Key
php artisan key:generate

#4 Run migrations
php artisan migrate

#5 Run serve
php artisan serve

```


## References
 [jwt-auth](https://github.com/tymondesigns/jwt-auth)

