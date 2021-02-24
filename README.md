# Commands

**Docker up**

```
$ docker-compose up -d --build
```

<br>

**Enter inside app container**

```
$ docker-compose exec app bash
```

<br>

**Install the laravel or Composer install**

```
[app] $ composer create-project --prefer-dist "laravel/laravel=6.*" .
[app] $ composer install
```

<br>

**copy the .env file**

```
$ cp .env.example backend/.env
```

<br>

**Create application key**

```
$ php artisan key:generate
```

<br>

**Edit the config file**

```
'timezone' => 'Asia/Tokyo',
'locale' => 'ja',
```

<br>

**npm install and run dev**

```
$ npm install
$ npm run dev
```
