# PHP Project Template

A most basic PHP project template with PHPUnit and PHP_CodeSniffer ready to roll.  The project is ISC-licensed by
default.

Additionally, the following Composer scripts are included to help you quickly get going.

- `composer app:test`: runs the PHPUnit unit tests.
- `composer app:lint`: runs PHP_CodeSniffer.
- `composer app:check-quality`: runs the PHPUnit unit tests and then PHP_CodeSniffer.

## Instructions

- Replace "php-project-template" with the name of your Git repository.
- Replace "PHP Project Template" with the name of your project.
- Except in `phpcs.xml`, replace "DanBettles" with your vendor namespace.
- Replace "PhpProjectTemplate" with the namespace of your app.
- Run `composer update`.
- Update the year and name in `LICENSE`.
- Rewrite this file.
- Start building from `tests/SomethingTest.php` and `src/Something.php`.
