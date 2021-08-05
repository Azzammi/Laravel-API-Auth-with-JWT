## Laravel 8 API With JWT Authentication

Using Laravel 

The tutorial [here](https://blog.pusher.com/laravel-jwt/) 

To deliver you app on a server, you have to (on you dev environement) :

  * Git clone the tag/branch that you want to deliver
  * Launch the command `composer install`
  * Rename `env.example` to `env`
  * Adjust di env file
  * run `php artisan key:generate`
  * Create sqlite file
```
touch database/database.sqlite
```
  * run `php artisan migrate:fresh --seed`
  * and just run `php artisan serve`


That's all, you have a beautifull package that can be deliver on a server 
