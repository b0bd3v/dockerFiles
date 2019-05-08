FROM php:7.3-apache
MAINTAINER Roberto Martins
WORKDIR /var/www/html
RUN docker-php-ext-install pdo pdo_mysql mysqli json xml
RUN a2enmod rewrite
