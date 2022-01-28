# Use the Nginx image
FROM nginx

# Remove the default nginx.conf
RUN rm /etc/nginx/conf.d/default.conf

COPY . /etc/nginx/html

# Replace with our own nginx.conf
COPY nginx.conf /etc/nginx/conf.d/