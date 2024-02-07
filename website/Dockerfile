# Use an official PHP runtime as a parent image
FROM  php:7.4-apache

# Set the working directory in the container
WORKDIR /var/www/html
ENV APACHE_RUN_DIR /var/run/apache2

# Copy PHP files from the website folder into the container
COPY . /var/www/html/

# Install any needed dependencies
# RUN commands to install additional PHP extensions, if required

# Expose port 80 to the outside world
EXPOSE 80

# Start Apache when the container launches
CMD ["apache2-foreground"]

