FROM php:7.2-apache

RUN groupadd test 
RUN useradd -ms /bin/bash Bordjah -g test
RUN apt-get update \
  && docker-php-ext-install pdo_mysql mysqli 
