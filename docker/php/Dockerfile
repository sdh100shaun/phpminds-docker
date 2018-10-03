FROM php:7.2.10-fpm

RUN apt-get update && apt-get install -y \
    && docker-php-ext-install -j$(nproc) pdo pdo_mysql

CMD ["php-fpm","-F"]

