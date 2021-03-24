# Setup Docker For Laravel (5, 6, 7 and 8)
Simple setup Docker, for Laravel aplications.


## Up Containers
```console
docker-compose up -d nginx mysql phpmyadmin redis
```


## Run comands:
```console
docker-compose exec workspace bash
```

```console
cd project/
```

```console
php artisan comand
```


### Ref:
This setup is inspired in [laradock](https://github.com/laradock/laradock)