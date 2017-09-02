FROM php:7.1.1-fpm

RUN apt-get update && apt-get install -y libmcrypt-dev curl nano zip

RUN docker-php-ext-install pdo_mysql

