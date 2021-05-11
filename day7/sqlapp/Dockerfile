FROM mysql:latest     
COPY . .       
ENV MYSQL_USER robertv
ENV MYSQL_PASSWORD robertv   
ENV MYSQL_ROOT_PASSWORD robertv   
ENV MYSQL_DATABASE test  
ADD test.sql /docker-entrypoint-initdb.d
