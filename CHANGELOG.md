# Changelog

All notable changes to `laravel-link-checker` will be documented in this file

## 4.4.0 2024-06-29

- update spatie/crawler to 8.2.0

## 4.3.0 2024-06-29

- support laravel 11
- support php 8.2

## 4.2.0 2019-11-26

- remove support for older php versions
- remove support for older laravel versions
- support laravel 5.8 and 6

## 4.1.1 - 2018-08-27

- add support for Laravel 5.7
- fix mail when broken urls are found

## 4.1.0 - 2018-04-26

- add client options to config file

## 4.0.0 - 2018-03-20

- Update to `spatie/crawler ^4.0`
- Drop `illuminate/support ~5.5.0` support

## 3.0.0 - 2018-02-12

- Update to `spatie/crawler ^3.0`
- Support Laravel 5.5 and 5.6

## 2.4.0 - 2018-01-17
- add `exclude_status_codes`

## 2.3.0 - 2018-01-17
- add "found on" in the `MailBrokenLinks` reporter

## 2.2.2 - 2017-10-24
- fix mail

## 2.2.1 - 2017-10-14
- permissions fix

## 2.2.0 - 2017-09-29
- add subject line to email

## 2.1.0 - 2017-09-29
- fix incorrect tagged versions
- improve speed by crawling the app with multiple concurrent connections
- add autodiscovery for Laravel 5.5

## 1.1.0 - 2017-06-29
**THIS VERSION WAS TAGGED INCORRECTLY, DO NOT USE**

- add autodiscovery for Laravel 5.5

## 1.0.5 - 2017-06-29
**THIS VERSION WAS TAGGED INCORRECTLY, DO NOT USE**
- remove hidden `laravel-collective/html` dependency

## 1.0.4 - 2017-01-19
**THIS VERSION WAS TAGGED INCORRECTLY, DO NOT USE**

- remove another typehint on a protected method

## 1.0.3 - 2017-01-19
**THIS VERSION WAS TAGGED INCORRECTLY, DO NOT USE**

- remove typehint from `isSuccessOrRedirect`

## 1.0.2 - 2016-12-03
**THIS VERSION WAS TAGGED INCORRECTLY, DO NOT USE**

- improve speed by crawling the app with multiple concurrent connections

## 1.0.1 - 2015-12-03

- The mail reporter now only reports broken urls

## 1.0.0 - 2015-11-25

- Initial release
