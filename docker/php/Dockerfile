FROM php:8.4-apache

RUN apt update 
RUN apt install git zip unzip libxml2-dev -y

RUN docker-php-ext-install pdo_mysql 

RUN a2enmod rewrite
RUN service apache2 restart

COPY --from=composer:latest /usr/bin/composer /usr/bin/composer
ENV COMPOSER_ALLOW_SUPERUSER=1

WORKDIR /var/www/html