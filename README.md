# Foursquare Provider for OAuth 2.0 Client

[![Latest Version](https://img.shields.io/github/release/stevenmaguire/oauth2-foursquare.svg?style=flat-square)](https://github.com/stevenmaguire/oauth2-foursquare/releases)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/stevenmaguire/oauth2-foursquare/master.svg?style=flat-square)](https://travis-ci.org/stevenmaguire/oauth2-foursquare)
[![Coverage Status](https://img.shields.io/scrutinizer/coverage/g/stevenmaguire/oauth2-foursquare.svg?style=flat-square)](https://scrutinizer-ci.com/g/stevenmaguire/oauth2-foursquare/code-structure)
[![Quality Score](https://img.shields.io/scrutinizer/g/stevenmaguire/oauth2-foursquare.svg?style=flat-square)](https://scrutinizer-ci.com/g/stevenmaguire/oauth2-foursquare)
[![Total Downloads](https://img.shields.io/packagist/dt/stevenmaguire/oauth2-foursquare.svg?style=flat-square)](https://packagist.org/packages/stevenmaguire/oauth2-foursquare)

This package provides Foursquare OAuth 2.0 support for the PHP League's [OAuth 2.0 Client](https://github.com/thephpleague/oauth2-client).

## Installation

To install, use composer:

```
composer require stevenmaguire/oauth2-foursquare
```

## Usage

Usage is the same as The League's OAuth client, using `\Stevenmaguire\OAuth2\Client\Provider\Foursquare` as the provider.

### Authorization Code Flow

```php
$provider = new Stevenmaguire\OAuth2\Client\Provider\Foursquare([
    'clientId'          => '{foursquare-client-id}',
    'clientSecret'      => '{foursquare-client-secret}',
    'redirectUri'       => 'https://example.com/callback-url'
]);
```

For further usage of this package please refer to the [core package documentation on "Authorization Code Grant"](https://github.com/thephpleague/oauth2-client#usage).

## Testing

``` bash
$ ./vendor/bin/phpunit
```

## Contributing

Please see [CONTRIBUTING](https://github.com/stevenmaguire/oauth2-foursquare/blob/master/CONTRIBUTING.md) for details.


## Credits

- [Steven Maguire](https://github.com/stevenmaguire)
- [All Contributors](https://github.com/stevenmaguire/oauth2-foursquare/contributors)


## License

The MIT License (MIT). Please see [License File](https://github.com/stevenmaguire/oauth2-foursquare/blob/master/LICENSE) for more information.
