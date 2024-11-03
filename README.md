# PHP Project Template

A most basic PHP project template with [PHPUnit](https://phpunit.de/), [PHPStan](https://phpstan.org/), and [PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer#about) ready to roll.  The project will be [ISC-licensed](https://en.wikipedia.org/wiki/ISC_license) by default.

Additionally, the following Composer scripts are included to help you quickly get going.

- `composer app:dev:test`: runs the PHPUnit unit tests
- `composer app:dev:analyse`: runs PHPStan at level 11
- `composer app:dev:lint`: runs PHP_CodeSniffer
- `composer app:dev:check-quality`: runs the PHPUnit unit tests, PHPStan, and then PHP_CodeSniffer

## Instructions

Run `composer create-project danbettles/php-project-template <path>` &mdash; substituting `<path>` with the pathname of the directory you'd like created &mdash; and then:

- Replace "php-project-template" with the name of your Git repository
- Replace "PHP Project Template" with the name of your project
- Except in `phpcs.xml`, replace "DanBettles" with your vendor namespace
- Replace "PhpProjectTemplate" with the namespace of your app
- In `composer.json`, update the type of the package &mdash; if need be
- Update the year and name in `LICENSE`
- Rewrite this file
- Run `composer update`
- Start building from `tests/SomethingTest.php` and `src/Something.php`
