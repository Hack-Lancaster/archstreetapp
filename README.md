# Readme

This project is built on Symfony 2.7.x.

## Prerequisites:

- Git
- PHP >= 5.4.x
- MySQL ~5.5
- Composer
- Ruby 2.x (for frontend work only)
- Bundler

## Getting Started:

- Clone repository
- Run `bundle` to download Ruby gems.  **Note:** The sass gem must be installed in `.gems` in the root of the project so Symfony can find it. Rbenv config files are included to help with this.
- Run `composer install` to download and configure the framework
- Run `php app/check.php` to check your environment. Fix any errors.
- Run `php app/console doctrine:migrations:migrate` to migrate your database to the latest migration.
- Run `php app/console assetic:dump` to compile web assets (sass and js)
- Run `php app/console server:start` to start a local server on port 8000.
- Verify that http://localhost:8000/hello/you outputs 'Hello you'

**More docs coming soon.**

In the meantime: http://symfony.com/doc/current/index.html