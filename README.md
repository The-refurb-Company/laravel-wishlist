# Laravel Wishlist

[![Latest Version on Packagist](https://img.shields.io/packagist/v/lamalama/laravel-wishlist.svg?style=flat-square)](https://packagist.org/packages/lamalama/laravel-wishlist)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/lamalama/laravel-wishlist/run-tests?label=tests)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![StyleCI](https://github.styleci.io/repos/268217938/shield?branch=master)](https://github.styleci.io/repos/268217938)
[![Total Downloads](https://img.shields.io/packagist/dt/lamalama/laravel-wishlist.svg?style=flat-square)](https://packagist.org/packages/lamalama/laravel-wishlist)

Make your models wishlistable. 

## Install

Via Composer

``` bash
$ composer require lamalama/laravel-wishlist
```

You can publish the migration with:
```bash
php artisan vendor:publish --provider="LamaLama\Wishlist\WishlistServiceProvider" --tag="migrations"
```

After publishing the migration you can create the `wishlist` table by running the migrations:

```bash
php artisan migrate
```

You can optionally publish the config file with:
```bash
php artisan vendor:publish --provider="LamaLama\Wishlist\WishlistServiceProvider" --tag="config"
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Credits

- [Mark de Vries](https://github.com/lamalamaMark)

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/lamalama/laravel-wishlist.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[link-packagist]: https://packagist.org/packages/lamalama/laravel-wishlist
