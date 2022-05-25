FROM php:fpm
LABEL version="1.0"
LABEL author="@edt ASIX-M06"
LABEL subject="PHP host"
ARG DEBIAN_FRONTEND=noninteractive
RUN docker-php-ext-install mysqli
COPY extagram.php /var/www/html/extagram.php 
#CMD startup.sh
