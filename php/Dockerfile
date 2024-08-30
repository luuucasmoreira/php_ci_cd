FROM php:8.3-fpm-alpine
WORKDIR /var/www/html/php
# Instala extensões PHP
RUN docker-php-ext-install mysqli pdo_mysql

# Copia o código da aplicação
COPY . /var/www/html

RUN chown -R www-data:www-data /var/www/html
RUN chmod -R 755 /var/www/html