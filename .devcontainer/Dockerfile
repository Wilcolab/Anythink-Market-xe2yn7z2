FROM dockware/dev:latest

# Set the working directory in the container
WORKDIR /var/www/html

# Copy the current directory contents into the container
COPY . .

# Install any needed packages specified in requirements.txt
RUN composer install

# Make port 80 available to the world outside this container
EXPOSE 80

# Define environment variable
ENV NAME Shopware

# Run app.py when the container launche