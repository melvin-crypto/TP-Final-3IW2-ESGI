FROM php:8-fpm-alpine
# Image php apache habituelle

# install de la librairie mysqli pour le php
RUN docker-php-ext-install mysqli pdo pdo_mysql
# Activation de mysql sur le serveur
RUN docker-php-ext-enable mysqli

#creer un composer
COPY --from=composer:latest /usr/bin/composer /usr/local/bin/composer

EXPOSE 9000