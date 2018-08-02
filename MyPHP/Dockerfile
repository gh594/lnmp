FROM php:7.2-fpm
MAINTAINER alan
ENV TZ "Asia/Shanghai"
RUN ["docker-php-ext-install", "mysqli"]
RUN pecl install redis-4.0.1 \
    && docker-php-ext-enable redis
EXPOSE 9000
CMD ["/usr/local/sbin/php-fpm"]
