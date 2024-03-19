FROM mysql:latest
ENV MYSQL_ROOT_PASSWORD=1234
LABEL name="database"
COPY ./database.sql /docker-entrypoint-initdb.d/
