FROM mysql:latest     
COPY . .       
ENV MYSQL_USER user
ENV MYSQL_PASSWORD robertv   
ENV MYSQL_ROOT_PASSWORD admin   
ENV MYSQL_DATABASE test  
ADD test.sql /docker-entrypoint-initdb.d
