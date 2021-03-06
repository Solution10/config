# Solution10\Config

This is a tiny, lightning fast way of defining configuration for your app.

This is deliberately bare-bones and not swamped with options / parsers. The focus is
on speed and lightness, whilst still retaining vital features.

[![Build Status](https://travis-ci.org/Solution10/config.svg?branch=master)](https://travis-ci.org/Solution10/config)
[![Latest Stable Version](https://poser.pugx.org/solution10/config/v/stable.svg)](https://packagist.org/packages/solution10/config)
[![Total Downloads](https://poser.pugx.org/solution10/config/downloads.svg)](https://packagist.org/packages/solution10/config)
[![License](https://poser.pugx.org/solution10/config/license.svg)](https://packagist.org/packages/solution10/config)

- [Features](#features)
- [Installation](#installation)
- [Documentation](#documentation)
    - [Userguide](#userguide)
- [PHP Requirements](#php-requirements)
- [Author](#author)
- [License](#license)

## Features

- No dependencies
- PHP 5.6, 7.0, 7.1 and HHVM support
- Lightning fast
- Extremely light
- Inheritance; define a base config and override per-environment

## Installation

Installation is via composer, in the usual manner:

```sh
$ composer require solution10/config
```

## Documentation

Check out the docs/ folder in the repo.

## PHP Requirements

- PHP >= 5.6
    - (If you require 5.3 support, versions up to 1.2.0 supported 5.3)
    - (if you require < 5.6 support, versions up to 2.1 supported 5.4 & 5.5)

## Author

Alex Gisby: [GitHub](http://github.com/alexgisby), [Twitter](http://twitter.com/alexgisby)

## License

[MIT](http://github.com/solution10/config/tree/master/LICENSE.md)
