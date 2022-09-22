# **[Bitsnbolts Feed](https://bitsnbolts.com) package**

[![License](https://poser.pugx.org/bitsnbolts/feed/license)](https://packagist.org/packages/bitsnbolts/feed) [![PHP tests](https://github.com/Bitsnbolts/laravel-feed/workflows/PHP%20tests/badge.svg?branch=master)](https://github.com//Bitsnbolts/laravel-feed/actions?query=workflow%3A%22PHP+tests%22) [![Test Coverage](https://api.codeclimate.com/v1/badges/4c293ed962c1328bfcfc/test_coverage)](https://codeclimate.com/github/Bitsnbolts/laravel-feed/test_coverage) [![Maintainability](https://api.codeclimate.com/v1/badges/4c293ed962c1328bfcfc/maintainability)](https://codeclimate.com/github/Bitsnbolts/laravel-feed/maintainability) [![Style Status](https://github.styleci.io/repos/10391723/shield?style=normal&branch=master)](https://github.styleci.io/repos/10391723) [![Latest Stable Version](https://poser.pugx.org/bitsnbolts/feed/v/stable)](https://packagist.org/packages/bitsnbolts/feed) [![Total Downloads](https://poser.pugx.org/bitsnbolts/feed/downloads)](https://packagist.org/packages/bitsnbolts/feed)

*Bitsnbolts Feed package for Laravel.*

## Notes

- Dev branches are for development and are **UNSTABLE** (*use on your own risk*)!

## Installation

Run the following command and provide the latest stable version (e.g v8.\*) :

```bash
composer require bitsnbolts/feed
```

or add the following to your `composer.json` file :

#### For Laravel 8
```json
"bitsnbolts/feed": "8.*"
```
(development branch)
```json
"bitsnbolts/feed": "8.x-dev"
```

#### For Laravel 7
```json
"bitsnbolts/feed": "7.*"
```
(development branch)
```json
"bitsnbolts/feed": "7.x-dev"
```

#### For Laravel 6
```json
"bitsnbolts/feed": "6.*"
```
(development branch)
```json
"bitsnbolts/feed": "6.x-dev"
```

#### For Laravel 5.8
```json
"bitsnbolts/feed": "3.1.*"
```
(development branch)
```json
"bitsnbolts/feed": "3.1.x-dev"
```

#### For Laravel 5.7
```json
"bitsnbolts/feed": "3.0.*"
```
(development branch)
```json
"bitsnbolts/feed": "3.0.x-dev"
```

#### For Laravel 5.6
```json
"bitsnbolts/feed": "2.12.*"
```
(development branch)
```json
"bitsnbolts/feed": "2.12.x-dev"
```

#### For Laravel 5.5
```json
"bitsnbolts/feed": "2.11.*"
```
(development branch)
```json
"bitsnbolts/feed": "2.11.x-dev"
```

Publish package views (OPTIONAL) :

```bash
php artisan vendor:publish --provider="Bitsnbolts\Feed\FeedServiceProvider"
```

## Examples

[How to generate basic feed (with optional caching)](https://github.com/Bitsnbolts/laravel-feed/wiki/basic-feed)

[How to generate multiple feeds](https://github.com/Bitsnbolts/laravel-feed/wiki/Multiple-Feeds)

[How to add images to your feed](https://github.com/Bitsnbolts/laravel-feed/wiki/How-to-add-images-to-your-feed)

[How to use custom view for your feed](https://github.com/Bitsnbolts/laravel-feed/wiki/How-to-use-custom-view)

[How to use custom content-type for your feed](https://github.com/Bitsnbolts/laravel-feed/wiki/How-to-use-custom-content-type)

and more in the [Wiki](https://github.com/Bitsnbolts/laravel-feed/wiki)

## Contribution guidelines

Before submiting new merge request or creating new issue, please read [contribution guidelines](https://github.com/Bitsnbolts/laravel-feed/blob/master/CONTRIBUTING.md).

## License

This package is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
