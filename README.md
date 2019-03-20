# Laravel 5.7 From Scratch
This course comes from [Laracasts](https://laracasts.com/). It's the [Laravel 5.7 From Scratch Series](https://laracasts.com/series/laravel-from-scratch-2018/). Documentation for Laravel can be found [here](https://laravel.com/docs/5.8).

## Episode 01: The Laravel Sell
Laravel is one of the most popular PHP Frameworks out there. Think of it like Ruby on Rails or Phoenix for Elixir. In this case, PHP is the language, Laravel is the framework. Just like Ruby is the language and Rails is the framework.

### Laravel Alternatives
- Symfony
- Cake PHP
- CodeIgnitor
- Zend

### Laravel Community
- [Laracasts](https://laracasts.com/)
  - Tutorials and podcasts
- [Laravel News](https://laravel-news.com/)
  - News and updates
- [Lara Jobs](https://larajobs.com/)
  - Job openings
- [Forge](https://forge.laravel.com/)
  - Servers for Deployment, built by the creator of Laravel
- [Envoyer](https://envoyer.io/)
  - Another Server option
- [Laravel Spark](https://spark.laravel.com/)
  - Boilerplates built with Laravel to help you get started
- [Laravel Nova](https://nova.laravel.com/)
  - CMS Style admin panel for Laravel Sites
- [Test Driven Laravel](https://course.testdrivenlaravel.com/)
  - Video course on building robust Laravel Applications
- [Servers For Hackers](https://serversforhackers.com/)
  - Site focused on providing the right servers for your application
- [O'Reilly Books](http://shop.oreilly.com/product/0636920044116.do)
  - Tons of books from O'Reilly on Laravel


## Episode 02: Initial Setup Requirements
[Grab Composer](https://getcomposer.org/)

To install Composer Globally, [run the install script](https://getcomposer.org/download/) on their site, then do the following command:
```bash
mv composer.phar /usr/local/bin/composer
```
This will move composer to a folder that will allow it to be accessed by any project

Install Laravel Globally
```bash
composer global require laravel/installer
```

Make sure Laravel can be accessed anywhere by adding this to your `.bash_profile` or similar bash commands file
```bash
export PATH=~/.composer/vendor/bin:$PATH
```

Issue this command to build the project
```bash
laravel new <project-name>
```


## Episode 03: Basic Routing
Use the `php artisan` command to see available commands

Run this command to spin up a server
```bash
php artisan serve
```
The site will appear at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

You will primarily use the `routes` folder and the `resources` folder

Create a new route:
```php
Route::get('/contact', function () {
    return view('contact');
});
```

Create a new view in the `resources/views` folder called `contact.blade.php`


## Episode 04: Blade Layout Files
- You can use `.` or `/` to denote folders

Layouts are created and extended to views
```php
@extends('layouts.default')
```

In a layout, you place a `@yield` for content

In a template, you place content inside a `@section`


## Episode 05: Sending Data To Your Views
- To get something from the query string, use `request('thing')`
- Laravel automatically escapes data for you
  - Data is usually escaped in the `{{ }}` syntax
  - To unescape data, use {!! !!}
- There are multiple, valid ways to pass data to views

## Episode 06:


## Episode 07:


## Episode 08:


## Episode 09:


## Episode 10:


## Episode 11:


## Episode 12:


## Episode 13:


## Episode 14:


## Episode 15:


## Episode 16:


## Episode 17:


## Episode 18:


## Episode 19:


## Episode 20:


## Episode 21:


## Episode 22:


## Episode 23:


## Episode 24:


## Episode 25:


## Episode 26:


## Episode 27:


## Episode 28:


## Episode 29:


## Episode 30:


## Episode 31:


## Episode 32:


## Episode 33:


## Episode 34:


## Episode 35:


## Episode 36:


## Episode 37:


## Episode 38:


