FROM php:7.3-fpm-alpine

RUN docker-php-ext-install bcmath mysqli pdo_mysql

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/local/bin --filename=composer

RUN apk add --no-cache nodejs npm

WORKDIR /app
