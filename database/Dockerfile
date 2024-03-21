# Use official MySQL image as base
FROM mysql:latest

# Environment variables
ENV MYSQL_ROOT_PASSWORD=Gaurik15#
ENV MYSQL_DATABASE=notes

# Copy SQL script to initialize database
COPY notes.sql /docker-entrypoint-initdb.d/

# Expose port
EXPOSE 3306
