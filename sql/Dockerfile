FROM mysql:latest

WORKDIR /app

COPY beer.sql /docker-entrypoint-initdb.d/

ENV MYSQL_ROOT_PASSWORD=root
ENV MYSQL_DATABASE=beer