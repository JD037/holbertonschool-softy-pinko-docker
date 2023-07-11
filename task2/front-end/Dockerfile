# Use the latest version of nginx
FROM nginx:latest

# Copy the softy-pinko-front-end to the Docker image
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# Copy Nginx configuration file
COPY ./softy-pinko-front-end.conf  /etc/nginx/conf.d/default.conf
