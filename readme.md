<p align="center">
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Article API

## Quick Start

``` bash
# Add virtual host if using Apache

# Install Dependencies
$ composer install

# Update the classes if needed
$ composer dump-autoload

# Run Migrations
$ php artisan migrate

# Link the [public/storage] directory [storage/app/public]
$ php artisan storage:link
  - upload image to post
  - copy 'noimage.jpg' to [storage/app/public]

# Install Laravel Passport
$ composer require laravel/passport

# Fully install Laravel Passport
$ php artisan migrate
$ php artisan passport:install

# Package manager for the Node JavaScript platform
$ npm install

# Import Articles
$ php artisan db:seed

# If you get an error about an encryption key
$ php artisan key:generate
```

## Endpoints

### List all articles with links and meta
``` bash
GET api/articles
```
### Get single article
``` bash
GET api/article/{id}
```

### Delete article
``` bash
DELETE api/article/{id}
```

### Add article
``` bash
POST api/article
title/body
```

### Update article
``` bash
PUT api/article
article_id/title/body
```

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, yet powerful, providing tools needed for large, robust applications.


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
