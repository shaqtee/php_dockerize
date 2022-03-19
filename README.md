## Konfigurasi Simpel Docker untuk Laravel

Laravel : Masukin project laravel ke folder src.
Wordpress : Bikin folder public dalam folder src masukin project wordpressnya.

## Penggunaan

[startup]
docker-compose build && docker-compose up -d
[destroy]
docker-compose down

[docker-compose run --rm][npm|composer]['command']
docker-compose run --rm npm -v
docker-compose run --rm composer -v

[docker-compose exec php]['command']
docker-compose exec php php artisan
docker-compose exec php php -v

## Permission

chmod 777 -R storage storage
chmod 777 -R storage bootstrap/cache

[whoami]
chown -R root:root storage
chown -R root:root bootstrap/cache

EnjoyIt!
