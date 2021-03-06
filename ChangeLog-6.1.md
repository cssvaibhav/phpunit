# Changes in PHPUnit 6.1

All notable changes of the PHPUnit 6.1 release series are documented in this file using the [Keep a CHANGELOG](http://keepachangelog.com/) principles.

## [6.1.0] - 2017-04-07

### Added

* Implemented [#2533](https://github.com/sebastianbergmann/phpunit/pull/2533): Implement configuration option to set a default test suite
* Implemented [#2541](https://github.com/sebastianbergmann/phpunit/issues/2541): Implement configuration option to ignore deprecated code from code coverage
* Implemented [#2546](https://github.com/sebastianbergmann/phpunit/issues/2546): Render `__FILE__` and `__DIR__` in `SKIPIF` section of PHPT tests

### Changed

* `.phar` files that are to be loaded as a PHPUnit extension must now have a valid `manifest.xml` file
* Details about risky tests are now always displayed

### Fixed

* Fixed [#2472](https://github.com/sebastianbergmann/phpunit/issues/2472): `PHPUnit\Util\Getopt` uses deprecated `each()` function

[6.1.0]: https://github.com/sebastianbergmann/phpunit/compare/6.0...6.1.0

