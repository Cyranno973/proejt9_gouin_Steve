FROM mysql:8.0.21

MAINTAINER me

ENV MYSQL_DATABASE=mediscreen \
    MYSQL_ROOT_PASSWORD=root

ADD 01.sql /docker-entrypoint-initdb.d

EXPOSE 3306