# nginx-php-docker-compose-template

## Using Image
* nginx:1.13-alpine
* php:7.2-fpm-alpine

## How to use
1. (Optional) Change `docker/nginx/nginx.conf` on your nginx settings.
2. (Optional) Change `docker/php-fpm/extra-php.ini` on your php settings.
3. (Optional) Custormize another settings. (change `docker-compose.yml`, add `docker-php-ext-enable`, etc...)
4. Run `docker-compose up --build`.
5. Check `http://localhost:8080` and `http://localhost:8080/phpinfo.php`.
6. Enjoy!
