Setup commands:
1. docker-compose up -d --build
2. docker cp ./LocalSettings.php php_base_name-php-fpm:/var/www/html/
3. docker-compose exec php-fpm bash
4. php ./maintenance/update.php
5. Restart containers, than copy LocalSettings.php again.
