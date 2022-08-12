FROM php:7.4-fpm

RUN apt-get update -y && apt-get install -y libpng-dev libbz2-dev libmcrypt-dev libxml2-dev imagemagick

RUN docker-php-ext-install gd bz2 mysqli pdo_mysql soap

USER 1000