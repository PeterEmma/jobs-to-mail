web: vendor/bin/heroku-php-nginx -C nginx.conf public/
queue: php artisan queue:work database --sleep=3 --tries=3 --timeout=0
