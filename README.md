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

**Install the laravel**

```
[app] $ composer create-project --prefer-dist "laravel/laravel=6.*" .
```

<br>

**Edit the config file**

```
'timezone' => 'Asia/Tokyo',
'locale' => 'ja',
```

<br>

**copy the .env file**

```
$ cp .env.example backend/.env
```
