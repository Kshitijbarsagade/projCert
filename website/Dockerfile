# Use an official PHP runtime as a parent image
FROM  devopsedu/webapp

# Set the working directory in the container
WORKDIR /var/www/html

# Copy PHP files from the website folder into the container
COPY index.php /var/www/html/

# Install any needed dependencies
# RUN commands to install additional PHP extensions, if required

# Expose port 80 to the outside world
EXPOSE 80

# Start Apache when the container launches
CMD ["apache2", "-D", "FOREGROUND"]

