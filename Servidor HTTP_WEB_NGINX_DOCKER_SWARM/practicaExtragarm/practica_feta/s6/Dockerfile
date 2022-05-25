FROM nginx:stable-alpine
LABEL version="1.0"
LABEL author="@edt ASIX-M06"
LABEL subject="NGINX host"
ARG DEBIAN_FRONTEND=noninteractive
COPY style.css /var/www/html/style.css
COPY preview.svg /var/www/html/preview.svg
COPY default.conf /etc/nginx/conf.d/default.conf
#CMD startup.sh
