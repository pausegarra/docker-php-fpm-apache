FROM php:7.2.7-fpm-alpine3.7

RUN apk update
RUN apk upgrade
RUN apk add --no-cache libxml2 libxml2-dev

RUN docker-php-ext-install mysqli
RUN docker-php-ext-install json
RUN docker-php-ext-install mbstring
RUN docker-php-ext-install pdo_mysql
RUN docker-php-ext-install xml
RUN docker-php-ext-install zip