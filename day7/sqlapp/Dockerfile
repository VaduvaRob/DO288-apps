FROM mysql
   
COPY ..  
ENV MYSQL_DATABASE test
ENV MYSQL_USERNAME robertv
ENV MYSQL_PASSWORD robertv
ENV MYSQL_ROOT_PASSWORD robertv
ADD test.sql /docker-entrypoint-initdb.d
