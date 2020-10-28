FROM mariadb

#Add a database
ENV MYSQL_DATABASE carsDB

#Add the content of the sql-scrpts/ directory to your image
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
COPY ./sql-scripts/ /docker-entrypoint-initdb.d/

EXPOSE 3306