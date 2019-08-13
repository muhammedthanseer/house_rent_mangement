# house_rent_mangement
Installation and use
HRM is build using Laravel 5.3
$ git clone https://github.com/muhammedthanseer/house_rent_mangement.git
$ cd HRM
$ mv .env.example .env
Change configuration in .env according your need and create Database

$ composer install
$ php artisan migrate
$ php artisan db:seed
$ php artisan storage:link
Give write permission to storage and bootstrap/cache directory

$ php artisan serve
http://localhost:8000 
USER: admin@hrm.com 
PASS: demo123
