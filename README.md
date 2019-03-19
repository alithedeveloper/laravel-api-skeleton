# Laravel API Skeleton
This project should serve as a starting point for any future API development. It has already got some packages that could help in kickstarting the api development.

# Requirements

 - Laravel 5.8
 - PHP 7.2+

## Packages Used

Following is a list of packages that we are using in the project

|  Packages                        | Usage                                    |
|----------------------------------|------------------------------------------|
|Api Response Builder      |A light response helper for building nice, normalized and easy to consume REST API responses. Read more at  [Api Response Builder](https://github.com/MarcinOrlowski/laravel-api-response-builder) |
|IDE Helper                | It creates an _ide-helper file which helps in auto-completion and suggestions while working with Laravel.Read more at [Ide helper](https://github.com/barryvdh/laravel-ide-helper) |
|Telescope                 | Laravel package to get the overview of each request entering into application. Read more at [Laravel Telescope](https://laravel.com/docs/5.7/telescope)  |
|PHP Codesniffer         | Helps in formatting the code according to PSR-2 standards. Read more at [Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer)|
|Passport                   | To set up OAUTH2 server. Read more at [Laravel Passport](https://laravel.com/docs/5.7/passport)|
|Laravel Query Builder      | It allows to filter, sort and include database relationships based on a request. Read more at [Query Builder](https://github.com/spatie/laravel-query-builder)

## Useful Commands

Some useful commands that you can use in addition to other commands.

 - ```composer run-script clear-all```
   A handy command to clear whatever laravel cached.

 - ```vendor/bin/phpcs```
 Find any PSR-2 violations in project
 - ```venodr/bin/phpcbf```
 Fix PSR-2 violations which can be fixed automatically
 - ```php artisan ide-helper:generate```
 It will create an _ide-helper.php to help with auto-completion

 - ```php artisan security-check:now```
 It should help in finding out if there is any known vulnerability in packages we are utilizing at the moment.

## How to use ?

 - Make folder for the project that you are going to work on e.g. project
 - ```cd project```, navigat to the folder
 - Clone the repository into the folder by runing the command ```git clone git@github.com:alithedeveloper/laravel-api-skeleton.git .```
 - Remove the ```.git``` folder by runing the command, ``` rm -rf .git ```
 - Re-initialize git by runing the command ```git init && git add . && git commit -m"{descriptive message}" ```
 - Create a repository on github and follow the integration instructions