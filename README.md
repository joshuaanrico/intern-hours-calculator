# Intern Hours Calculator

A small Laravel web app that lets an intern log a working day (date, start time, end time, task, blockers) and calculates the hours worked, adding each day to a results table.

Built in two days in May 2020 as the technical test for the Campuspedia web developer internship.

## Pages

- **Home:** what the app is for, with a link to the calculator.
- **Services:** the work-hours form and results table. The calculation runs in the browser with plain JavaScript.
- **About**

## Stack

Laravel 7 (PHP 7.2+), Blade templates, Bootstrap, JavaScript.

## Run locally

Needs PHP 7.2 or later and Composer.

```bash
git clone https://github.com/joshuaanrico/intern-hours-calculator.git
cd intern-hours-calculator
composer install
cp .env.example .env
php artisan key:generate
php artisan serve
```

Then open http://127.0.0.1:8000. No database is needed for the calculator.

## Note

This is an early project, kept as it was submitted. The interface text is in Indonesian.
