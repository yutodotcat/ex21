FROM php:7.4-apache

# tzdata, xdebug install
RUN apt-get update && apt-get install -y \
    tzdata \
    && pecl install xdebug \
    && rm -rf /var/lib/apt/lists/*

# enviroment variable for setting timezone
ENV TZ=Asia/Tokyo

