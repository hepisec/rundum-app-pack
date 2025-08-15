# rundum/app-pack

This is a meta package for PHP Symfony apps to install several dependencies at once.

The following packages are included:

- `scheb/2fa-bundle` and `scheb/2fa-google-authenticator` to support 2FA authentication
- `stof/doctrine-extensions-bundle` to provide useful extensions for Doctrine ORM
- `symfony/apache-pack` to setup the project for Apache2 (adds an .htaccess file)
- `symfony/uid` for UUID and ULID support
- `symfonycasts/verify-email-bundle` to verify email addresses during the signup process
- `pentatrion/vite-bundle` to build frontend assets with Vite

For development and testing, these additional packages are also included:

- `dama/doctrine-test-bundle` to efficiently run tests against a test database
- `friendsofphp/php-cs-fixer` to enforce code style
- `zenstruck/foundry` to write better tests
