FROM php:7.4.7-cli

COPY --from=composer:latest /usr/bin/composer /usr/bin/composer

RUN apt update && apt install -y zip unzip

