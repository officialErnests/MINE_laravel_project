# MADE WITH
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

# Little ramble about project:
SUPPER COOL LARAVEL LOGIN AND POST SITE
- Features:
- Register
- Login
- Logout
- Create event
- Edit event
- Delete event
 
What did i learn?
- Composer
- php /w laravel
- sqlite
- pgsql
- ssh
- tailwind
- npm
- nest

Story: <br>
So i made this originaly on laravel on pc and it was smooth sailing, well except the sqlite connection but i managed. Then i wanted to add some style so installed some tailwind for it, afterwards i was ready to submit, but sadly needed a demo link and after sugestion from pkd to host it on nest.. not knowingly i embarked on 4 day trip trying my hardest to get it working, first i tried vercel but no luck then my frend smil tried to help, also no luck, then i uploaded whole project to nest and had some issues with composer so i just also uploaded the downloaded files. Then i had some issues with database so i tried one day debug sqlite on server (with ssh on linux cli, on wich i have never worked on) after while i realised that in php.ini the extenstion po_sqlite isn't enabled so i had to switch to another sql onnection and i switched my whole laravel projet to postgres db (all it was just few lines that took me way too long to debug, since it was weird to install and test so in the end i had to make it half blind on ssh and it worked :DD) afterwards there was no css BUT I AM DONE, this already took me 4 days and just learned that laravel shouldn't be on nest even but it is now lol

ALSO no css since it keeps blocking each time it tries to acces it and idk how to get tailwind on server so live witouth it or just serve it yourself XD

ALSO NO AI, like  not even help i like pain raw >:))

# MAIN FILES
DB tables: https://github.com/officialErnests/MINE_laravel_project/tree/main/database/migrations
FB models: https://github.com/officialErnests/MINE_laravel_project/tree/main/app/Models
Controllers, aka request handling stuff: https://github.com/officialErnests/MINE_laravel_project/tree/main/app/Http/Controllers
Main website files: https://github.com/officialErnests/MINE_laravel_project/tree/main/resources/views
Main web trafick thingy: https://github.com/officialErnests/MINE_laravel_project/blob/main/routes/web.php

# HOW TO RUN
Create env file (you can see setups online)
As well setup your own db :))
In conosle run 
```
composer install
php artisan migrate:fresh
php artisan serve
```
then go to your local host and enjoy :DD
