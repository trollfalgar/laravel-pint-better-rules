![Laravel Pint](https://raw.githubusercontent.com/laravel/pint/main/art/overview.png)

# Laravel Pint's Better Rules

This project is focused in create the best set of rules for Laravel Pint.

**Laravel Pint** is an opinionated PHP code style fixer for minimalists. Pint is built on top of [PHP-CS-Fixer](https://github.com/FriendsOfPHP/PHP-CS-Fixer) and makes it simple to ensure that your code style stays clean and consistent.

## Preset and Rules

- By default, the preset used is **PER**, a new and modern preset over the PSR12. But you can change to `laravel`, `psr12` or even `symfony`.
- This preset was chosen by my personal preference, you can use what ever you want.
- The set of rules applied in this configuration was chosen to a clean, organized and modern code.

## Laravel Pint Official Documentation

Documentation for Pint can be found on the [Laravel website](https://laravel.com/docs/pint).
The project page on Github can be found [here](https://github.com/laravel/pint).

## How to Use

1. Install Laravel Pint
   - `composer require laravel/pint --dev`
   - In Laravel version 9.21 and newers, the package comes officially on new installations.
2. Clone the project or download the file `pint.json` and place it in the root folder of your project.
   - If you want place the file in another folder, no problem. When you run the `pint` command, pass the argument like this ` --config the/path/to/pint.json`
3. Run the command `./vendor/bin/pint` with or without arguments and **DONE**!

## Warning
Laravel Pint require PHP 8 or higher.
