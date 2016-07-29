FROM php:7.0-fpm

RUN docker-php-ext-configure pdo_mysql --with-pdo-mysql=mysqlnd && \
    docker-php-ext-configure mysql --with-mysql=mysqlnd && \
    docker-php-ext-configure mysqli --with-mysqli=mysqlnd && \ 
    docker-php-ext-install mysql mysqli pdo pdo_mysql
