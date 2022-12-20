FROM php:7.4-fpm

RUN docker-php-ext-install mysqli

WORKDIR /var/www/wordpress

RUN chown -R www-data:www-data /var/www/wordpress
