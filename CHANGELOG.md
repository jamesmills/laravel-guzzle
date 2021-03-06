# Changelog

All notable changes to `laravel-guzzle` will be documented in this file

## 2.1.0 - 2020-03-03

- added Laravel 7 support

## 2.0.0 - 2020-02-24

- [upgrade guide](https://github.com/Astrotomic/laravel-guzzle/pull/2#issue-378649298)
- added `default_client` and `clients` config keys
- added `\Astrotomic\LaravelGuzzle\Factory` as new core of the package
- changed `\Astrotomic\LaravelGuzzle\Facades\Guzzle` to pipe calls to the new factory
- dropped `guzzle()` helper function 
- renamed service-provider from `LaravelGuzzleServiceProvider` to `GuzzleServiceProvider`

## 1.0.1 - 2020-02-17

- upgrade guzzle to at least v6.3

## 1.0.0 - 2020-02-14

- initial release
