FROM mysql:5.7
COPY scripts/orderdb.sql /docker-entrypoint-initdb.d/orderdb.sql

ENV MYSQL_DATABASE orderdb 
ENV MYSQL_USER navanath 
ENV MYSQL_PASSWORD pass@1234 
ENV MYSQL_ROOT_PASSWORD rootPass@1234