FROM mysql:latest
LABEL version="1.0"
LABEL author="@edt ASIX-M06"
LABEL subject="MYSQL host"
ARG DEBIAN_FRONTEND=noninteractive
COPY schema.sql /docker-entrypoint-initdb.d/schema.sql
