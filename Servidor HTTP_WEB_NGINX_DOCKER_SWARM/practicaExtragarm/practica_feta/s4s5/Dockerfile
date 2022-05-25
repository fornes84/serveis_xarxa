FROM php:fpm
LABEL version="1.0"
LABEL author="@edt ASIX-M06"
LABEL subject="PHP host"
RUN apt-get update
ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get -y install procps iproute2 tree nmap vim less finger passwd
COPY upload.php /var/www/html/upload.php 
#CMD startup.sh
