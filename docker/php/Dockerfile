FROM php:7.4-fpm-alpine

COPY --from=composer /usr/bin/composer /usr/bin/composer

RUN apk update
RUN apk add git && docker-php-ext-install pdo_mysql

WORKDIR /var/www/html