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

## Project Background:

Arch Street Center exists to promote the general well-being of adults experiencing serious mental health issues and emotional problems by providing a gathering place with an atmosphere that is positive and supportive.
Members can enjoy social and recreational activities including anything from sharing a television program or listening to music with friends to a variety of day trips, group games, craft programs and guest speakers. A nourishing meal is provided each evening for a nominal donation.

## Project Goals:

Currently, Arch Street Center does all of their patient management, tracking, and reporting by hand or through Excel spreadsheets. They are seeking a web app that will let them automate and improve the efficiency of their most tedious tasks, so that more of their volunteers' efforts can be spent helping their members rather than repeating time-consuming manual efforts. This app will allow them to manage their members' physician referrals and intake information, track their visits to the Center as well as the activities they participate in while there, and generate reports that can be sent to the county for funding purposes and also for internal/community use.
