### Docker file MySQL ##

# Use the official MySQL image from the Docker Hub
FROM mysql:8.0

# Set environment variables for MySQL
ENV MYSQL_ROOT_PASSWORD=Admin123
ENV MYSQL_DATABASE=database-1
ENV MYSQL_USER=admin
ENV MYSQL_PASSWORD=Admin123

# Expose MySQL port
EXPOSE 3306

# Copy the initialization script to the container
COPY test.sql /docker-entrypoint-initdb.d/

# Start MySQL server
CMD ["mysqld"]
