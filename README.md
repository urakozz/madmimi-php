# MadMimi for PHP
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/urakozz/madmimi-php/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/urakozz/madmimi-php/?branch=master)
[![Latest Stable Version](https://poser.pugx.org/kozz/madmimi-php/v/stable.svg)](https://packagist.org/packages/kozz/madmimi-php)
[![Latest Unstable Version](https://poser.pugx.org/kozz/madmimi-php/v/unstable.svg)](https://packagist.org/packages/kozz/madmimi-php)
[![License](http://img.shields.io/packagist/l/kozz/madmimi-php.svg)](https://packagist.org/packages/kozz/madmimi-php)

### Install with Composer

Simply add a dependency on `kozzz/madmimi-php` to your project's `composer.json` file if you use [Composer](http://getcomposer.org/) to manage the dependencies of your project. Here is a minimal example of a `composer.json` file that just defines a dependency:

    {
        "require": {
            "kozz/madmimi-php": "~1.0"
        }
    }


## Notes on basic usage:

```php
$mimi = new MadMimi('username', 'api_key');

$mimi->Promotions();

$mimi->Lists();
```

...and etc. For more detailed examples, see the Examples directory.

General Mad Mimi API documentation can be found at the [Mad Mimi developer's wiki.](http://madmimi.com/developer)

## Contributors
gorilla3d
lehresman

## License
(C) Copyright 2010 Mad Mimi, LLC <support@madmimi.com>
Released under the MIT License.
