# 1. Base Image: We use a lightweight, official Nginx web server
FROM nginx:alpine

# 2. Application Code: We copy the HTML file from our local 'app' folder 
# into the standard Nginx hosting directory inside the container
COPY app/index.html /usr/share/nginx/html/index.html

# 3. Port: We expose port 80 so traffic can reach the web server
EXPOSE 80
