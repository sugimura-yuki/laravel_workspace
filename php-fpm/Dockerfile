FROM php:7.4.7-fpm-alpine

RUN apk add autoconf build-base && \
    pecl install redis-5.1.1 && \
    docker-php-ext-enable redis

RUN docker-php-ext-install bcmath pdo_mysql tokenizer
