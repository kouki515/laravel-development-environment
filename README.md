# Laravel Template
**version 6.x**

<br>

# Commands
**Enter inside app container**
```
$ docker-compose exec app bash
```
<br>

**Install the library on the vendor**
```
[app] $ composer install
```
<br>

**Create .env file**
```
[app] $ cp .env.example .env
```
<br>

**Create application key**
```
[app] $ php artisan key:generate
```
<br>

**Execute migration**
```
[app] $ php artisan migrate
```