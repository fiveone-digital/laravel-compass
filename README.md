<p align="center"><img src="https://res.cloudinary.com/dave24hwj8/image/upload/v1585775689/new-laravel-compass-logo.svg"></p>

<p align="center">
<a href="https://github.com/davidhsianturi/laravel-compass/actions"><img src="https://github.com/davidhsianturi/laravel-compass/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/davidhsianturi/laravel-compass"><img src="https://img.shields.io/packagist/dt/davidhsianturi/laravel-compass" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/davidhsianturi/laravel-compass"><img src="https://img.shields.io/packagist/v/davidhsianturi/laravel-compass" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/davidhsianturi/laravel-compass"><img src="https://img.shields.io/packagist/l/davidhsianturi/laravel-compass" alt="License"></a>
</p>

<p align="center">
<kbd>
<img src="https://res.cloudinary.com/dave24hwj8/image/upload/v1585775692/Screen_Shot_2020-04-02_at_16.05.24_PM.png">
</kbd>
</p>

## Introduction

Laravel Compass is an elegant REST assistant for the Laravel framework that you can use to test API calls and create API documentation. it provides automatically endpoints for GET, POST, PUT/PATCH, DELETE, various auth mechanisms, and other utility endpoints based on Laravel routes in your project.

## Installation and usage

In order to install the package, you need add following repositories to your composer file.
```json
    "repositories": {
        "fiveone-digital/laravel-compass": {
            "type": "vcs",
            "url": "git@github.com:fiveone-digital/laravel-compass.git"
        },
        "fiveone-digital/documentarian": {
            "type": "vcs",
            "url": "git@github.com:fiveone-digital/documentarian.git"
        }
    }
```

and then run following composer require commands
```
	composer require fiveone-digital/documentarian
	composer require fiveone-digital/laravel-compass
```
This package requires PHP 8.1 and Laravel 9.0 or higher.  
 
## Changelog

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## License

Laravel Compass is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
