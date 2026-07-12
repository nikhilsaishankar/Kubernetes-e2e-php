FROM mysql/mysql-server:5.7
COPY init.sql /docker-entrypoint-initdb.d/
EXPOSE 3306
ENV MYSQL_ROOT_PASSWORD=admin123
