FROM php:8.0.0RC3-fpm-alpine
RUN apk --update --no-cache add git gmp-dev
RUN docker-php-ext-install pdo_mysql ctype gmp bcmath
RUN curl -sS https://getcomposer.org/installer | php -- --filename=composer --install-dir=/bin
ENV PATH /root/.composer/vendor/bin:$PATH
WORKDIR /var/www
CMD composer install ;  php-fpm
EXPOSE 9000
